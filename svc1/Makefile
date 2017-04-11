.PHONY: docker.build
docker.build:
	docker build -t svc1:latest .

.PHONY: docker.run
docker.run:
	docker rm svc1svc
	docker run --rm -d --name svc1svc svc1 
	
.PHONY: docker.stop
docker.stop:
	docker stop svc1svc 

.PHONY: install
install:
	go install ./cmd/...

.PHONY: run
run:
	svc1