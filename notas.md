# Docker

Usar
```Dockerfile
ENV PYTHONUNBUFFERED 1
```
Esto es recomendable para correr python en docker containers.
It does not allow python to buffer the output and prints it directly.

```bash
% docker build .
```
```bash
% docker-compose build
```
