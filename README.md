#create a mysql database to see the ouput;
if you download this project,
##use the command npm install in frontend and backend directories.


####database creation:
create database users;
use users;
create table user_details(id int auto_increment primary key,username varchar(200) not null,password varchar(200) not null);
