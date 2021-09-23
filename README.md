# telegram-group-data

All message data in telegram group. Text, identity, datetime.

## What kind of data?
Column : `id,reply_to_msg_id,text,first_name,last_name,username,phone,day_utc,month_utc,year_utc,hour_utc,minute_utc,second_utc`.

## How can i got those data?
source code : [get-telegram-group-data](https://github.com/Hidayathamir/get-telegram-group-data).

## Note
1. count data : 1,865,827. In `count_data.ipynb`.
2. I use `change_file_name.ipynb` to sync first id, last id, with file name in format `group-first_id-last_id.csv`
