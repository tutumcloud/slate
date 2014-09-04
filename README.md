tutum-docker-slate
==================


Usage
-----

In your source documentation folder (which looks like [this](https://github.com/tripit/slate/tree/master/source)), create a `Dockerfile` with the following contents:

	FROM tutum/slate


Build the image and run it:

	docker build -t mydocs .
	docker run -d -p 4567:4567 mydocs


Go to `http://localhost:4567/` and you will see your new API beautiful documentation.