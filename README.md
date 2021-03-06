![](https://img.shields.io/badge/Microverse-blueviolet)

# hello-rails-back-end

## Description

> Since I familiar with Rails and React I put them together in a new kind of 'Hello World!' app. This exercise is going to have you create a React front-end with a Rails back-end and connect them to display a random message.



## Learning objectives

- Implement a connection between a Ruby on Rails back-end and React front-end.
- Understand pros and cons of different approaches of connecting Ruby on Rails back-end with React front-end.


## Getting Started

To get a local copy for this project and running follow these simple example steps.

## Link

[react-front-end](https://github.com/sja-thedude/hello-react-front-end/tree/setup)

[heroku](https://sja-thedude-api.herokuapp.com/api/messages)

## Setup

### Creating the hello-rails-back-end

```bash
$   rails new hello-rails-back-end --api --database=postgresql
$   cd hello-rails-back-end # Move into the application directory
```


### Clone this repository

```bash
$ https://github.com/sja-thedude/hello-rails-back-end.git
$ cd hello-rails-back-end
```

### Create the database

```bash
$   rails db:create   # or
$   rake db:create
```


### Install linter and 

- Rubocop gem

```bash
$  bundle init
$  bundle install
```


- Run linter

```bash
$  rubocop .
```

- In auto-correct mode, RuboCop will try to automatically fix offenses:

```bash
$  rubocop -A # or
$  rubocop --auto-correct-all
```


## Built With

This project is build with:

-  ![Ruby](https://img.shields.io/badge/-Ruby-000000?style=flat&logo=ruby&logoColor=red)
-  ![Ruby on Rails](https://img.shields.io/badge/-Ruby_on_Rails-000000?style=flat&logo=ruby-on-rails&logoColor=blue)

## Authors

👤 **Syeda Juveria Afreen**

- GitHub: [@sja-thedude](https://github.com/sja-thedude)
- Twitter [@sja_thedude](https://twitter.com/sja_thedude)
- LinkedIn [sjathedude](https://www.linkedin.com/in//)

## 🤝 Contributor


Contributions, issues, and feature requests are welcome!

Feel free to check the [issues page](https://github.com/sja-thedude/hello-rails-back-end/issues).

## Show your support

Give a ⭐️ if you like this project!

## Acknowledgments

- Credit to [Gregoire Vella on Behance](https://www.behance.net/gregoirevella), the author of the original [design guidelines](https://www.behance.net/gallery/19759151/Snapscan-iOs-design-and-branding?tracking_source=)


## 📝 License

This project is [MIT](./MIT.md) licensed.