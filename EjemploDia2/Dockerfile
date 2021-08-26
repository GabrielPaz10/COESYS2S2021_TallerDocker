#para obtener la version de node
FROM node:15.11.0

#se crea el directorio de trabajo
WORKDIR /app

#se copian los packages
COPY package*.json  ./

#se ejecuta el comando para instalar las dependencias
RUN npm install 

# se copian todos los archivos al contenedor
COPY . .

#se ejecuta la aplicacion
CMD ["npm", "start"]