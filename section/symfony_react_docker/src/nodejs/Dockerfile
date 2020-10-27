ARG NODEJS_VERSION=15.0

FROM node:${NODEJS_VERSION}-alpine

RUN yarn install

ENTRYPOINT ["/usr/local/bin/docker-entrypoint.sh"]
# Skipped as used with encore installation under SF5
# CMD ["yarn", "run", "encore", "dev", "--watch"]
CMD ["yarn"]