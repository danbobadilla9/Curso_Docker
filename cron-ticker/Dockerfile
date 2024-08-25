FROM node:19.2-alpine3.16
# cd app
WORKDIR /app
#Dest / app
COPY app.js package.json ./

#Dest / app
COPY app.js ./

# instalar 
RUN npm install
# comando correr la imagen  
CMD ["node","app.js"]