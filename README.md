# README

- created Kitten scaffold model
- added navigation links to views
- seeds items to db and run rails db:seed 
- installed gem 'rest-client'
- bundle install
- open new terminal, run irb
- > require 'rest-client'- should return => true
- > r puts r.body= RestClient.get("http://localhost:3000/kittens", :accept => :json) => <RestClient::Response 200 "[{\"id\":1,\"n...">
- puts r.body
[{"id":1,"name":"Zoyi","age":"7","cuteness":"cute","softness":"soft","created_at":"2021-03-18T20:24:40.798Z","updated_at":"2021-03-18T20:24:40.798Z","url":"http://localhost:3000/kittens/1.json"},{"id":2,"name":"El Kashkudo","age":"1","cuteness":"too cete","softness":"soft","created_at":"2021-03-18T20:33:46.058Z","updated_at":"2021-03-18T20:33:46.058Z","url":"http://localhost:3000/kittens/2.json"},{"id":4,"name":"Adolf","age":"5","cuteness":"1","softness":"8","created_at":"2021-03-18T20:59:26.156Z","updated_at":"2021-03-18T21:00:16.820Z","url":"http://localhost:3000/kittens/4.json"},{"id":5,"name":"Tippy","age":"1","cuteness":"5","softness":"7","created_at":"2021-03-18T20:59:26.266Z","updated_at":"2021-03-18T21:00:38.507Z","url":"http://localhost:3000/kittens/5.json"},{"id":6,"name":"Crufold","age":"7","cuteness":"7","softness":"6","created_at":"2021-03-18T20:59:26.394Z","updated_at":"2021-03-18T21:00:06.113Z","url":"http://localhost:3000/kittens/6.json"},{"id":7,"name":"Hamwee","age":"3","cuteness":"3","softness":"3","created_at":"2021-03-18T20:59:26.526Z","updated_at":"2021-03-18T21:01:27.386Z","url":"http://localhost:3000/kittens/7.json"},{"id":8,"name":"kittenslayer","age":"69","cuteness":"10","softness":"9","created_at":"2021-03-18T20:59:26.636Z","updated_at":"2021-03-18T20:59:26.636Z","url":"http://localhost:3000/kittens/8.json"},{"id":9,"name":"Gandalf","age":"5","cuteness":"1","softness":"8","created_at":"2021-03-18T20:59:26.769Z","updated_at":"2021-03-18T20:59:26.769Z","url":"http://localhost:3000/kittens/9.json"},{"id":10,"name":"Rudolf","age":"1","cuteness":"5","softness":"7","created_at":"2021-03-18T20:59:26.882Z","updated_at":"2021-03-18T20:59:26.882Z","url":"http://localhost:3000/kittens/10.json"},{"id":11,"name":"Rufold","age":"7","cuteness":"7","softness":"6","created_at":"2021-03-18T20:59:27.011Z","updated_at":"2021-03-18T20:59:27.011Z","url":"http://localhost:3000/kittens/11.json"},{"id":12,"name":"Harold","age":"3","cuteness":"3","softness":"3","created_at":"2021-03-18T20:59:27.124Z","updated_at":"2021-03-18T20:59:27.124Z","url":"http://localhost:3000/kittens/12.json"},{"id":13,"name":"Kitten123","age":"69","cuteness":"10","softness":"9","created_at":"2021-03-18T20:59:27.258Z","updated_at":"2021-03-18T21:00:58.067Z","url":"http://localhost:3000/kittens/13.json"}]
=> nil

{"id":1,"name":"Zoyi","age":"7","cuteness":"cute","softness":"soft","created_at":"2021-03-18T20:24:40.798Z","updated_at":"2021-03-18T20:24:40.798Z","url":"http://localhost:3000/kittens/1.json"}

This README would normally document whatever steps are necessary to get the
application up and running.

Things you may want to cover:

* Ruby version

* System dependencies

* Configuration

* Database creation

* Database initialization

* How to run the test suite

* Services (job queues, cache servers, search engines, etc.)

* Deployment instructions

* ...
