# simple_gRPC
This repo contains the Proto file that has 

- 2 Message types 

- 1 Service

- 4 RPCs for that Service

And the Go files generated by compiling the proto file.

- simple.pb.go \- contains the pb messages

- simple_grpc.pb.go \- contains the gRPC Service and methods

To use this package

    go get -u github.com/LogeshVel/simple_gRPC/simple/testgrpc

and import the package

    import "github.com/LogeshVel/simple_gRPC/simple/testgrpc"


The packages in this repo is used by the [Four gRPC modes](https://github.com/LogeshVel/four_gRPC_modes) repo
