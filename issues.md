# issues

## docker
 - docker rm --stopped #15160
 - docker rmi --unused #9054
 - socket operation on non-socket ARM v1.7 #
 
 # Improvements
 - how to docker cp easily
 - optimize for building
 - DEFAULT PATH RASPBIAN: /usr/local/sbin:/usr/local/bin:/usr/sbin:/usr/bin:/sbin:/bin



 - docker aufs -> many builds -> graph=3.9G -> overlay -> graph=3.9G
 - Why does failed builds persist? Shouldn't they be removed along with their containers
 - ENV PATH $PATH:/usr/bin -> echo $PATH -> :/usr/bin == ARM issue
 - /bin/bash -c "source /version.sh; cat /version.sh; echo $GO_VERSION" fails in build
 - when the computer is asleep the clock in docker ps is paused
 - IPv4 forwarding is disabled => system-docker


## kubernetes
 - cadvisor unsupported #8424
 - socket operation on non-socket /luxas #
 - kubernetes/pause platform dependent #




## etcd
 - stop etcd service and start again => docker
 



## rancheros
 - rsync vagrant issue
 - kubectl binary depends on libc, which isn't present
 - build on own machine
 - ls dist/artifacts build error
 - Raspberry Pi support
 - 

