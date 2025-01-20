FROM node:17.9.0-slim
LABEL maintainer="Shubhamksawant"
WORKDIR /app
COPY . .
RUN npm install
EXPOSE 1004
ENV MONGO_URL=""
ENV ADMIN_EMAIL="mail@shubhamksawant.in"
CMD ["npm", "start"]