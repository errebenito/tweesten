### Tweesten 

Tweesten tweets what you listen to.

Tweesten is a python utility that retrieves a collage of album covers based on your last.fm scrobbles, kindly provided by [tapmusic.net](http://tapmusic.net), and tweets it with an (optional) message. 

### Quick Install

* Install Tweesten from PyPI

        # pip3 install tweesten

* Install Tweesten from sources

        # tar zxvf tweesten-0.1.tar.gz
        # cd tweesten
        # python3.4 setup.py install
        
        Or
        
        # python3.4 setup.py install --install-scripts=/usr/bin

### Use Tweesten

* As a prerequisite to use Tweesten, you need to create a Twitter app. Go to https://dev.twitter.com/apps/new (log in if you're not already logged in on Twitter), and supply the required fields. Once you've submitted the form, go to the keys and access tokens tab, and generate your consumer key and secret and your access token and token secret as needed.

* Create or modify the tweesten.ini file in order to configure Tweesten:

        [main]
        consumer_key=*Your consumer key*
        consumer_secret=*Your consumer secret*
        access_token=*Your access token*
        access_token_secret=*Your access token secret*
        size= *3x3, 4x4, or 5x5 (2x6 and 10x10 are also available if you're a premium tapmusic.net user)*
        fromlast= *One of the following: 7day, 1month, 3month, 6month, 1year, overall*
        caption= *Either true or false, controls whether artist and album names are shown*
        username= *Your last.fm username*
        message= *The text of the tweet, leave a space to post only the image*

* Launch Tweesten

        $ tweesten /path/to/tweesten.ini

### Authors

Raúl Benito <erre.benito@gmail.com>

### License

This software comes under the terms of the GPLv3+ or at your option, any later version. See the LICENSE file for the complete text of the license.
