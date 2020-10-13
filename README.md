# README

# Ruby on Rails Tutorial sample application
This is the sample application for
[*Ruby on Rails Tutorial:
Learn Web Development with Rails*](https://www.railstutorial.org/)
(6th Edition)
by [Michael Hartl](https://www.michaelhartl.com/).

[You can open this app here!](https://whispering-springs-79425.herokuapp.com/)
## License
All source code in the [Ruby on Rails Tutorial](https://www.railstutorial.org/)
is available jointly under the MIT License and the Beerware License. See
[LICENSE.md](LICENSE.md) for details.
## Getting started
To get started with the app, clone the repo and then install the needed gems:
```
$ bundle install --without production
```
Next, migrate the database:
```
$ rails db:migrate
```
Finally, run the test suite to verify that everything is working correctly:
```
$ rails test
```
If the test suite passes, you'll be ready to run the app in a local server:
```
$ rails server
```
## Usage
You can sign up as a user and add microposts (max 140 characters). You can also add an image to these microposts which will be automatically resize. Users could have followers and follow the others. 99 sample users shipped along with this app as default (shown in db/seeds.rb file). There are also admins, who can delete other users profiles. You can sign in as a default user, who is also an admin:
```
email: example@railstutorial.org
password: foobar
```
## Author
Joanna Klosinska 

