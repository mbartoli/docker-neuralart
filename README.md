# docker-neuralart
Docker container to generate neural art, based on 'A Neural Algorithm of Artistic Style'

## Setup
Pull the docker repo
```
docker pull mbartoli/neuralart
```
and then open a shell within the container 
```
docker run -i -t mbartoli/neuralart /bin/bash
```
Then, in the new shell, run
```
luarocks install inn cunn nn qtlua image
```

### Automated Build 
See https://hub.docker.com/r/mbartoli/neuralart/ 

## TODO
Add CUDA capability  
