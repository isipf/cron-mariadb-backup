FROM alpine:3.18

RUN apk update &&  apk upgrade &&  apk add --no-cache mariadb-client=10.11.4-r0

RUN addgroup -g 1000 user1 &&  adduser -G user1 -u 1000 user1 -D
# Démarrer le démon Cron
CMD ["crond", "-f", "-l", "8"]