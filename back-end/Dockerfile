#pull repository image from Docker Hub
FROM node:16

# workdir inside container
WORKDIR usr/src

# copy from local directory to container directory (. means local directory)
COPY . .

EXPOSE 5000

RUN npm i
RUN npm run build
RUN npm run prisma:seed

CMD ["npm", "start"];





