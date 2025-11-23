
FROM mcr.microsoft.com/devcontainers/base:ubuntu-24.04

# 必要なパッケージをインストール
RUN apt-get update && apt-get install -y \
    curl wget unzip git \
    && apt-get clean && rm -rf /var/lib/apt/lists/*
