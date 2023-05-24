
# Start from a Node.js version 14 image
FROM node:16-alpine

EXPOSE 3001

WORKDIR /app/back-end

ADD node_modules.tar.gz .

COPY . .

ENTRYPOINT [ "npm" ]

CMD ["start"]