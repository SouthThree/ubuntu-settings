# ubuntu-settings
时间设置：
sudo timedatectl set-local-rtc 1
sudo apt-get install ntpdate
sudo ntpdate time.windows.com
sudo hwclock --localtime --systohc

jdk设置：
#set oracle jdk environment
export JAVA_HOME=/opt/jdk1.8.0_261 
export JRE_HOME=${JAVA_HOME}/jre  
export CLASSPATH=.:${JAVA_HOME}/lib:${JRE_HOME}/lib  
export PATH=${JAVA_HOME}/bin:$PATH  
