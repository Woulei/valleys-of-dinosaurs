# Valley of Dinosaurs

Simple Rails app made during the Codaisseur Academy. This was our first experience with ruby on Rails.
The app two models, the Valley and the Dinosaur. They have a one-to-many relationship.
It has all the CRUD management for the two models.

__NOTE:__ This was build during the Academy. If I would build it again, I would do it differently. Also the finishing touches were skipped due to the small amount of time available. 

## Steps I took to make
 1. Create the Rails app
 2. Create the Dinosaur model, some seeds, and minor other things
 3. Build the CRUD management for the Dinosaurs, also some validations
 4. Created the Valley model and added CRUD for them. Also assigned the Dino's to a Valley
 
## Database Structure
  * Dinosaur
    * name:string
    * age:interger
    * image_url:string
    * valley_id:references
  * Valley
    * name:string

## Running Locally
  Make sure you have [Ruby](https://www.ruby-lang.org/en/) and [Bundler](http://bundler.io/) installed.
  Also you will need to have a [Postgresql](https://www.postgresql.org/) server running.
  
  1. `git clone git@github.com:Woulei/valleys-of-dinosaurs.git`
  2. `cd valleys-of-dinosaurs`
  3. `bundle install`
  4. `rails db:create db:migrate db:seed`
  5. `rails server`
  
## Related Documentation
  * [Codaisseur Reader](https://reader.codaisseur.com/courses/beginner-bootcamp-f2b14e3d-8465-426d-9148-58641907bfb0/ruby-on-rails-basics/introduction-to-ruby-on-rails/quiz)
  * [Ruby on Rails](http://rubyonrails.org/)
