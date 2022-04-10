# greedy-yotube-downloader
Massive instal YouTube channals, and YouTube Lists with preview images, titles, descriptions, subs etc.

##Install
Run command in console
`pip install git+https://github.com/pytube/pytube`
or
`pip install pytube`

##Usage 

Open `dl_list.py` file, scroll to bottom file.

If you need downlad channals, uncomment (delete '#' at start string if it has it) this line, and enter url to channals
`#youtube_downloader.download_from_channal_url('https://www.youtube.com/c/SUREN_VIDEO') # <----- ENTER CHANNAL URL HERE`

If you need download youtube list. Uncomment (delete '#' at start string if it has it) this line, and enter url to list
`#youtube_downloader.download_from_play_list('https://www.youtube.com/watch?v=KzH1ovd4Ots&list=PLoROMvodv4rNH7qL6-efu_q2_bPuy0adh') # <------- ENTER PLAYLIST URL HERE`

Run dl_script.py in terminal
`/usr/bin/nohup python dl_list.py > _log1 2>_log2 & echo $!`

After downloading you see sets of files, with naming == youtube video ID for examle 

```
52702 -rwxrwxrwx 1 user_name user_name      35235 апр  9 19:43  0nFfurVRqnE.jpg
52701 -rwxrwxrwx 1 user_name user_name     80701 апр  9 19:43  0nFfurVRqnE.json
52698 -rwxrwxrwx 1 user_name user_name  128595795 апр  9 19:43  0nFfurVRqnE.mp4
52652 -rwxrwxrwx 1 user_name user_name      37374 апр  9 19:27  3SsaabdqPNU.jpg
52651 -rwxrwxrwx 1 user_name user_name     125577 апр  9 19:27  3SsaabdqPNU.json
52650 -rwxrwxrwx 1 user_name user_name  118727367 апр  9 19:27  3SsaabdqPNU.mp4
```

0nFfurVRqnE.jpg - Preview image file
0nFfurVRqnE.json - Titles, descriptions, etc
0nFfurVRqnE.mp4 - YouTube video
