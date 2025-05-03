FROM mcr.microsoft.com/devcontainers/base:ubuntu

RUN apt-get update && apt-get install -y \
    curl \
    openjdk-17-jdk \
    rlwrap \
    && rm -rf /var/lib/apt/lists/*

# Install Clojure CLI tools
RUN curl -O https://download.clojure.org/install/linux-install-1.11.1.1413.sh \
    && chmod +x linux-install-1.11.1.1413.sh \
    && ./linux-install-1.11.1.1413.sh \
    && rm linux-install-1.11.1.1413.sh
