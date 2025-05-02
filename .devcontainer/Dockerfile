FROM ubuntu:22.04

# 安裝必要工具
RUN apt-get update && \
    apt-get install -y curl sbcl git emacs && \
    apt-get clean

# 設定預設工作目錄
WORKDIR /workspace

# 建立使用者
RUN useradd -m vscode
USER vscode
