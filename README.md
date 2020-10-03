# alpine-nginx-full

<p>
  <img src="https://img.shields.io/badge/openresty-1.15.8.3-green.svg?style=for-the-badge">
  <img src="https://img.shields.io/badge/lua-5.1.5-green.svg?style=for-the-badge">
  <img src="https://img.shields.io/badge/luarocks-3.3.1-green.svg?style=for-the-badge">
</p>

docker build -t alpine-nginx-full --build-arg LUA_VERSION=5.4.0 --build-arg LUAROCKS_VERSION=3.4.0 --build-arg OPENRESTY_VERSION=1.17.8.1 .

docker build -t alpine-nginx-full -f Dockerfile.node . 



This is a base image for use in other images. See Dockerfile for build steps.

### Usage:

```
FROM xkas/alpine-nginx-full-node:1.0.0
...
```
