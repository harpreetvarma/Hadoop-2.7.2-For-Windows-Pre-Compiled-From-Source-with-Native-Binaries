Hadoop-2.7.2-on-Windows-with-Native-Binaries


As of now, Apache Hadoop didn't provide official Release / Support for Windows Users.

So I have Downloaded the official source package from here:
http://www.apache.org/dyn/closer.cgi/hadoop/common/hadoop-2.7.2/hadoop-2.7.2-src.tar.gz

and build a Pre-Compiled Package For Windows Users for Directly Downloading From here & Working On this Package.

The Path to Building on Windows:

Requirements:

* Windows System
* JDK 1.7+
* Maven 3.0 or later
* ProtocolBuffer 2.5.0
* CMake 2.6 or newer
* .NET Framework 4.0 (ONLY)
* Windows SDK 7.1 
* Visual Studio 2010 
* Cygwin
* Internet connection for building (to fetch all Maven and Hadoop dependencies)


All the Above Softwares Needs To Be Installed and " ENVIRONMENT VARIABLES " Must be set "Perfectly".

Also set, 

Platform=x64 in ENVIRONMENT VARIABLES under System Variables.

From The Root Directory from Source Package Run:

mvn package -Pdist,native-win -DskipTests -Dtar



I have even Posted Some Images of this Hadoop Distribution working Perfectly at my blog.

http://www.apirobuzz.com/2017/01/hadoop-272-pre-compiled-for-windows-x64.html


Windows 64 bit Users Can Download it from this https://drive.google.com/file/d/0BxI56NUuiAg3ZTFBTUdvNFZneVE/view?usp=sharing

After You download Follow the Instructions from here:

https://wiki.apache.org/hadoop/Hadoop2OnWindows

Jump to this Section & Follow instructions from There-On:
3. Starting a Single Node (pseudo-distributed) Cluster


Please Comment Back Here if You Face Any Issues.
