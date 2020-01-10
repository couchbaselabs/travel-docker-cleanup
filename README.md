# travel-docker-cleanup
Mobile Travel-Sample demo cleanup scripts.

When creating VMs or containers there may be a need to clean things up between runs to keep the environment ready.
 
The flow is as shown below (can use the stop-sg script instead of kill %2).
~~~~
# ./reset
# ./start-sg &
# ./start-webapp &
 
*** do demo
 
# kill %1
# kill %2
~~~~

## ToDo
1. provide additional commands for the use within the container
2. link to the demo contents
3. add additional user scripts for sync-gateway users
