FROM alpine
#RUN, COPY, ADD, FROM
#RUN mkdir -p /app
WORKDIR /app

#ADD VS. COPY
COPY myapp.sh /app

RUN ls /app && chmod +x myapp.sh && apk add --update bash

CMD [ "./myapp.sh" ] 
#con CMD se puede sobreescribir lo ejecucion al momento de la invocacion del docker.

#invocacion normal de la ejecucion inicial.
#ENTRYPOINT [ "bash", "myapp.sh" ]
#ENTRYPOINT +CMD