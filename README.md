# dominioncardstext


This is a repository of Dominion cards text scraped from http://wiki.dominionstrategy.com/index.php/List_of_cards. To be used for Twitch commands that pull Dominion card text into Twitch chat.

**Nigtbot** custom command - https://nightbot.tv/ <br>
!card : ```$(urlfetch https://raw.githubusercontent.com/azeonwy/dominioncardstext/main/$(eval var1=`$(querystring)`;var2=var1.toUpperCase().toLowerCase();var2))```

**Streamlabs Cloudbot** custom command - https://streamlabs.com/dashboard#/cloudbot/commands/custom <br>
works for lowercase only, improvement suggestions appreciated<br>
!card : ```{readapi.https://raw.githubusercontent.com/azeonwy/dominioncardstext/main/{1}}```

**StreamElements** custom command - https://streamelements.com/ <br>
works for lowercase only, improvement suggestions appreciated<br>
!card : ```$(urlfetch https://raw.githubusercontent.com/azeonwy/dominioncardstext/main/${1})```

**Usage**:
- Connect Nightbot/Streamlabs Cloudbot/StreamElements to your Twitch channel.
- Make a new custom !card command by copy pasting the code above.
- Type in Twitch chat _!card sentry_ OR _!card throne_room_ OR _!card will-o'-wisp_.
