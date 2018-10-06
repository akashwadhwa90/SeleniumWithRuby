Steps to follow:

Prerequisite: Ruby is installed and set up in your system

1. Install Rubymine IDE – www.jetbrains.com/ruby/download
2. Create a new project -> Select SDK -> C/ruby…/ruby.exe
3. Now open terminal and navigate to the new project directory : cd <directory path>
4. Type command: bundle init --> This will create a gemfile under that project 
The Gemfile will list all the gems we need in order to get our simple cucumber project up and running. Open the gem file with 
your favorite text editor add the following gems :

source 'https://rubygems.org'
 gem 'capybara'
 gem 'cucumber'
 gem 'selenium-webdriver'
 gem 'debase'
 gem 'ruby-debug-ide'
 
 5. The listed gems must now be installed along with their dependencies, close the Gemfile and within the cucumber_project 
 on the command line line run: bundle install
 
Bundler will now install the listed gems

6. Download chromedriver and save it under the project
