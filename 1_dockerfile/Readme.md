# Dockerfile tp

## Package curl

My computer dosen't have curl installed, and I want a docker to run curl on my laptop (as shown with python in the previous tp).

I want to be able to do this :

```bash
cd curl
docker image build -t my-curl .
```

And then, run it.

You have to do is to **write the Dockerfile in the curl directory**.

I want to use it like that : 

```bash
docker container run --rm my-curl:latest https://example.com
```

## Package my bash script

I want the script in the folder bash to be run within a `ubuntu` container.

**You must write the docker container.**

## Package a python app

I want my python app to be packaged in a docker container using python **2.7**.

You have to do is to **write the Dockerfile in the python directory**.

I want to run it like that : 

```bash
docker run -d -p 5000:5000 my-hello-world
```

And I want it to be pushed on docker hub.

Here you must put the link on :