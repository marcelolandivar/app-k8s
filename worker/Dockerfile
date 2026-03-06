FROM node:16-alpine
WORKDIR "/app"
COPY worker/package.json ./
RUN npm install
COPY worker ./
CMD ["npm", "run", "start"]