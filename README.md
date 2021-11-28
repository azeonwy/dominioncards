# dominioncardstext


This is a repository of Dominion cards text scraped from http://wiki.dominionstrategy.com/index.php/List_of_cards. To be used for Twitch command that pulls card text into chat.

**Nigtbot** custom command - https://nightbot.tv/ <br>
!card : ```$(urlfetch https://raw.githubusercontent.com/azeonwy/dominioncardstext/main/$(eval var1=`$(querystring)`;var2=var1.toUpperCase().toLowerCase();var2))```

**Streamlabs Cloudbot** custom command - https://streamlabs.com/dashboard#/cloudbot/commands/custom <br>
works for lowercase only, suggestions appreciated<br>
!card : ```{readapi.https://raw.githubusercontent.com/azeonwy/dominioncardstext/main/{1}}```

**Usage**:
- Connect Nightbot or Streamlabs Cloudbot to your Twitch channel.
- Nightbot or Streamlabs Cloudbot might need to be modded.
- Make a new custom !card command as per above.
- Type in chat
!card sentry
!card throne_room
!card will-o'-wisp
