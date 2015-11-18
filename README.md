check-mk-agent-plugins
======================

Various plugins for check-mk-agent

Current plugins are:
* swap - check if swap is enabled
* swapsize - check if swap is a percent of physical memory
* total-free-mem - check if free memory is at least x mb
* uptime - check if system has been up at least x minutes 
* no-root-owner - check if any files are owned by root under a folder
* script - run a check on any script. e.g. `curl http://localhost; ./script $?`
* redis - check that nc is able to connect to redis on localhost (ha proxy)



