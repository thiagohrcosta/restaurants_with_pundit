# Restaurant with Pundit
![main](https://res.cloudinary.com/dloadb2bx/image/upload/v1619494712/restaurant1_qs0p9t.png)

## Technologies
This project was created with:

 - [Ruby](https://www.ruby-lang.org/pt/)
 - [Rails](https://rubygems.org/gems/rails)
 - [ERB](https://ruby-doc.org/stdlib-2.7.1/libdoc/erb/rdoc/ERB.html) (for template system with Ruby)
 - [Pry-byebug](https://rubygems.org/gems/pry-byebug/versions/3.4.0?locale=pt-BR) (for debugging)
 - [Bootstrap](https://getbootstrap.com/)
 - [Simple_form](https://rubygems.org/gems/simple_form)
 - Postgresql
 - [Devise](https://rubygems.org/gems/devise/versions/4.2.0?locale=pt-BR)
 - [Pundit](https://rubygems.org/gems/pundit/versions/1.1.0)


## How to run this project
Download or clone it. Then run in the main folder the command `rails server`. If needed, run `bundle install` to check if all gems are correctly installed. Then open the project on `localhost:3000`


## What user can do?
As user you can manipulate all **CRUD** operations like:

 - Guest can create a account;
 - Guest can't access restaurants - Need to login;
 - Guest can create a account and login;
 - User can create a new restaurant;
 - User can edit or delete their own restaurant;
 - User can't edit or delete restaurants created by others users.
