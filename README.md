# react-login-backend
React login back-end

### Setup
Tested on:
- Ruby 2.4.1
- Rails 5.1.4

- Install the app dependencies:
`bundle`

- Prepare the database:
`
    bin/rake db:create:all db:migrate
`

- Load static data into database (default user with admin@example.com:password credentials):
`
   bin/rake db:seed
`

- Start the server
`
bin/rails s
`

The project will run at http://localhost:3000
