GStreamer Tutorial2 recreated using instructions posted on Stack Overflow by Eduardo Fernando.
Variable GSTREAMER_ROOT_ANDROID must be defined in /etc/profile or /home/USERNAME/.profile and show to a path where you have extracted GStreamer Android binaries, for example:
export GSTREAMER_ROOT_ANDROID=/home/USERNAME/gstreamer-1.0-android-universal-1.14.2<br/>
If you're having trouble building the project, download and unzip revision 10e of the NDK, set path pointing to it in your project's settings and copy file "source.properties" from the up-to-date NDK folder to folder containing the 10e version.
