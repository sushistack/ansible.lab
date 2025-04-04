FROM mcr.microsoft.com/devcontainers/base:ubuntu

# 필수 패키지 설치
RUN apt-get update && apt-get install -y \
    ansible \
    git \
    openssh-client \
    sshpass \
    python3-pip \
    && apt-get clean

# Ansible 사용 시 편의를 위한 기본 디렉토리 생성
RUN mkdir -p /workspace/inventory /workspace/playbooks
WORKDIR /workspace