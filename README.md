# build-maven-center
this is a simple project to teach you how to build a maven center in your server

#### step one 

down load sonatype nexus oss:[sonatype nexus](http://www.sonatype.org/nexus/go/) 

#### step two

move it to /user/local

$ sudo cp nexus-x.xx.x-xx-bundle.tar.gz /usr/local

$ cd /usr/local

$ sudo tar xvzf nexus-x.xx.x-xx-bundle.tar.gz

$ sudo ln -s nexus-x.xx.x-xx nexus

#### step three

add to path:  $NEXUS_HOME   /usr/local/nexus

#### step four

sudo $NEXUS_HOME/bin/nexus start

attention: you must be root user

#### the last(update your studio library to maven center)

watch here:[gradle-mvn-push](https://github.com/chrisbanes/gradle-mvn-push)


