#-------------------------------------------------------------------------------------------------------------
# Copyright (c) Microsoft Corporation. All rights reserved.
# Licensed under the MIT License. See https://go.microsoft.com/fwlink/?linkid=2090316 for license information.
#-------------------------------------------------------------------------------------------------------------

# To fully customize the contents of this image, use the following Dockerfile instead:
# https://github.com/microsoft/vscode-dev-containers/tree/v0.117.1/containers/typescript-node-12/.devcontainer/Dockerfile
FROM registry.cn-shenzhen.aliyuncs.com/canbefree/docker-nodejs:1.0.0

# ** [Optional] Uncomment this section to install additional packages. **
#
# ENV DEBIAN_FRONTEND=noninteractive
# RUN apt-get update \
#    && apt-get -y install --no-install-recommends <your-package-list-here> \
#    #
#    # Clean up
#    && apt-get autoremove -y \
#    && apt-get clean -y \
#    && rm -rf /var/lib/apt/lists/*
# ENV DEBIAN_FRONTEND=dialog


RUN git config --global user.name "谢宇天" \
    && git config --global user.email "xieyt01@mingyuanyun.com" 

# RUN mkdir /root/.ssh
COPY .ssh /root/.ssh

RUN  chmod -R 600 /root/.ssh
