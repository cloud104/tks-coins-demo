FROM node:12-slim
RUN npm install express
RUN npm install redis@v3.1.2
RUN npm install holderjs
COPY files/ /files/
COPY webui.js /
CMD ["node", "webui.js"]
EXPOSE 80
