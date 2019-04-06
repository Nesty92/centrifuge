Example demonstrates oversimplified digest auth workflow.

Server sends random string in first message and expects it to be transformed to upper case by client. If condition is valid client connection is accepted, otherwise disconnected.

To start example locally install dependencies first:

```
dep init
dep ensure
```

Then go to http://localhost:8000 to see it in action.