FROM almalinux
ENV COURSE="devops" \
    TRAINER="shivakumar"
## label is used for giving tag so that we can filter also .. docker images -f "label=trainer=shivakumar" ..
CMD ["sleep","15"]
## docker always runs in foreground but we make it background using -d .. docker run -d env.v1

## we can see env output at ... docker exec -it 8d bash ... enter env ... these are environment variable we can see at environment variable it will add in the server