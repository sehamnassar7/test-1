FROM openjdk

WORkDIR /application

COPY seham.java .

RUN javac seham.java

CMD java seham 