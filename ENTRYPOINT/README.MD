### ENTRY POINT ###

Entry point is also used to run the container just like cmd but there are few diffrences
* we cannot override entrypoint if tried so it'll append to the existing command.
* we can overrride CMD
* fro best results we use entry point and CMD

if you use cmd and entry point here cmd act as a arguement provider to the entry point.

