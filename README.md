# Welcome

This repository contains my solutions to some of the Bark coding challenges. I took on a mixture of the Full Stack and Front End challenges.

I worked on the full stack challenges first to familiarize myself with the Rails stack. Some of that work was later invalidated by the front end work, but it remains in the commit history and the index.html.erb file still contains the commented out template code.

For the front end challenges I included React and Material UI from CDN repositories, allowing me to get them up and running quickly. Because of this I had to code the React scripts directly into the index.html.erb file and there was not a good way to test the components. This is obviously not ideal, but it seemed to be the best way to get React running on the example site in a reasonable timeframe.

# Set up

You'll need [ruby 2.2.4](https://rvm.io/rvm/install) and [rails 5](http://guides.rubyonrails.org/getting_started.html#installing-rails) installed.

Run `bundle install`

Initialize the data with `rake db:reset`

Run the specs with `rspec`

Run the server with `rails s`

View the site at http://localhost:3000
