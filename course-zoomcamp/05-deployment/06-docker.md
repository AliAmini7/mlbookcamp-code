## 5.6 Environment management: Docker

<a href="https://www.youtube.com/watch?v=wAtyYZ6zvAs"><img src="images/thumbnail-5-06.jpg"></a>

[Slides](https://www.slideshare.net/AlexeyGrigorev/ml-zoomcamp-5-model-deployment)


## Installing Docker

### Ubuntu 

```bash
sudo apt-get install docker.io
```

To run docker without `sudo`, follow [this instruction](https://docs.docker.com/engine/install/linux-postinstall/).


### Windows

1- Use the following link to install ubuntu on windows 10:
https://ubuntu.com/tutorials/ubuntu-on-windows#1-overview 
note: I enabled WSL 2.

2- Use the following in the Ubuntu terminal to install docker:

```bash
sudo apt-get install docker.io
```
3- You may need the following post-installation steps if you need to add your user to the docker group:

```bash
sudo groupadd docker
```

```bash
sudo usermod -aG docker $USER
```

```bash
newgrp docker 
```

check if docker works fine: 
```bash
docker run hello-world
```

### MacOS

Please send a PR!


## Notes

Add notes from the video (PRs are welcome)


<table>
   <tr>
      <td>⚠️</td>
      <td>
         The notes are written by the community. <br>
         If you see an error here, please create a PR with a fix.
      </td>
   </tr>
</table>


## Nagivation

* [Machine Learning Zoomcamp course](../)
* [Session 5: Deploying Machine Learning Models](./)
* Previous: [Python virtual environment: Pipenv](05-pipenv.md)
* Next: [Deployment to the cloud: AWS Elastic Beanstalk (optional)](07-aws-eb.md)
