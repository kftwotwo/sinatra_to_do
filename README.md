# {Application Name}

#### {Brief description of application}, {Date of current version}

#### By [Kevin Finley](http://www.kfinley.com)

## Description

{content}

## Setup/Installation Requirements

Go to github and clone the repository `https://github.com/kftwotwo/sinatra_do_to.git`.  
Once the repository is cloned:
```
$ git clone sinatr_do_to
$ cd sinatra_do_to
$ bundle install
```

### Setup Database
From the command line access you postgres database with the `psql` command. In psql do the following:
```
> CREATE DATABASE to_do_test WITH TEMPLATE to_do;
> CREATE TABLE tasks (id serial PRIMARY KEY, description varchar, list_id int);
> CREATE TABLE lists (id serial PRIMARY KEY, name varchar);
```

## Known Bugs

If you notice any bugs or problems you can fill out an issue [here](http://www.github.com/kftwotwo/{project}/issue) or you can clone the project and work on it yourself!

## Contact details
Here is my email kf.two.two@gmail.com

## Contribute

Issue Tracker: https://github.com/kftwotwo/{project}/issues

Source Code: https://github.com/kftwotwo/{project}


## Technologies Used
```
HTML
CSS
Ruby
Javascript
```
### License

*This is under a MIT License*

Copyright (c) 2016 **_Kevin Finley_**
