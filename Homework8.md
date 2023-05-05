# HOMEWORK - 8

## Queries

1 - Create a table called 'employee' in your test database with columns id (INTEGER), name VARCHAR(50), birthday DATE, and email VARCHAR(100).

2 - Using the 'Mockaroo' service, add 50 records to the created employee table.

3 - Perform 5 UPDATE operations that update the other columns according to each column.

4 - Perform 5 DELETE operations that delete the corresponding row according to each column.

</br>

## Solution

```1
CREATE TABLE employee(
id integer,
name VARCHAR(50),
birthday DATE,
email VARCHAR(100)
);
```

```2
insert into employee (id, name, birthday, email) values (1, 'Ulrica', '1992-11-06', 'ufirpi0@mozilla.com');
insert into employee (id, name, birthday, email) values (2, 'Ned', '1984-07-14', 'nnewson1@tumblr.com');
insert into employee (id, name, birthday, email) values (3, 'Danette', '1970-10-25', 'dgonzalo2@nature.com');
insert into employee (id, name, birthday, email) values (4, 'Ally', '1988-12-08', 'abeaton3@unblog.fr');
insert into employee (id, name, birthday, email) values (5, 'Granger', '1981-12-22', 'ggrzelczak4@icio.us');
insert into employee (id, name, birthday, email) values (6, 'Filippo', '1991-07-15', 'fwilkisson5@mail.ru');
insert into employee (id, name, birthday, email) values (7, 'Candi', '1995-12-03', 'cborrington6@zimbio.com');
insert into employee (id, name, birthday, email) values (8, 'Cristobal', '1994-07-17', 'cbranni7@so-net.ne.jp');
insert into employee (id, name, birthday, email) values (9, 'Jerry', '2003-12-23', 'jnardoni8@tamu.edu');
insert into employee (id, name, birthday, email) values (10, 'Alysia', '1979-04-19', 'acollabine9@msu.edu');
insert into employee (id, name, birthday, email) values (11, 'Laurens', '1971-10-19', 'lkema@salon.com');
insert into employee (id, name, birthday, email) values (12, 'Aylmar', '2001-04-27', 'aandreassonb@1und1.de');
insert into employee (id, name, birthday, email) values (13, 'Faydra', '1983-02-27', 'fjoslingc@examiner.com');
insert into employee (id, name, birthday, email) values (14, 'Bron', '2001-02-09', 'bmouatd@hexun.com');
insert into employee (id, name, birthday, email) values (15, 'Natty', '1983-09-30', 'nmenichinoe@smh.com.au');
insert into employee (id, name, birthday, email) values (16, 'Joycelin', '1991-10-22', 'jovellf@bloglines.com');
insert into employee (id, name, birthday, email) values (17, 'Suzanne', '1980-11-06', 'sdeavilleg@sina.com.cn');
insert into employee (id, name, birthday, email) values (18, 'Jethro', '1977-07-24', 'jrossbrookeh@163.com');
insert into employee (id, name, birthday, email) values (19, 'Kelley', '1987-10-09', 'kmerritti@narod.ru');
insert into employee (id, name, birthday, email) values (20, 'Sal', '1969-08-12', 'sbrowerj@noaa.gov');
insert into employee (id, name, birthday, email) values (21, 'Johny', '1992-12-02', 'jbeedlek@shareasale.com');
insert into employee (id, name, birthday, email) values (22, 'Rollie', '2000-11-26', 'rmaxfieldl@parallels.com');
insert into employee (id, name, birthday, email) values (23, 'Lorilee', '1969-05-19', 'lmccallm@cbsnews.com');
insert into employee (id, name, birthday, email) values (24, 'Daloris', '1993-03-01', 'dallsebrookn@bandcamp.com');
insert into employee (id, name, birthday, email) values (25, 'Lanny', '2000-04-29', 'lkunzelmanno@macromedia.com');
insert into employee (id, name, birthday, email) values (26, 'Dena', '1976-02-21', 'dwestwoodp@usda.gov');
insert into employee (id, name, birthday, email) values (27, 'Brunhilde', '1977-08-25', 'bfosdikeq@skyrock.com');
insert into employee (id, name, birthday, email) values (28, 'Loreen', '1980-04-16', 'lkilcoyner@istockphoto.com');
insert into employee (id, name, birthday, email) values (29, 'Ramona', '1998-11-16', 'rfersons@nymag.com');
insert into employee (id, name, birthday, email) values (30, 'Christabella', '2003-09-26', 'clangt@elpais.com');
insert into employee (id, name, birthday, email) values (31, 'Pauline', '2001-05-22', 'pzuppau@loc.gov');
insert into employee (id, name, birthday, email) values (32, 'Charleen', '1984-09-28', 'csindlev@hao123.com');
insert into employee (id, name, birthday, email) values (33, 'Calvin', '2005-03-23', 'cculpanw@mapy.cz');
insert into employee (id, name, birthday, email) values (34, 'Jeffry', '1987-09-06', 'jmchirriex@soup.io');
insert into employee (id, name, birthday, email) values (35, 'Emmye', '1977-04-27', 'eslydey@arstechnica.com');
insert into employee (id, name, birthday, email) values (36, 'Ivar', '1981-09-09', 'itortoishellz@devhub.com');
insert into employee (id, name, birthday, email) values (37, 'Grady', '2001-06-14', 'gvanderkrui10@qq.com');
insert into employee (id, name, birthday, email) values (38, 'Esmeralda', '1970-12-28', 'egrigorini11@ehow.com');
insert into employee (id, name, birthday, email) values (39, 'Renata', '1988-07-10', 'rlintall12@flavors.me');
insert into employee (id, name, birthday, email) values (40, 'Mabel', '1974-07-28', 'mmaydway13@woothemes.com');
insert into employee (id, name, birthday, email) values (41, 'Gert', '1979-03-23', 'gmayow14@nbcnews.com');
insert into employee (id, name, birthday, email) values (42, 'Cletus', '1990-01-19', 'cpidduck15@infoseek.co.jp');
insert into employee (id, name, birthday, email) values (43, 'Frederico', '1985-04-27', 'frelfe16@deliciousdays.com');
insert into employee (id, name, birthday, email) values (44, 'Joana', '1994-09-19', 'jskellington17@facebook.com');
insert into employee (id, name, birthday, email) values (45, 'Barret', '1978-12-08', 'bcallender18@npr.org');
insert into employee (id, name, birthday, email) values (46, 'Deana', '1993-12-02', 'dtitchmarsh19@cdbaby.com');
insert into employee (id, name, birthday, email) values (47, 'Gordon', '2007-04-08', 'gcasini1a@wordpress.org');
insert into employee (id, name, birthday, email) values (48, 'Deirdre', '2004-08-22', 'dclubley1b@tinyurl.com');
insert into employee (id, name, birthday, email) values (49, 'Aggie', '1991-02-17', 'aoakshott1c@globo.com');
insert into employee (id, name, birthday, email) values (50, 'Rebekah', '1998-07-08', 'rgaynesford1d@vimeo.com');
```

```3
UPDATE employee
SET name = "Sofia"
WHERE id = 1;

UPDATE employee
SET email = "sqlLesson@gmail.com"
WHERE name like "A%";

UPDATE employee
SET name = "Martin"
WHERE  email = "ggrzelczak4@icio.us";

UPDATE employee
SET birthday = "1982-01-11"
WHERE length(name) < 6;

UPDATE employee
SET email = NULL
WHERE name = "Ned";
```

```4

DELETE FROM employee
WHERE length(name) > 6;

DELETE FROM employee
WHERE id = 1;

DELETE FROM employee
WHERE email like "C%";

DELETE FROM employee
WHERE birthday BETWEEN "1999-01-01" AND "2002-01-01";

DELETE FROM employee
WHERE length(name) in (3,4);
```
