FROM nginx:alpine

ENV APP_VERSION=1.0.0

WORKDIR /app

COPY index.html /app

RUN apk update && apk add --no-cache curl htop wget

CMD ["nginx", "-g", "daemon off;"]
