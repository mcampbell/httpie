# httpie

Docker httpie container.  About 1/3 the size of most on hub.docker.com.

# Usage

`docker run -it --rm mcampbell/httpie [HTTPIE_ARGS_HERE]`

Typically you will alias `http` to `docker run -it --rm mcampbell/httpie`, so your command line becomes the same as if
you had the binary installed locally.

By default the `HTTPIE_ARGS` are set to `--help`.

