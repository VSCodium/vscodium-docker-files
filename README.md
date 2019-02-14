# vscodium-docker-files

makes it easier to troubleshoot problems in the Travis builds

the dockerfiles should install the necessary dependencies and clone the vscodium + vscode repos. then you can drop in and build or tweak things as desired.

### building
for now there's just the 32-bit file:
```bash
docker build -t vscodium-ia32 -f Dockerfile.ia32 .
```

### getting a shell
```bash
docker run -it vscodium-ia32 bash 
```

## License
MIT
