FROM node:16-alpine3.16
WORKDIR /app/back-end
COPY . .
ADD node_modules.tar.gz .
EXPOSE 3001
ENTRYPOINT ["npm"]
CMD ["start"]
