# use-rstudio-gcp

docker pull rocker/rstudio
docker run -v $(pwd):/home/rstudio --name rstudio -d -p 8080:8787 rocker/rstudio
