# Scan Messages for "very"

#### What it does
This feature scans a message for the word "very" and sends a message in response to that.

#### Imlementation
```javascript
if (message.includes("very")) {
  send("_How dare you use the forbidden blasphemous word \"v\*ry\"_");
}
```
