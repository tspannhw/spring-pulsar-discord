## spring-pulsar-discord

Spring - Pulsar Application to send messages to Discord


![diagram](https://raw.githubusercontent.com/tspannhw/spring-pulsar-discord/main/images/springpulsardiscord2.png)

### Send Message

````
client.getChannelById(channelIdHere)
    .ofType(MessageChannel.class)
    .flatMap(channel -> channel.createMessage("Your content here"))
    .subscribe();

````

### Library Options

* https://github.com/DV8FromTheWorld/JDA
* https://github.com/Discord4J/Discord4J

### Setup Discord for App Use

https://docs.discord4j.com/discord-application-tutorial

### Apache Pulsar Discord Example

https://discord.com/channels/1039648903483621466/1054515395442249868

### Resources

* https://discord4j.com/


