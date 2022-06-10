# Discord notifications for SSH connections
In this repo you will find one single bash script. This bash script is designed to send a HTTP POST using cURL to a Discord Webhook.
<br/></br>

----

## Required Configurations
| Variables | Description | Example |
|---|---|---|
| DISCORD_WEBHOOK_URL | This URL can be acquired by using ⚙️ `Edit Channel`, navigate to the `Integrations` tab then `Webhooks` | https://discord.com/api/webhooks/985713672184625953/MX1IqBDA6qdCa5qmYAW4-9CqwQdPpfSF3yTdQandkJNyyvehsDZupgtZy9RcZHUq9Fv |
| ADMIN_CONTACT | This is the raw value of a Discord user for pings, you can append a `\` preceding a @ to see this. | <@176355202687959051> |
<br/></br>

----
## How-To Install
Installation is ez, simply place the discord-webhook.sh file into `/etc/profile.d` for this notification to occur for logins