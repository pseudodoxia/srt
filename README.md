Linux bash script srt_convert.sh uses C-compiled program srt to convert file_name.txt from Youtube transcription box to file_name.srt which contains subtitles in srt format.

Instruction:

1. create file_name.txt and copy the content of Youtube transcription box to this file
    
2. sudo gcc -o srt srt.c
   
3. files:
   
      srt_convert.sh
   
      file_name.txt
   
      srt
   
         should be in the same directory.
   
4. run the script typing ./srt_convert.sh
5. Script srt_convert.sh is a modification of the script prepare_mp4.sh from https://bitbucket.org/MattHawkinsUK/rpispy-video-capture-unit/src/master/
6. codes srt_convert.sh and srt.c were written nad compiled on Rapspberry Pi Zero WH 512MB RAM - WiFi + BT 4.1
   
   under 2019-04-08-raspbian-stretch-lite http://downloads.raspberrypi.org/raspbian_lite/images/raspbian_lite-2019-04-09/

7. literature:  The ANSI C Programming Language by Brian W. Kernighan, Dennis M. Ritchie;  chapters 1.5.1-4; pages 18-22
   
   https://archive.org/details/the-ansi-c-programming-language-by-brian-w.-kernighan-dennis-m.-ritchie.org/page/18/mode/2up




################

 
Example - input .txt format from Youtube transcription box:

0:00

sudo gcc -o srt srt.c

0:04

Linux bash script srt_convert.sh uses C-compiled program srt

0:07

to convert file_name.txt from Youtube transcription box

0:14

to file_name.srt which contains subtitles in srt format.

0:17



#################

Output .srt format:

1

00:00:00,000 --> 00:00:04,000 

sudo gcc -o srt srt.c

2

00:00:04,000 --> 00:00:07,000 

Linux bash script srt_convert.sh uses C-compiled program srt


3

00:00:07,000 --> 00:00:14,000 

to convert file_name.txt from Youtube transcription box


4

00:00:14,000 --> 00:00:17,000 

to file_name.srt which contains subtitles in srt format. 

