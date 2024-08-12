# Lab 2

## Create your first ruby and rails application

In this evaluation, you will be asked to create a simple web application using Ruby on Rails. The application will be a simple blog app, with name `Writer`.

## Instructions

### Creation new Rails Application

Create a new Rails application with postgres and boostrap called `writter`:

``` bash
rails new writter --database postgresql -j esbuild --css bootstrap
```

Now you need create a database for the application:

``` bash
rails db:create
```

Next step check if the application is running:

``` bash
rails server
```

## Requirements

* Create landing page using bootstrap with the following elements:
  * Navigation bar with the following functional links:
    * Home
    * About
    * Contact
  * Home page with the following elements:
    * Title
    * Subtitle
  * About page with the following elements:
    * Title
    * Subtitle
    * Description
  * Footer with the following elements:
    * Copyrigth
    * Social media links (not functional)

* Create 3 routes for the following pages:
  * Home -> /
  * About -> /about
  * Contact -> /contact

* Important if elements is common to all pages, you should create in layout file.
* The application should have bootstrap design.

### Submission

#### 1. Create a repository

Create a new repository public in your github account called `lab-2`

#### 2. Upload the code

Upload the code to the repository created in the previous step. follow the instructions below:

#### 3. Submit the repository link

Upload the repository link to Canvas.
