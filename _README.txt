This is a repository of Dominion card text (NOT UP TO DATE info was from https://docs.google.com/spreadsheets/d/1u52jHe1-JN6rJGwHqW3xhhaQblPOtPeC0TLShrCloik/edit?usp=sharing)
To be used for a !card Twitch Nigtbot command (https://nightbot.tv/) that pulls card text into chat.
!card : $(urlfetch https://raw.githubusercontent.com/azeonwy/dominioncardstext/main/$(eval var1=`$(querystring)`;var2=var1.toUpperCase().toLowerCase();var2))

A similar Streamlabs command should be possible.
