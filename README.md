# weather-widget
Simple webpage that displays the weather forecast using AJAX request to a weather server.
Server outputs weather information in JSON format:

{
   "updated": "Thu, 11 Oct 2012 5:54 pm CDT",
   "location": {
      "city": "St. Louis",
      "state": "MO"
   },
   "wind": {
      "chill": "62",
      "direction": "150",
      "speed": "3 mph"
   },
   "atmosphere": {
      "humidity": "50",
      "visibility": "10",
      "pressure": "30.12 in"
   },
   "current": {
      "code": "28",
      "text": "Mostly Cloudy",
      "temp": "62°F",
      "date": "Thu, 11 Oct 2012 5:54 pm CDT"
   },
   "tomorrow": {
      "code": "29",
      "text": "Clouds Early/Clearing Late",
      "low": "45°F",
      "high": "61°F"
   },
   "dayafter": {
      "code": "30",
      "text": "Partly Cloudy",
      "low": "53°F",
      "high": "65°F"
   },
   "credit": "http://us.rd.yahoo.com/dailynews/rss/weather/St._Louis__MO/*http://weather.yahoo.com/forecast/USMO0170_f.html"
}
