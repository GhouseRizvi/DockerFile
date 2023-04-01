ARG VERSION
# we can also specify the default version as below or you can use the arguments to specify the version < docker build -t arg:v1 --build-arg VERSION=9 . >
FROM almalinux:${VERSION:-8}

ARG GREETING="Hi Welcom to the almalinux"
ENV GREET=${GREETING}
RUN echo "${GREET}"
# Below variable is out of scope so can't be executed
# RUN echo "${VERSION}"

#for best results we use args and env