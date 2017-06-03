[![](https://images.microbadger.com/badges/image/ufirstgroup/alpine-rubocop.svg)](https://microbadger.com/images/ufirstgroup/alpine-rubocop "Get your own image badge on microbadger.com")

# docker-alpine-rubocop

based on https://github.com/mhart/alpine-rubocop

```bash
docker run -it --rm \
  -e USER_ID=`id -u` \
  -e GROUP_ID=`id -g` \
  -v $HOME:/homedir \
  -v `pwd -P`:/workdir  \
  ufirstgroup/alpine-rubocop:latest rubocop
```
