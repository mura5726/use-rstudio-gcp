# use-rstudio-gcp

## running Rstudio
docker pull rocker/rstudio <br>
docker run -v $(pwd):/home/rstudio --name rstudio -d -p 8080:8787 rocker/rstudio

## closeing Rstudio
docker rm -f rstudio
docker rmi rocker/rstudio
