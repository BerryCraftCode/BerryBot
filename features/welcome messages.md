# Welcome Messages

#### What it does
This feature looks at the name of the eprson joining and provides a custom message based on it.

```javascript
bot.on('guildMemberAdd', member => {
    const username = member.user.username;
    var channel = member.guild.channels.get('channelID')
    if (username.toLowerCase().includes("potato")) {
      channel.send("The evil spuds have sent " + username + " to continue the Potato Invasion!");
    } else if (username.toLowerCase().includes("berry")) {
      channel.send(username + " is a berry good fellow");
    } else {
      // idk some random stuff
    }
});
```
