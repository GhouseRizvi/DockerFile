ARG VERSION
# we can also specify the default version as below or you can use the arguments to specify the version < docker build -t arg:v1 --build-arg VERSION=9 . >
FROM almalinux:${VERSION:-8}

ARG GREET="Hi Welcom to the almalinux"
RUN echo "${GREET}"
RUN echo "${VERSION}"