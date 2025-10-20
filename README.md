# Nifty PM API Reference
I'm in no away  affiliated with Nifty PM. This repo is designed to supplement the existing Nifty API documentation. Purely for educational purposes.

## Add A Comment To A Task
POST https://openapi.niftypm.com/api/v1.0/messages
```
{
  "type": "text",
  "text": "Message",
  "task_id": "Task ID"
}
```

## Add A Comment To A Project Discussion

POST https://openapi.niftypm.com/api/v1.0/messages
```
{
  "type": "text",
  "text": "Message",
  "chat_id": "Chat ID"
}
```

To get a project discussion's chat ID, get the project first, then grab the chat id value from "general_discussion".
