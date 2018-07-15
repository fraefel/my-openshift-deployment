# My OpenShift deployment helper

## Easy deployment of OpenShift on Hetzer Cloud

```
# Build ansible docker container

docker build -t a -f Dockfile.ansible .

docker run -ti -v $(pwd):/a a 

export export HCLOUD_TOKEN=79yLNrFjq0lMHScZm....

```

