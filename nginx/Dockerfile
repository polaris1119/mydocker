FROM nginx:1.18.0
LABEL maintainer="polaris@studygolang.com"

# set timezone
ENV TZ=Asia/Shanghai
RUN ln -snf /usr/share/zoneinfo/$TZ /etc/localtime && echo $TZ > /etc/timezone && useradd --create-home --no-log-init --shell /bin/bash www

