# weather_dashboard

For this project we were supposed to create an app that :

    1. Allows users to search for current weather using the provided API
    2. Displays current temperature, wind, humidity, and uv index
    3. The uv index displays a color code
    4. The next few days of temp and humidity are displayed
    5. A history list is populated


API STUFF
This was great practice with API calls.  I feel comfortable making API calls, I do feel my code gets pretty messy when I have multiple calls within the same event listener.

BULMA

    I tried BULMA out.  I like it! Need to learn a lot more though.

ISSUES
    The future forecast would have been better if I could have accessed the other APIs on the openweather site, for example 30 day and 16 would give me access errors but the 5 day with a forecast for ever three hours worked.

    UV-index was interesting because I couldnt find the UV in the first API call and had to make a differnt call for it.  My code calls 3 different open weather APIS-- is there a more efficient way? Would this cost 3x as much if I were paying per call?

    Localstorage... I think if I had more time I could have gotten the search history to stay but  wrestling with scope and unwritten storage was making my head spin