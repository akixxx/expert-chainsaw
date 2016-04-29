chatwork-to-slack
-----------------

**EXPERIMENTAL**

## Why ???
- ChatWork is not user friendly (especially for engineers)
- I don't wish to launch many chat tools
- I want to read chat message only from Slack

## Getting started
`chatwork-to-slack` requires Node v6.0.0 or later.

```
$ node -v
6.0.0

$ npm i -g chatwork-to-slack
```

To start `chatwork-to-slack`, you need to install and launch MongoDB.

```
$ chatwork-to-slack \
   --chatwork-room-id=12345 \
   --chatwork-api-token=YOUR_CHATWORK_API_TOKEN \
   --slack-webhook-url=YOUR_SLACK_WEBHOOK_URL \
   --slack-channel=CHANNEL_NAME \
   --mongodb-url=mongodb://localhost/chatwork
```

The command is not deamonized.
You can use `chatwork-to-slack` along with Cron.

## License
MIT License