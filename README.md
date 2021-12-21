# Engineering CV/Resume Template
This repository is built for easily constructing a CV or resume by simply adding 
information to the `_data\data.yml` file. The document is hosted online using GitHub 
Pages and Jekyll.

## Customizing the Template
The template is customizable to fit each user's needs. The `_data` folder contains
the content used to populate the CV or resume. In `_data\data.yml`, each field 
corresponds to each section and new entries. To modify the order of each subject 
section, it is necessary to modify the order of the contents of `index.html`, not 
`data.yml`. To change the formatting of each section, modify `assets\css\main.css` 
and the respective section in the `_includes` directory. 

## Jekyll
Jekyll is a tool for generating static webpages hostable on GitHub Pages. This is a template repository to begin creating custom Jekyll templates. To view the modifcations locally, build and run jeykll locally.

### To Run Locally:
1. Install the Ruby development environment
1. Install Jekyll and bundler gems <br>
    `gem install jekyll bundler`
1. Build the site and host it on the local server <br>
    `bundle exec jekyll serve`
1. The site will be hosted on http://localhost:4000

