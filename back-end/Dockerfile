#pull repository image from Docker Hub
FROM node

# workdir inside container
WORKDIR usr/src

# copy from local directory to container directory (. means local directory)
COPY . .

EXPOSE 5000

RUN npm i
RUN npm run build

CMD ["npm", "start"];





