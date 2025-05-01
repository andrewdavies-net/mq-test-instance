This application set should load everything in the development environment under the "app" app type
If app had 2 QM & 4 ace apps then it would load everything for development (this approach might need to change)
It also works on active/failover and therefore it can groups the entire application stack
However if a second queue manager wanted to be run on a seperate cluster then applicationset defines placement and it would need to move down a level. this is likely 