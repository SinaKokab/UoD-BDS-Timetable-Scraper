# UoDTimeTableBot

(Still in progress)

Pulls data from UoD timetable, parses it, and serves it using FB messenger.

How:
  * Uses headless chrome and selenium to navigate the timetable
  * Uses BS4 to browse the data and organise it
  * Uses Pymessenger to recieve and serve messages across FB Messenger
    * Uses Flask to provide pathways for GET and POST requests
    * Uses Wit.ai for NLP to decipher the intent of the message and get corresponding data, i.e. date, to respond.

TODO:
  * Add user customisation properties, i.e. only show labs for group A.
  * Add ability for user to select what school and modules to scrape.
  * Move host from Heroku to VPS.
  * Host flask backend in Docker VM.
  * Add ability to check next weeks lectures.
  * Generally clean code and fix issue with threading.

