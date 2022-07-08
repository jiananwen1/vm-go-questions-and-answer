# Deployment frequent questions and answers

## cgroup related

1. fail to setCGroup, err: [mkdir /sys/fs/cgroup/memory/chainmaker: read-only file system]

missing --privileged when running the vm-docker-go.

