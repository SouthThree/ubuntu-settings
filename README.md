# ubuntu-settings
##时间设置：
+sudo timedatectl set-local-rtc 1

+sudo apt-get install ntpdate

+sudo ntpdate time.windows.com

+sudo hwclock --localtime --systohc

##jdk设置：

export JAVA_HOME=/opt/jdk1.8.0_261 

export JRE_HOME=${JAVA_HOME}/jre  

export CLASSPATH=.:${JAVA_HOME}/lib:${JRE_HOME}/lib  

export PATH=${JAVA_HOME}/bin:$PATH  

# update-alternatives --list python
update-alternatives: error: no alternatives for python

# update-alternatives --install /usr/bin/python python /usr/bin/python2.7 1
update-alternatives: using /usr/bin/python2.7 to provide /usr/bin/python (python) in auto mode
# update-alternatives --install /usr/bin/python python /usr/bin/python3.5 2
update-alternatives: using /usr/bin/python3.5 to provide /usr/bin/python (python) in auto mode

# update-alternatives --config python

