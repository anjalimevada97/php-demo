# PHP MySQL CRUD

Git repository with the following command:

```
cd existing_repo
git remote add origin https://github.com/anjalimevada97/php-demo.git
git branch -M main
git push -uf origin main
```

## Creating the Database Table

```
CREATE TABLE employees (
    id INT NOT NULL PRIMARY KEY AUTO_INCREMENT,
    name VARCHAR(100) NOT NULL,
    address VARCHAR(255) NOT NULL,
    salary INT(10) NOT NULL
);
```
