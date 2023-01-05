# elastichsearch-docker

## building docker image
`$ docker build -t dev-elasticsearch -f Dockerfile-logstash`

## testing logstash
`$ docker run -ti --rm dev-elasticsearch /usr/share/logstash/bin/logstash -e 'input{stdin{}} output{stdout{}}'`