This is the base repository for an OpenEmbedded Raspberry Pi build that I'm using
with Jenkins.

## Setup
git submodule init

git submodule update

cd build-oe

./build-docker.sh

## Execution
./build.sh

## Notes
Permissions errors are likely due to selinux.

chcon -Rt svirt_sandbox_file_t *path*
