# build
$ docker image build -t sample-es02 .

# make container
$ docker container run -d --name sample-es02 -p 29200:9200 sample-es02

