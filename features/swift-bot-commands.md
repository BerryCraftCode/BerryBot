# Swift Bot Commands

#### What It Does
This brings some commands from SwiftBot over to BerryBot

#### Implementation
```js
case 'echo':
  send(message);
  break;
case 'mirror':
  send(reverseString(args.join(" ")));
  break;
case 'hex':
  send(encode(args.join(" ")));
  break;
```
