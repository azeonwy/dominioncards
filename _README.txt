This is a repository of Dominion card text (NOT UP TO DATE info was from https://docs.google.com/spreadsheets/d/1u52jHe1-JN6rJGwHqW3xhhaQblPOtPeC0TLShrCloik/edit?usp=sharing)
To be used for Twitch command that pulls card text into chat.

Nigtbot command (https://nightbot.tv/):
!card : $(urlfetch https://raw.githubusercontent.com/azeonwy/dominioncardstext/main/$(eval var1=`$(querystring)`;var2=var1.toUpperCase().toLowerCase();var2))

Streamlabs Cloudbot similar command - lowercase only (https://streamlabs.com/dashboard#/cloudbot/commands/custom):
!card : {readapi.https://raw.githubusercontent.com/azeonwy/dominioncardstext/main/{1}}
