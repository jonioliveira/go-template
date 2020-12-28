FROM node:15-alpine3.10

RUN npm install -g @commitlint/cli @commitlint/config-conventional

WORKDIR /commit-msg

ENTRYPOINT ["commitlint"]
