FROM node as node

WORKDIR /app



COPY . .

RUN npm install
RUN npm install --save rxjs-compat
RUN npm install -g @angular/cli
RUN npm run build --prod


CMD ng serve --host 0.0.0.0
