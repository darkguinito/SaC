# SaC

**S**oftware **a**s **C**ode


# Docker-compose 

## Services 

### deploy-mopidy

Deploy mopidy to k3s cluster 

### undeploy-mopidy

Remove mopidy to k3s cluster 

### deploy-snap

Deploy snapserver to k3s cluster 

### undeploy-snap

Remove snapserver to k3s cluster 

## Apps

Name    | Path        | Description
:---:   |:---:        |:---
mopidy  | mopidy      | Mopidy application with Muse add on
snap    | snapserver  | Snapserver application
fast    | fast        | Fast app, Youtubedl front & backend with celery worker
browser | fileBrowser | Share nfs folder

