
## Connect to database
```
  psql -h 127.0.0.1 -p 5432 -U postgres -W  postgres
```

## Create table blog
```
  CREATE TABLE Blog (post varchar(255));
```

## Insert blog post
```
  INSERT INTO blog(post) VALUES ('Start my new blog!');
```

## Select blog post
```
  SELECT * FROM blog;
```
