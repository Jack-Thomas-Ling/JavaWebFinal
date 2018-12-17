# JavaWebFinalProject
- This is the first version of web project based on experiment 9. It can be successful only in connecting mysql 8.0.
- You guys can clone this project and test it.
- Here is the MySQL .sql:
> CREATE DATABASE `test` 
/*!40100 DEFAULT CHARACTER SET utf8mb4 COLLATE utf8mb4_0900_ai_ci */;
CREATE TABLE `users` ( <br>
  `id` int(11) NOT NULL AUTO_INCREMENT,
  `name1` varchar(50) DEFAULT NULL,
  `gender` varchar(10) DEFAULT NULL,
  PRIMARY KEY (`id`)
) ENGINE=InnoDB AUTO_INCREMENT=3 DEFAULT CHARSET=utf8;
