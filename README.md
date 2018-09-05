In order to run this app:
 
- Install [node.js](https://nodejs.org/en/).
- Sign up for a free [ipstack API key](https://ipstack.com/signup/free).
- Clone the repository.
- Install dependencies using `npm install`.
- Make a new app at Heroku, and add the Heroku Redis add-on (free plan) and note the app URL.
- Add a config var APP_URL (usually {app_name}.herokuapp.com)
- Make a Slack webhook for a slack-channel and note the URL, add them as config vars named SLACK_URL & SLACK_CHANNEL.
- Deploy to Heroku.
- Have anyone who wants to contribute add the webhook on https://app.plex.tv/web/app#!/account/webhooks

You'll be asked to complete these config vars
```
SLACK_URL      # your slack webhook URL
SLACK_CHANNEL  # the slack #channel-name to post messages
APP_URL        # the App URL ({app_name}.herokuapp.com)
IPSTACK_KEY    # your ipstack API key
```
