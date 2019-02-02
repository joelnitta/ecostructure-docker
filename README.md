# ecostructure-docker

[Dockerfile](https://github.com/joelnitta/ecostructure-docker/blob/master/Dockerfile) and [image](https://hub.docker.com/r/joelnitta/ecostructure/) for running [ecostructure](https://github.com/kkdey/ecostructure).

## Example Usage

Pull the most recent build:

```
docker pull joelnitta/ecostructure
```

Launch the container:

```
docker run -d -p 8787:8787 -e PASSWORD=clever_pw -e USER=rstudio joelnitta/ecostructure
```

For a more detailed example, see the [vignette](https://github.com/joelnitta/ecostructure-docker/blob/master/ecostructure.rmd).
