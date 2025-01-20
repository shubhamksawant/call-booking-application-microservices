FROM node:17.9.0-slim
LABEL maintainer=Shubhamksawant
WORKDIR /app
COPY . /app
RUN npm install
EXPOSE 1004
ENV MONGO_URL=""
CMD ["npm", "start"]