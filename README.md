# DockerFiles
Docker files examples

For Running Appium via Container :

mv ./AppiumServerDockerfile  ~/<UserFolder>/Dockerfile
cd ~/<UserFolder>
docker build . -t imagename
docker run -d -p 4723:4723 imagename