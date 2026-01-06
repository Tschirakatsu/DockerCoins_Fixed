FROM node:18-slim
WORKDIR /app
RUN npm install express redis@3
COPY files/ /app/files/
COPY webui.js /app/
EXPOSE 80
CMD ["node", "webui.js"]

