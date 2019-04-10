# Docker Sphinx Documentation Guide

## Initial Image with Sphinx

``` cmd
docker build -t crema/sphinx:1.0 -f Dockerfile.sphinx .
```

## Sphinx Build Container

``` cmd
docker build -t crema/sphinx-builder:1.0 -f Dockerfile.sphinx-builder .
```
