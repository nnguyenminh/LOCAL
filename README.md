### Landing Page with Django By Docker 


### Prerequisites

Have knowledge about Django, Javascript, CSS, Git, Docker


### Installation

Build an image of our landing page by Dockerfile on a Docker machine => run command
```
docker build -t nmnhat:local .
```


### Deployment

An [image](https://hub.docker.com/repository/docker/nmnhat/local) is built and stored on Docker Hub with name local and tag default is latest => On a Docker web machine => run command
```
docker run -dp 8000:8000 nmnhat/local
```


### Final result

And a public URL will be generated, like http://ip172-18-0-36-c9fok9s33d5g008bbtm0-8000.direct.labs.play-with-docker.com/


### Built With

* [Docker Hub](https://hub.docker.com/) - Docker Image Repositories
* [Docker Online Terminal](https://labs.play-with-docker.com/) - Learn and practice with docker directly on website
* [Django](https://www.djangoproject.com/) - Python web framework used to built website


### Authors

* **Nhat Nguyen** - *Owner* - [Github Profile](https://github.com/nnguyenminh)
* **Minh Nguyen** - *Supporter* - [Github Profile](https://github.com/nvminh0810)


### Acknowledgments

* Learn and practice Django
* Learn and practice Docker
* etc
