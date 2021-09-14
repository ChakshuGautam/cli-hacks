# Fix Entropy issues
```sh
docker pull harbur/haveged
docker run --privileged -d harbur/haveged
cat /proc/sys/kernel/random/entropy_avail
```
