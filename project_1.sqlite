CREATE TABLE friends (
id INTEGER,
name TEXT,
birthday DATE
);

INSERT INTO friends (id, name, birthday)
VALUES(1, 'Ororo Munroe', '1940-05-30');

SELECT * FROM friends;

INSERT INTO friends (id, name, birthday)
VALUES(2, 'Joe Biden', '1950-02-23');

INSERT INTO friends (id, name, birthday)
VALUES(3, 'Bob Smith', '1996-11-27');

UPDATE friends
SET name = 'Storm Munroe'
WHERE id = 1;

ALTER TABLE friends
ADD COLUMN email TEXT;

UPDATE friends
SET email = 'Storm@codecademy.com'
WHERE id = 1;

UPDATE friends
SET email = 'Joe@codecademy.com'
WHERE id = 2;

UPDATE friends
SET email = 'Bob@codecademy.com'
WHERE id = 3;

DELETE FROM friends WHERE id = 1;

SELECT * FROM friends;