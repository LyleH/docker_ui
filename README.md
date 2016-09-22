## Takealot Docker UI


UI For Docker is a web interface for the Docker Remote API.  The goal is to provide a pure client side implementation so it is effortless to connect and manage docker.

![screen shot 2016-09-22 at 10 07 05](https://cloud.githubusercontent.com/assets/16188304/18743650/54ddea92-80ba-11e6-8792-f59db0d1b91c.png)

### Aim
* Stop, Start and maintain docker containers and images from the web as opposed to commandline or GUI

### How to
* Clone the following repo from your terminal `git@github.com:LyleH/docker_ui.git`

1. Run: `docker run -d -p 9000:9000 --privileged -v /var/run/docker.sock:/var/run/docker.sock uifd/ui-for-docker`

2. Open your browser to `http://<dockerd host ip>:9000`

![screen shot 2016-09-22 at 12 02 27](https://cloud.githubusercontent.com/assets/16188304/18744052/8074b602-80bc-11e6-93e5-17028a94fcf0.png)


That's it!
