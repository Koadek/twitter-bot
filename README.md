# twitter-bot
Simple Twitter Bot that favorite a given number of tweets that includes our query.  

in config.js :

module.exports = {
  consumer_key: '',
  consumer_secret: '',
  access_token_key: '',
  access_token_secret: '',
};

Visit the Twitter API and fill out the form. When done, click on the Keys and Access Tokens tab to view your consumer key/secret and access token key/secret.

in app.js :  

var params = {
  q: '#github',
  count: 10,
  result_type: 'recent',
  lang: 'en',
};

you can change the params to make the bot favorite a different number of tweets that includes a different query.  

The bot could also be modify in order to do a different action.
