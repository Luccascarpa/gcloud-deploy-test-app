Following the google tutorial on how to deploy a python app to cloud run

Added: ENV 8080 to dockerfile

To run:
```
$ docker image build -t helloworld .
```
```
$ docker run -p 8080:8080 -d helloworld
```
