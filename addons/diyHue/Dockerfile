FROM python:3.6-slim
ARG BUILD_ARCH=aarch64

COPY rootfs /

WORKDIR /opt/hue-emulator

# Install requirments
RUN apt-get update && \
    apt-get install --no-install-recommends -y nmap psmisc iproute2 libcoap-1-0-bin && \
    rm -rf /var/lib/apt/lists/* && \
    pip3 install --no-cache-dir -r requirements.txt && \
    mv ./entertainment-${BUILD_ARCH} ./entertain-srv && \
    ln -s $(which coap-client) /opt/hue-emulator/coap-client-linux && \
# Add Docker Build scripts
    chmod +x ./genCert.sh && \
# Remove unused binaries 
    find . -name 'entertain-*' ! -name 'entertain-srv' -delete && \
    find . -name 'coap-client-*' ! -name 'coap-client-linux' -delete && \
    mkdir export

CMD [ "python3", "-u", "/opt/hue-emulator/HueEmulator3.py", "--docker", "--debug"]
