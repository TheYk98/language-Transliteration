# Language Translation
Get instantaneous translation letter by letter .Every letter matters! Choose over 10+ sugesstions for each word.
# How to use?
* Select the language to which you want to convert
* Type the Word
* Select from the suggestion list and get the word replaced to translated word.
# Improvements
* One of the cases that doesn't work until now is , Adding a new word inbetween the previously typed words of a sentence.
* Another case is appending a letter in between word typed. 
``` However, You can use backspace and add back the letter.```
# How it works?
* For each letter typed, A key listner routine runs which gets the input from the user. A GET call is made with that particular letter and we get the translated word returned from the api. 
* After the api call, the typed word is replaced with the translated word

* Word is formed by appending each of the letter and that's how the suggestions are made at letter level.

# Download Route
 * You can download the word you typed with the respective transliteration now as a CSV format.
 ``` \download ``` will produce a output.csv file with all the typed inputs in the current session. Also, You can download by  cclicking on the download button.
 
 # Deployment 
 * Heroku Procfile handles the deployment in heroku. Gunicorn is a WSGI HTTP server for handling multiple requests at the same time.
