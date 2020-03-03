readme.txt

sudo -u postgres psql

CREATE  ROLE newuser WITH LOGIN INHERIT PASSWORD 'password';

createdb todos-dev
sequelize db:migrate