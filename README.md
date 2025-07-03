In this RPA project, the user inputs a city name and their email address.

The bot retrieves the current weather for the specified city by opening a browser and performing a Google search. Based on the weather conditions, it suggests an activity:
- If it’s raining, the bot recommends staying at home.
- If the weather is clear, the bot checks the temperature:
  - For very hot or very cold temperatures, it suggests visiting a museum.
  - For moderate or pleasant temperatures, it suggests visiting a park.
- The bot performs another Google search to find a museum or park in the given city.

Finally, the bot sends an email containing a short weather report along with its recommendation to either visit a place or stay at home.
