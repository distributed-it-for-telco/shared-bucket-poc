# Live session 2022.05.31

## Q/A

- local NATS server is preferred over docker for live sessions
- is using wasmCloud in docker and want to use hot-reload, then map a host volume
- versioning
  - no dependencies to the tool-belt once the actors/cp is built
  - runtime dependencies are managed though interfaces name versioning (eg: wasmcloud:keyvalue:v2)
- managing developer keys
  - use the toolset of NATS (organization...)


## hands on

- scaffold `wash new actor shared-bucket-poc`
- add the actor via the GUI (or via a command if using the repository)
- 

## commands

`wash claims inspect $(make target-path-abs)`





