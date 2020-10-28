# FS1030php

Credit: https://www.tutorialrepublic.com/php-tutorial/php-mysql-crud-application.php

## Clone repo

Open command line/terminal

Mac users go to /applications/xampp/htdocs
Windows users go to c:/xampp/htdocs/ folder

Clone repo there

```
git clone https://github.com/tarun27in/FS1030
```

## Create DB and Table

Copy the below commands in workbench or mysql command line

```
CREATE DATABASE demo;
USE demo;
CREATE TABLE employees (
`id` int(11) NOT NULL AUTO_INCREMENT,
`name` varchar(100) not null,
`address` varchar (255) not null,
`salary` double not null,
PRIMARY KEY (`id`) 
) ENGINE=InnoDB  DEFAULT CHARSET=latin1 AUTO_INCREMENT=1;
```

## Execute code

Open http://localhost/FS1030php/

## To know about php environment

Open http://localhost/FS1030php/phpinfo.php