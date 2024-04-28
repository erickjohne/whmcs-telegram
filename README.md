# whmcs-telegram
telegram notification for whmcs


Send WHMCS notifications to telegram

Installation
Place the Telegram folder in your WHMCS installation (modules/notification/Telegram)
Create a bot with BotFather, and get the token.
Send a message to your new bot from the user/channel on which you want to receive notifications.
Go to this URL: https://api.telegram.org/bot[TOKEN]/getUpdates (Replace[TOKEN] with your bot token)
Get your chat ID
Go to your WHMCS administration panel, Setup > Notifications, click on the Configure button under Telegram, and put your bot token and chat ID, you should receive a message "Connected with WHMCS", otherwise, check your chat ID and token.
