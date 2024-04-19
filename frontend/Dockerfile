FROM node:21
WORKDIR /app
COPY . /app
RUN npm i
COPY .env.sample .env
CMD ["npm","run","dev"]
