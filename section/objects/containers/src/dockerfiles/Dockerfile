FROM nginx
ARG ENVIRONMENT=index_dev.html
ENV ENVIRONMENT_INDEX=$ENVIRONMENT
COPY ./${ENVIRONMENT_INDEX} /usr/share/nginx/html/index.html