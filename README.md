# mgmt
management server

## Definitions

### Farm

group of multiple servers of each type (NIGX, NodeJS, CouchDB, Redis). Each organization will be assigned a farm.

A farm will be a minimum of 2 "physical" servers geographically close to one another. Each server will be assigned a 'zone name'. Then each app type will be able to use the zones for redundency.

### cluster
