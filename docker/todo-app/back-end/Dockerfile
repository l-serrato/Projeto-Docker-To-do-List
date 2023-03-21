FROM node:14
ADD node_modules.tar.gz todobackend
COPY . .
EXPOSE 3001
ENTRYPOINT ["npm"]
CMD [ "start" ]