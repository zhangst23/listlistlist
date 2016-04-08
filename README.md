rails new listlistlist
***
gem 'bootstrap-sass'
gem 'simple_form'

gem 'devise'
gem 'cancancan'
gem weixin/weibo/qq


gem 'carrierwave'
gem 'mini_magick'

gem 'kaminari'

gem 'pry-rails'
***
rails g controller profile 

***
rails g scaffold topic title:string content:text user:references node:references
rails g model Node name:string bio:text topic:references
rails g controller nodes create destroy
***
rails g model comment user:references content:text
rails g controller comments create destroy edit
***
rails g model relationships follower_id:integer followed_id:integer

***
gem 'elasticsearch-model'
gem 'elasticsearch-rails'
***
gem 'grape'
API 设计



以后实现
***
收藏功能
http://liuzxc.github.io/articles/rails-app-study-09/
collection  favorite
***
notifications
https://github.com/rails-engine/notifications
https://www.devwalks.com/lets-build-instagram-part-6-notifications/
















