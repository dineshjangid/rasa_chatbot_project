## happy path 1 (C:\Users\jangi\AppData\Local\Temp\tmpni_nvxmh\97355d555e9d4430bcc5fb5492270c6f_conversation_tests.md)
* greet: hello there!
    - utter_greet
* mood_great: amazing   <!-- predicted: affirm: amazing -->
    - utter_happy   <!-- predicted: utter_ask_location -->


## happy path 2 (C:\Users\jangi\AppData\Local\Temp\tmpni_nvxmh\97355d555e9d4430bcc5fb5492270c6f_conversation_tests.md)
* greet: hello there!
    - utter_greet
* mood_great: amazing   <!-- predicted: affirm: amazing -->
    - utter_happy   <!-- predicted: utter_ask_location -->
* goodbye: bye-bye!
    - utter_goodbye   <!-- predicted: utter_ask_location -->


## sad path 1 (C:\Users\jangi\AppData\Local\Temp\tmpni_nvxmh\97355d555e9d4430bcc5fb5492270c6f_conversation_tests.md)
* greet: hello
    - utter_greet
* mood_unhappy: not good   <!-- predicted: deny: not good -->
    - utter_cheer_up   <!-- predicted: utter_ask_location -->
    - utter_did_that_help   <!-- predicted: action_listen -->
* affirm: yes
    - utter_happy   <!-- predicted: utter_ask_location -->


## sad path 2 (C:\Users\jangi\AppData\Local\Temp\tmpni_nvxmh\97355d555e9d4430bcc5fb5492270c6f_conversation_tests.md)
* greet: hello
    - utter_greet
* mood_unhappy: not good   <!-- predicted: deny: not good -->
    - utter_cheer_up   <!-- predicted: utter_ask_location -->
    - utter_did_that_help   <!-- predicted: action_listen -->
* deny: not really
    - utter_goodbye   <!-- predicted: utter_ask_location -->


## sad path 3 (C:\Users\jangi\AppData\Local\Temp\tmpni_nvxmh\97355d555e9d4430bcc5fb5492270c6f_conversation_tests.md)
* greet: hi
    - utter_greet
* mood_unhappy: very terrible   <!-- predicted: affirm: very terrible -->
    - utter_cheer_up   <!-- predicted: utter_ask_location -->
    - utter_did_that_help   <!-- predicted: action_listen -->
* deny: no
    - utter_goodbye   <!-- predicted: utter_ask_location -->


## say goodbye (C:\Users\jangi\AppData\Local\Temp\tmpni_nvxmh\97355d555e9d4430bcc5fb5492270c6f_conversation_tests.md)
* goodbye: bye-bye!
    - utter_goodbye   <!-- predicted: utter_ask_location -->


## bot challenge (C:\Users\jangi\AppData\Local\Temp\tmpni_nvxmh\97355d555e9d4430bcc5fb5492270c6f_conversation_tests.md)
* bot_challenge: are you a bot?   <!-- predicted: restaurant_search: are you a bot? -->
    - utter_iamabot   <!-- predicted: utter_ask_location -->


