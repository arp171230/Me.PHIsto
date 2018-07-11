# Me.PHIsto
CS 2336 Project 1 - Chatbot
--------------------------------------------------------------------------------------------------------------------------------
This was a project made for my CS 2336 class using the PIRCbot and GSON libraries under the Eclipse Public User License 2.0
--------------------------------------------------------------------------------------------------------------------------------

Note: Both the PIRCbot and the GSON libraries are required in the IDE in order for this to work. Developed in Eclipse Oxygen.3a

Me.PHIsto operates on the freenode Web IRC server at webchat.freenode.net, and connects to a channel that can be specified by the host. The default setting that I have used is the channel #JavaChat. The bot responds to 4 function calls; 3 APIs and 1 help function. 

--------------------------------------------------------------------------------------------------------------------------------
Weather function:

Me.PHIsto utilizes the AerisWeather API in order to get the weather at a specific location. Currently, locations are limited to the United States. Message formats to trigger the call are as follows:
    weather {location}, weather in {location}, {location} weather, weather at {location}, weather of {location}

The location formats currently accepted are either ZIP code, {city},{state}, {city}, {state}, {city}, {ST}, {city},{ST}, where {ST} is the two-letter abbreviation of the state
--------------------------------------------------------------------------------------------------------------------------------
News function:

Me.PHIsto utilizes the NewsAPI.org API to retrieve the top trending headline for a given category. Categories are currently limited to Business, Entertainment, General, Health, Science, Sports, and Technology. Message formats to trigger the call are:
    news {category}
    {category} news
    news about {category}
    news of {category}
   
--------------------------------------------------------------------------------------------------------------------------------
Translation function:

Me.PHIsto utilizes the YandexTranslate API to translate a message by a user. Languages currently are limited to major world languages (Spanish, German, Arabic, Chinese, French, Italian, Hindi, Urdu, Russian, Portuguese, Greek, and English). Message format to trigger the call is:
    translate "{text}" to {language}
    
--------------------------------------------------------------------------------------------------------------------------------
