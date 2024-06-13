# if your new to alexa skills start here:
- https://developer.amazon.com/en-US/alexa/trainings_and_workshops

# info
- the skill's invocation name is: "friedhof fahrplan"
- the only intent so far is: "planintent"

# steps to adjust
This is a alexa skill i coded to ask alexa when my next bus will arrive. You need to take a few steps to make it work for you.

1. Go into the lamda > class planintentHandler and add your bus times to the bus_times list.
2. adjust the timezone by changeing the timedelta (timedelta is just a workaround lol). currently its the UTC + 2 Hours = German Timezone
3. Add your own uri in skill.json

