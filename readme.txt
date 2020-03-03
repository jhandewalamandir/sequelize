readme.txt

1. sudo -u postgres psql

2. CREATE  ROLE newuser WITH LOGIN INHERIT PASSWORD 'password';

3. npm init

4. npm install

5. npm install -g sequelize-cli

6. npm install --save sequelize pg pg-hstore

7. npm install -g pg

8. createdb todos-dev
9. sequelize db:migrate

10. npm run start:dev

11. curl -X POST http://localhost:3500/api/todos --data "title=Did it"
12. curl -X GET http://localhost:3500/api/todos
13. curl -X POST http://localhost:3500/api/todos/1/items --data "content=I am a child element"
14. curl -X PUT http://localhost:3500/api/todos/1 --data "title=sunia"
15. curl -X DELETE http://localhost:3500/api/todos/2
16. curl -X GET http://localhost:3500/api/todos
17. curl -X DELETE http://localhost:3500/api/todos/2



12. 