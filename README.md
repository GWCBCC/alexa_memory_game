# alexa_memory_game

Just following [@_johnwheeler's](https://twitter.com/_johnwheeler) tutorial [Flask-Ask: A New Python Framework for Rapid Alexa Skills Kit Development](https://developer.amazon.com/blogs/post/Tx14R0IYYGH3SKT/Flask-Ask-A-New-Python-Framework-for-Rapid-Alexa-Skills-Kit-Development)

I ran into three issues:

1. My old Mac had too many old versions of Python installed with old pips and virtualenv etc.  I followed these instructions https://stackoverflow.com/a/3819829.  **Just make sure not to remove anything under /System/Library...** Your Mac needs those!  I then did a fresh install of Python3.6 by installing https://www.python.org/downloads/
2. When running the app, I got some SSL cert errors which were resolved by updating Python 3.6 certs: https://stackoverflow.com/a/41692664
3. The JSON format for the skill configuration has changed a little since this tutorial was written.  Copy and paste the one here: https://developer.amazon.com/edw/home.html#/skills
