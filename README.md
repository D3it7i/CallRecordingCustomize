# CallReRecord - Google dialer CallRecording announcement customize
**Thanks to the [original project](https://github.com/vvb2060/CallRecording) for giving me the opportunity to revise**

[GAppsMod ISSUSE#50](https://github.com/jacopotediosi/GAppsMod/issues/50) solution,
This is the xposed module, you need to enable it using lsposed etc.  
Then you need to place your custom start and end announcements respectively, and the wav files are in the following paths:
* /data/data/com.google.android.dialer/files/callrecordingprompt/starting_custom.wav
* /data/data/com.google.android.dialer/files/callrecordingprompt/ending_custom.wav  
  Grant permissions to ensure that the file can be read by everyone, This is done and he will work。  
  **If the file is unreadable or does not exist, the recording prompt will be slient**
# known issues
* none