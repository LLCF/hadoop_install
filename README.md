# hadoop_install

##install 

jdk
maven
g++ 
autoconf 
automake 
libtool 
cmake 
zlib1g-dev 
pkg-config 
libssl-dev
protobuf-compiler

download Hadoop

mvn clean package -Pdist,native -DskipTests -Dtar
