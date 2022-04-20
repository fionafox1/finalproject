First, YelpAPI must be installed using pip install yelpapi. 

In order to use the Yelp API you will need and API key that can be obtained here: https://www.yelp.com/developers/documentation/v3/authentication.
Use the following code to authenticate your API key:
api_key = 'MY KEY'
headers = {'Authorization': 'Bearer {}'.format(api_key)}

In order to run the program you will need to install the requests package and the flask package. If you wish to cache your results from the API you
will also need to install the requests_cache package. 

You can alter the parameters for the Yelp API in order to get any sort of results. Results will be stored in the yelp.sqlite cache. 

In order to interact with the program, simply run the code and follow the prompts. 
