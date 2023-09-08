FROM node:18-alpine
WORKDIR /frontend
# ENV API_BASE_URL="http://testbackend.manthanthakkar.works"
COPY . .
RUN npm install 
CMD [ "npm", "start" ]
EXPOSE 3000