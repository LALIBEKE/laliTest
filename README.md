 git branch -b lali


  docker pull python:3.7.17-alpine3.18


## build
  docker build -t convertor .

   docker build -t lali .


## wsl:-RUN 

 docker run -v $PWD/images:/app/images -v $(pwd)/output:/app/output convertqr images


