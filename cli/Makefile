.PHONY: docker.build
docker.build:
	docker build -t cli:latest .

.PHONY: docker.run
docker.run:
	docker rm clisvc
	docker run --rm -d --name clisvc cli 
	
.PHONY: docker.stop
docker.stop:
	docker stop clisvc 

.PHONY: install
install:
	go install .

.PHONY: run
run:
	cli