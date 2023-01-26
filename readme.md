POSTGRES_HOST=127.0.0.1
POSTGRES_PORT=5432
POSTGRES_USER=postgres
POSTGRES_PASSWORD=root
POSTGRES_DATABASE=app
PORT=3000
MODE=DEV
RUN_MIGRATIONS=true


nest new api

.. per mysql
npm install --save typeorm mysql2

..ok quello sotto
npm install --save @nestjs/typeorm pg @nestjs/config

https://blog.devgenius.io/setting-up-nestjs-with-postgresql-ac2cce9045fe

cd .\api
npm run start:dev

nest g mo feed
nest g s feed/services/feed --flat --no-spec
nest g co feed/controllers/feed --flat --no-spec


npm i -g @ionic/cli
ionic start
cd .\MyApp

ionic generate component home/components/header

ionic generate component home/components/header/popover

"# personalProject" 
