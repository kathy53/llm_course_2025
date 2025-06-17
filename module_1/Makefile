build:
	docker build -t llm_zoomcamp .
jupyter:
	docker run --rm -it -p 8888:8888 -v $(shell pwd):/usr/src/app llm_zoomcamp 

bash:
	docker run --rm -it -v $(shell pwd):/usr/src/app --env-file ./.env llm_zoomcamp /bin/bash
