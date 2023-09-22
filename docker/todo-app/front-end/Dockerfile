FROM node:16-alpine3.16
WORKDIR /app/front-end
COPY . .
ADD node_modules.tar.gz .
EXPOSE 3000
ENTRYPOINT ["npm"]
CMD ["start"]