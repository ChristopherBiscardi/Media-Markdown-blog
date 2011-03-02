Icecast with node
=======================
Deps:

ffmpeg

NPM:  
stream-stack  
icecast-stack  


Step 1
==============
Create flac files  
Audacity is nice for this  
http://audacity.sourceforge.net/  
import file  
export flac  

Step 2
==============
in icecast-stack/examples/server  
copy decodeCwdFlacToStream.sh and place it in a folder with your flac files  

Step 3
==============
./decodeCwdFlacToStream.sh | node /path/to/icecast/example/server/server.js



Step 4
============
Listen to the .ogg stream
Works in Safari
