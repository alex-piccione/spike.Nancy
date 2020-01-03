# spike.Nancy

Spike for Nancy

[https://github.com/alex75it/spike.nancy/workflows/Build Docker image/badge.svg]


## GitHub Docker image creation

### Step 1: Authenticate
$ docker login docker.pkg.github.com --username alex-piccione
### Step 2: Tag
$ docker tag IMAGE_ID docker.pkg.github.com/alex75it/spike.nancy/IMAGE_NAME:VERSION
### Step 3: Publish
$ docker push docker.pkg.github.com/alex75it/spike.nancy/IMAGE_NAME:VERSION
