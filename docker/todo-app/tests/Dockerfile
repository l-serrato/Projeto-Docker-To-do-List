FROM mjgargani/puppeteer:trybe1.0
WORKDIR /app
ADD node_modules.tar.gz .
COPY . .
EXPOSE 3000
ENTRYPOINT ["npm"]
CMD [ "test" ]

