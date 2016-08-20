Configure Tweesten
==================

As a prerequisite to use Tweesten, you need to create a Twitter app. Go to https://dev.twitter.com/apps/new (log in if you're not already logged in on Twitter), and supply the 
required fields. Once you've submitted the form, go to the keys and access tokens tab, and generate your consumer key and secret and your access token and token secret as needed.

Tweesten uses an ini file with the following sections and fields::

    [main]
    consumer_key=*Your consumer key*
    consumer_secret=*Your consumer secret*
    access_token=*Your access token*
    access_token_secret=*Your access token secret*
    size= *3x3, 4x4, 5x5 or 2x6 (10x10 is also available if you're a premium tapmusic.net user)*
    fromlast= *One of the following: 7day, 1month, 3month, 6month, 1year, overall*
    caption= *Either true or false, controls whether artist and album names are shown*
    username= *Your last.fm username*
    message= *The text of the tweet, leave a space to post only the image*
