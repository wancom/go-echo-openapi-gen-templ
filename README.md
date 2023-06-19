# Open API generator template for golang echo server
## How to use
Clone the template repository and run the command below WITHOUT INTO REPOSITORY DIR.
```
mkdir -p out/go && cp go-echo-openapi-gen-templ/.openapi-generator-ignore out/go/
docker run --rm -v "${PWD}:/local" openapitools/openapi-generator-cli generate -i /local/api.yml -g go-echo-server -o /local/out/go -c /local/mytmpl/config.yaml
```

## LICENSE
The template is based on the openapi-generator template(go-echo-server).  
This repository succeed to the same license Apache License 2.0.