# AceBook

[![Build Status](https://travis-ci.org/simone-smith/acebook-off-the-rails.svg?branch=master)](https://travis-ci.org/simone-smith/acebook-off-the-rails)

Acebook is a clone of Facebook built with Ruby on Rails as a group project during weeks 8-9 by team Off The Rails of the May 2018 cohort at Makers Academy.


## Getting Started

To run the app on your machine, download the files, run `bundle install` to install the gems, run `rails db:create`, `rails db:migrate`, fire up the `rails server` and navigate to localhost:3000 in your browser.

It is also deployed to Heroku at https://blooming-meadow-10813.herokuapp.com/.

To run the tests, make sure RSpec is installed (`bundle install`) and run `rspec` from the command line.


## User Stories

Acebook satisfies the following User Stories:

```
As a user
So that I can share my thoughts and feelings with my friends
I can post to AceBook
```

```
As a user
So that I can post to AceBook
I can sign up for an Acebook Account
```

```
As a user
So that I can advise and opine on the posts of others
I can comment on others' posts
```

```
As a user
So that I can express approval of the posts of my friends
I can add likes to the posts of others
```

```
As a user
So that I can make my posts more jolly-looking
I can attach images to my posts
```

```
As a user
So that I can remain abreast of developments in the lives of my friends
I want to be able to friend them online
```

```
As a user
So that my friends can know me better
I can have a user profile page with my photo, bio and posts
```


## Screenshots

Welcome page
![Welcome page](https://github.com/simone-smith/acebook-off-the-rails/blob/finalise_readme/app/assets/images/welcome.png)

Newsfeed
![Newsfeed](https://github.com/simone-smith/acebook-off-the-rails/blob/finalise_readme/app/assets/images/newsfeed.png)

Profile page
![Profile](https://github.com/simone-smith/acebook-off-the-rails/blob/finalise_readme/app/assets/images/profile.png)


## Technologies used

- Ruby 2.5.0
- Rails (5.2.0)
- Rspec-rails (3.5)
- Capybara (2.13)
- PostgreSQL
- Acts As Votable
- Bootstrap / CSS
- Simplecov
- Rubocop
- Travis
- Heroku


## Group workflow

We held stand ups every morning to discuss our achievements and/or blockages from the day before, plans for the day and allocate tickets. We used Trello to track our work and split user stories into smaller tasks, running two day sprints to assess our current progress and evaluate which features to focus on implementing.

All pull requests had to be reviewed and approved by at least two other members of the team before they could be merged into the master.

We worked in pairs, and switched regularly to ensure that everyone had a chance to work across all areas of the codebase.


## Future improvements

Given more time, we would have liked to implement more features, such as groups, albums and chat functionality to our app.

## Contributors

- [Diego Fontecilla](https://github.com/diegofontecilla)
- [Lucia Gore](https://github.com/luciagore)
- [Nick Richardson](https://github.com/n-ckr-ch-rds-n)
- [Simone Smith](https://github.com/simone-smith)
- [Matt Wareing](https://github.com/mdwareing)
