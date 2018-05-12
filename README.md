# Inomniac Studios

All purpose bot for Insomniac Studios company.

## Getting Started

This section will tell you how to install the bot configuration and variables to run the program.

### Prerequisites

Java 1.8
Bot Server on Discord
Administrative permissions for Bot

### Installing

Compile the SRC into a Jar file, and make sure you have an environment variable named `BOT_CONFIG` leading to the directory path for the bot information.

```bash
#Bot Configuration
Export BOT_CONFIG=/InsomniacBot/configurations/
```

Now you should run the program once, and a config.json file should appear, looking something like this:


```json
{
  "serverInformation": {
    "token": "enter-tokenID",
    "ownerID": "enter-memberID",
    "prefix": "enter-prefix",
    "embedColor": "6814bc",
    "botCommanderRole": "BotCommander"
  },
  "ticketInformation": {
    "idNumber": 0,
    "tickets": {},
    "pendingTicketCategory": "enterCategoryID",
    "paidTicketCategory": "enterCategoryID",
    "completedTicketCategory": "enterCategoryID",
    "salesCommissionChannel": "enterChannelID",
    "commissionChannel": "enterChannelID"
  }
}
```

Fill out the information, and you're good to go. Make sure you have permissions setup properly, and specfic people can see specific channels only.

##### Note
To add specific roles using the command `!ticket add [roleName]`, don't ping the role! Just add the name of the role.

## Built With

* [Kotlin](https://kotlinlang.org) - Language
* [KUtils](https://github.com/AberrantFox/KUtils) - Discord API Wrapper for Kotlin
* [JDA](https://github.com/DV8FromTheWorld/JDA) - Discord API Core
* [Gradle](https://gradle.org/) - Dependency Management

## Contributing

Please contact hapz#8318 for more information regarding contributing to this repo.

## Authors

* **Hamza ALI** - *Initial work* - [Hamzantal](https://github.com/Hamzantal)
