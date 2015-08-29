# mywebapp


typical architecture:

web-front 
	-fetches data from api and renders html templates
http api
     - fetches data from data store and handles http cashing
data store
     -  constructs DB queries


resources:

Todd McLeod 
pluralsight - creating web application + language resources

best router - Julian Schmidts!

check out webstorm - to create your templates

- project folder structure:
 |
  - bin
  - pkg
  - public
    |_ css
    |_ img
    |_scripts
    |_video
  -src
    |_controllers
    |_converters
    |_main
    |   |_main.go
    |_models
    |_viewmodels
  -templates
    |_home.html

  .gitignore
- external libraries 

- always run main.go  from root of the project

- your GOPATH to contain more than one location seperated by colon (:). location 1 is ...\golib.
go get installs downloads to first location by default

-host on appengine 

- use default mux for now

- use webstorm ide

- Use gitignore to remove videos.

