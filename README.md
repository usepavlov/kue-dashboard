# kue-dashboard

Simple Docker container for [kue's](https://github.com/Automattic/kue) web UI.

## Usage

Available on Docker Hub as [pavlov/kue-dashboard](https://hub.docker.com/r/pavlov/kue-dashboard).

    $ docker run -e REDIS_URL=redis://127.0.0.1:6379 -t pavlov/kue-dashboard

## Development

    $ make build
    $ make push

## License

[BSD 3-Clause](https://github.com/pavlovml/kue-dashboard/blob/master/LICENSE)
