# The Giphy Slack Command for Groupme

This is a bot that adds the functionality of the `/giphy` command from Slack to Groupme.

After deployment, users can just message a group on Groupme a text saying `/giphy [something]` and the bot will respond with the first gif it finds on Giphy by searching the query `something`.

To deploy your own, you will need a bot ID from Groupme and possibly an API key from giphy. When you have those, make sure you `export BOT_ID="yourBotId"` and `export API_KEY="YourAPIKey"`. I have also included a Procfile, in case you choose to deploy this bot with Heroku, as I did.
