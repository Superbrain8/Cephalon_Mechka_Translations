# Cephalon_Mechka_Translations
Translations for the Discord Bot Cephalon Mechka

How to add a Translation:
edit the lang.json to meet following requirements
```json
{
    "languages": ["english","Your Language"],
    "translations": {
      "ERROR": {
        "english": "an Error occured please try again.",
        "Your Language": "an Error occured please try again.(in your language)"
      },
      "ARBI_START": {
        "english": "Arbitrations Starts:",
        "Your Language": "Arbitrations Starts:(in your language)"
      },
      "ARBI_ENDS": {
        "english": "Arbitrations Ends:",
        "Your Language": "Arbitrations Ends:(in your language)"
      },
      "ARBI_MODE": {
        "english": "Mode:",
        "Your Language": "Mode:(in your language)"
      },
      "ARBI_CHECK": {
        "english": "Last time checked:",
        "Your Language": "Last time checked:(in your language)"
      }
    }
}
```
if done open a Pull request. if merged to the Repo the bot will load the new language after the next Restart. (will be done by me manually)
  
