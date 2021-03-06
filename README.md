# go-test-multi-stage-build
Go multi stage build practice 

# Objective
Practice how to enable multi stage build in golang.

# Run
1. `go get -u github.com/golang/dep/cmd/dep`
1. `dep ensure`
1. `docker build . -t go2docker`
1. `docker run --name demo go2docker`

# Expected result
![result](https://i.imgur.com/VURu2Zs.png)

# Vendor file handle
https://ops.tips/blog/dockerfile-golang/

# Google image reference
https://github.com/GoogleCloudPlatform/distroless

# About go dep
https://github.com/golang/dep

# Images compare ( size )
![docker images size](https://i.imgur.com/Ohr7kmJ.png)
