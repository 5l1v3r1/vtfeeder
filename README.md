# vtfeeder

Telegram Bot to download virustotal feed files each hour.
Gets feed from (https://www.virustotal.com/vtapi/v2/file/feed) and downloads all files included in feed file. 

## Setup

- Add your VT Private API key and Telegram Bot Key to config.py
- Run bot. type /chat_id . Put chat_id to config.py (for authentication)
- Uncomment line 165 in vt_feeder.py
- Change directory in config.py if you want

## Commands 

/start_d : Starts looping sequence.

/stop_d : Stops loop

/is_running : Check if loop is on

/list_packages : List downloaded package files
