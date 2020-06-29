## happy path
* greet
  - utter_greet
* mood_great
  - utter_happy
* mood_happy
  - utter_happy
## sad path 1
* greet
  - utter_greet
* mood_unhappy
  - utter_cheer_up
  - utter_did_that_help
* affirm
  - utter_happy

## sad path 2
* greet
  - utter_greet
* mood_unhappy
  - utter_cheer_up
  - utter_did_that_help
* deny
  - utter_goodbye

## say goodbye
* goodbye
  - utter_goodbye

## bot challenge
* bot_challenge
  - utter_iamabot

## story_ask_weather
* ask_weather
  - action_ask_weather
* weather_city
  - utter_weather_good
