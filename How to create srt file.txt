So srt file is, you want to add some subtitles to your video, then how do you create subtitles and add them to the video, srt is a collection file of all the subtitles.

Here's how you can create an SRT file:

component of srt:
1. Sequence number (e.g., 1, 2, 3 indicating the sequence of the subtitles)

2. Timecode (Hours, Minutes, Seconds, Milliseconds, The timestamp represents the start and end time of each subtitle. The first set of zeros (00) represents the hours, the second set represents the minutes, and so on for seconds and milliseconds.)

3. Text (This is the sentence or dialogue that you want to display as a subtitle between the specified time stamps.) 

example: (Note: Leave one empty line space between each timestamp)
```
1
00:00:01,00 --> 00:00:03,032
hi this is my family video

2
00:00:03,032 --> 00:00:05,156
Welcome to this amazing event record

3
00:00:05,156 --> 00:00:07,00
and this is another amazing moment
```

Save the file with a .srt extension, and your SRT file is ready to use.