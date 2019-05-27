#escape=`

# Stage 1 - the build react app
FROM nodejs:1 
WORKDIR /app
COPY . /app/

ENV NODE_ENV production
WORKDIR /app
# RUN chown -R node:node /usr/src/app/
EXPOSE 4654

ENTRYPOINT ["C:\\Program Files\\nodejs\\node.exe", "."]
