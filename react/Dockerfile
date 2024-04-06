FROM node:lts-alpine

ENV TZ Asia/Tokyo

WORKDIR /app

RUN apk update && \
  apk add bash && \
  apk add --no-cache --update git vim

COPY /app .

CMD ["npm", "start"]