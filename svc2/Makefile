.PHONY: docker.build
docker.build:
	docker build -t svc2:latest .

.PHONY: docker.run
docker.run:
	docker rm svc2svc
	docker run --rm -d --name svc2svc svc2 
	
.PHONY: docker.stop
docker.stop:
	docker stop svc2svc 

.PHONY: install
install:
	go install ./cmd/...

.PHONY: run
run:
	svc2