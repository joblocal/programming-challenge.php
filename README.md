# PHP Programming Challenge: RESTful ToDo Service

## Objective

Implement a ToDo-Service which can be used via a RESTful API.

### Key features:
 * Store ToDo-Items in a database (use any database driver you like, e.g. SQLite)
 * A ToDo-Item consists of at least a 'title' (string, required)
 * Provide a [CRUD](https://en.wikipedia.org/wiki/Create,_read,_update_and_delete)- and [RESTful](https://en.wikipedia.org/wiki/Representational_state_transfer)-API-Endpoint for a ToDo-List
 * Write tests for your API-Endpoints & Models
 * Your repository contains meaningful commit messages
 
Nice to haves:
 * +1 [JSON API Spec](http://jsonapi.org/)
 * +1 Provide a meaningful API documentation

For an example consumer application for your API, have a look [here](http://todomvc.com/examples/vue/).

## Installation / Getting started
Please do **not** fork this repository, but clone it and re-initialize it as your own repository.
Make the first commit without applying any changes to the code. 
Then, start your solution.

```sh
git init .
git add .
git commit -m "Your initial commit message of choice"
```

Ensure you have the following software (globally) installed on your system:

* `[PHP](http://php.net/)` ^7.2
* `[Composer](http://getcomposer.org/)` ^1.5

```sh
# install dependencies
composer install

# check the coding style
composer lint

# run the tests
composer test

# start the dev server
composer start
```

## Project submission

Feel free to place this test on your Github/Gitlab/Bitbucket/... account as a public repository. Send the link back to Joblocal. We are looking forward to hearing from you. Good luck! :)