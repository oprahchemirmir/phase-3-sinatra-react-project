# PROJECT MANAGEMENT API
It is a simple web API where you make  calls to a server to organize a project management app.
# built with
-Ruby
-ActiveRecord
-SQLite3
-Rack
# project setup
-git clone this repo 
`git@github.com:oprahchemirmir/phase-3-sinatra-react-project.git`
-Ensure the ruby gems are setup in your machine
`bundle install`  
 -Perform any pending database migrations
`rake db:migrate`
-Run the application
`rake server`
-Open the application from your browser
`http://localhost:9292`
# application
This application is a simple web API that allows users to:
Register a new account.
Log in to existing account.
Create projects
Update projects
View all projects
edits project
Delete a project
# exmples of calls you can make with the api
CREATE projects
DELETE a project
UPDATE a project
# exmple of CREATE projects
`localhost:9292/projects`
{
  "apps": [
    {
      "id": 6,
      "name": "TMA",
      "title": "charity app",
      "description": "people are able to give there donations"
    },
    {
      "id": 7,
      "name": "CCR",
      "title": "weather app",
      "description": "one can be ale to tell the weather"
    },
    {
      "id": 8,
      "name": "PFA",
      "title": "Pet finder app",
      "description": "Pet finder project"
    },
    {
      "id": 9,
      "name": "MFA",
      "title": "Movie finder app",
      "description": "movie app project"
    },
    {
      "id": 10,
      "name": "PMA",
      "title": "Portfolio management app",
      "description": "Portfolio management project"
    }
  ]
}
# LICENSE 
Copyright 2023 Oprah Chemirmir

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the “Software”), 
to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, 
and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED “AS IS”, WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. 
IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.







