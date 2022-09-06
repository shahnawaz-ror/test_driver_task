## Live working Demo
https://testdrivertask.herokuapp.com/api-docs/index.html



https://user-images.githubusercontent.com/26624702/188695500-a6322cec-76c6-466b-b60c-ca1f404d976e.mp4



## Install

### Clone the repository

```bash
https://github.com/shahnawaz-ror/test_driver_task.git
cd test_driver_tas

```

### Check your Ruby version

```bash
ruby -v
```

The ouput should start with something like `ruby 3.1.2`

If not, install the right ruby version using rvm (it could take a while):

```bash
rvm install "ruby-3.1.2"
```

### Install dependencies

Using [Bundler](https://github.com/bundler/bundler):

```bash
bundle
```

### Update database.yml file
In database.yml file, edit the database configuration as required.

### Initialize the database

```ruby
rails db:create db:migrate db:seed
```

### Serve

```ruby
rails s
```
And now you can visit the site with the URL http://localhost:3000/api-docs/index.html

### Additonal Info
if you create changes in spec folder
run below command

```bash
rake rswag:specs:swaggerize 
```
**DataBase ERDiagram**
[erd.pdf](https://github.com/shahnawaz-ror/test_driver_task/files/9497744/erd.pdf)
