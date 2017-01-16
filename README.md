# stellar_asset_history
A simple web app that displays tables and charts of stellar.org asset history prices

This web app pulls data from the funtracker.site API that provides stellar.org asset historys.
from the API data we create a table of avalible asset pairs and setup links to view charts on 
each one and a link to setup buy trade on any asset combo that uses the funtracker.site wallet
to trade.

The API server that is used here has been provided by funtracker.site. The API server is also available in public domain 
that can be found at:  https://github.com/sacarlson/stellar_utility/tree/master/multi-sign-server.
It can be setup on your own server were it will record history and provide the API for this web app if desired.
