help:
	# build
	# run
	# shell

build:
	docker build \
		--tag http_server_python \
		.

run:
	docker run \
		--rm -it \
		--publish 8000:8000 \
		http_server_python

shell:
	docker run \
		--rm -it \
		--publish 8000:8000 \
		--entrypoint /bin/sh \
		http_server_python