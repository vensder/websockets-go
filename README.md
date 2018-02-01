# websockets-go
Simple golang web socket app for testing in a docker and on AWS Elastic Beanstalk environment.

```bash
git clone https://github.com/vensder/websockets-go.git
cd websockets-go
```

## How to test ws/wss on localhost

```bash
docker-compose up -d
```

Open http://localhost and send test messages via ws.

Open https://localhost and send test messages via wss.

Original link: https://github.com/golang-samples/websocket.git

For testing ws/wss on AWS Elastic Beanstalk environment use content of [elasticbeanstalk](elasticbeanstalk) directory as template.
