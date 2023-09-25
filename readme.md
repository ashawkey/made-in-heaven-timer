# Made In Heaven Timer

A simple script to create a timer video at any acceleration speed:

https://github.com/ashawkey/made-in-heaven-timer/assets/25863658/1477eb63-c639-42ed-a330-87ba7434481c

https://github.com/ashawkey/made-in-heaven-timer/assets/25863658/4e45aae3-d344-432a-9246-d7e7cd594670


### Usage
```bash

# create a timer from 00:10 to 00:00 (count down), with red text and grey background, save to default timer.mp4
python mih_timer.py --start 00:10 --end 00:00 --fg_color red --bg_color grey

# create a timer from 00:00 to 01:00 (count up), with 10x acceleration, save to timer1.mp4
python mih_timer.py --start 00:00 --end 01:00 --speedup 10 --out timer1.mp4

# find out more options by:
python mih_timer.py --help
```
