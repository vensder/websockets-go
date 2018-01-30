# websockets-go
Simple golang web socket app for testing in a docker

```bash
git clone https://github.com/vensder/websockets-go.git
cd websockets-go
```

## How to test ws

```bash
docker run -d -p 8080:8080 vensder/websockets-go
```

Open http://localhost:8080 and send test messages.

## How to test wss

```bash
docker-compose up -d
```

Open https://localhost and send test messages.

Original link: https://github.com/golang-samples/websocket.git
