### How to use sqlite3 that built-in library into python3

If you can't use built-in sqlite3 library, You have to install these packages on Ubuntu.
And need to rebuild python binary.

```sh
sudo apt install libsqlite3-dev libbz2-dev libncurses5-dev libgdbm-dev liblzma-dev libssl-dev tcl-dev tk-dev libreadline-dev
```

### Create a project

```sh
django-admin startproject myblog .
```

### db migrate use sqlite3

```sh
python manage.py migrate
```

### Run web server

```sh
python manage.py runserver
```
