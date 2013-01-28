Alexa-Ranking
=============

Python library to get the Alexa rank of the domain of any URL
Not installer yet, so in order to use it, you'll have to copy the alexa.py file to your Python lib search path.

Usage:
    from alexa import Alexa
    ranker = Alexa() # this might take a while as the rankings are downloaded
    google_rank = ranker.getrank('www.google.com')
    some_rank = ranker.getrank('www.somestupiddomain.com') # should return -1