FROM node:11-alpine

ENV diameter=4.0

COPY compute.js .

CMD node compute.js

# docker build -t jsparam .
# docker run --rm jsparam
# docker run --rm -e diameter=5.0 jsparam