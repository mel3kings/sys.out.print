FROM node:6.12
ADD ./ src/
WORKDIR src/
RUN node -v
RUN npm install

EXPOSE 3000

CMD [ "npm", "start" ]