FROM bash

ARG FLAG=MKzgASrjByzdIaTdpaTdq2vzAIgY

RUN adduser -D suzen

ADD hello /bin/hello
ADD Director.txt /home/suzen/Director.txt


WORKDIR /home/suzen 
USER suzen

RUN sed -i "s/INSERT_FLAG_HERE/${FLAG}/g" Director.txt


ENTRYPOINT ["/bin/hello"]

