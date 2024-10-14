# My First Rails App

This repository contains my first Ruby on Rails web application, created as part of The Odin Project: [Your first Rails app](https://www.theodinproject.com/lessons/ruby-on-rails-installing-rails#your-first-rails-app)

## Project Overview

This project serves as a foundational introduction to building applications with Ruby on Rails. The main objective is to familiarize yourself with Rails conventions, scaffolding, and basic CRUD (Create, Read, Update, Delete) operations.

### Ruby Version

This application is built using Ruby version **3.3.4**. Ensure you have the correct version installed.

## System Dependencies

- **Ruby**: 3.3.4
- **Rails**: 7.x.x
- **Yarn**: JavaScript package manager (installed via npm)

## Configuration

1. **Install Rails**:
   ```bash
   gem install rails
   ```

   Verify installation:
   ```bash
   rails -v
   ```

2. **Install Yarn via npm**:
   ```bash
   npm install --global yarn
   ```

## Database Setup

The setup includes creating the Rails application, generating a scaffold for `Car`, and migrating the database.

```bash
rails generate scaffold car make:string model:string year:integer
```

```bash
rails db:migrate
```

## Start up the app

Now that you have created a Rails application, you can start it up and see if it works!

```bash
rails server
```
Now, open a browser and visit http://localhost:3000/cars to see your application!

## Summary

This project marks the beginning of my journey in Ruby on Rails, equipping me with essential skills for web application development and laying the groundwork for future projects.
