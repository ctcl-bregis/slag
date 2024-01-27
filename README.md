<div align="center">
  <img src="slag_logo.svg" style="width: 50%" alt="SLAG"/>
</div>

# SLAG: Security, Logging, Analytics and General purpose bot

SLAG is a bot for the Discord chat service. It was created for small guilds such as school clubs.

SLAG is an initialism of "Security, Logging, Analytics and General Purpose". The logo is based off from this, with the goal of the bot to be "solid as steel". 

Unlike many other bots, there are no donations, premium or voting.

## Features
Features are extended through the use of [Cogs](https://discordpy.readthedocs.io/en/v2.3.2/ext/commands/cogs.html). 


### Logs
There are three different logs that SLAG writes to

#### sys_log.log
sys_log.log contains activity about the bot itself.

#### act_log.csv
act_log.csv contains user activity such as leaves, joins

#### [guild_id]/[user_id]_msg_log.csv
There is a message log in the CSV format for each user in each guild

## Requirements
This bot is meant to be hosted in a Linux environment. Some features may not be available on other platforms.
