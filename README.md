## openfaas-actions-multiarch

A Golang middleware microservice built as an ARM and Intel image, deployed over a cloud native tunnel with TLS + [inlets.dev](https://docs.inlets.dev)

1) Push code to repo
2) GitHub Actions builds and pushes a multi-arch OpenFaaS function for ARM and Intel
3) Pushes to private registry
4) Deploys to faasd running in your network over TLS with inlets tunnel (in this instance, to my RPi)

See my [sample endpoint](https://faasd.exit.openfaas.pro/function/go-example) which is running on an RPi3 with [faasd](https://blog.alexellis.io/faasd-for-lightweight-serverless/)

Forked from an example by [Oliver Jägle](https://github.com/mrsimpson)

Also influenced by [Mike Grant](https://twitter.com/mike_grant_/status/1234522382049607682)
