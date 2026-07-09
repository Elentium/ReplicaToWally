# ReplicaToWally

## The repo contains source code of slightly modified ReplicaServer and ReplicaClient (by loleris) in order to properly work separately in wally package system

## In order to add Replica to your project, insert the following to wally.toml:
```toml
[dependencies]
ReplicaShared = "elentium/replicashared@1.0.2"
ReplicaClient = "elentium/replicaclient@1.0.0"

[server-dependencies]
ReplicaServer = "elentium/replicaserver@1.0.1"
```