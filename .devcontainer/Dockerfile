FROM ://microsoft.com

# Install ADB and OpenSSH server
RUN apt-get update && apt-get install -y \
    android-tools-adb \
    openssh-server \
    && rm -rf /var/lib/apt/lists/*

# Expose SSH port internally
EXPOSE 22
