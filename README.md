# pew-pew for WordPress Devs
Easily upload your plugin or theme to the wordpress.org directory

## How to use

```bash
docker run --rm -v `pwd`:/workspace nateinaction/pew-pew plugins my-fancy-plugin 1.0.1 user pass
```

## How to contribute

1. Fork and clone the repo
2. Make changes
3. Build local docker image

    ```bash
    docker build -t pew-pew .
    ```

4. Test local image

    ```bash
    docker run --rm -v `pwd`:/workspace pew-pew plugins my-fancy-plugin 1.0.1 user pass
    ```
 
5. Submit PR
