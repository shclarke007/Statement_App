# README
  Created an income & expense app that allows upload of income & expense statements via csv or form input

## Known issues  
 - Input form bug
 - UI needs updating
## Getting Started 
  ```
  git clone git@github.com:shclarke007/Statement_App.git  
  cd ie_statement_app  
  bundle install
  ```
  ### Ruby version
  2.7.4
  ### Rails version
  6.1.7.3
  ### System dependencies
  postgres database
  ###  Database creation
  ` rails db:create `
  ### Database initialization
  ` rails db:migrate `  
  ` rails db:seed `
  ### Start App
  `
  rails s -p 3000
  `  
  App available at:  http://localhost:3000/
 ### How to run the test suite
  rspec 
