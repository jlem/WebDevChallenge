# WebDevChallenge
> A hopefully ever-growing list of web-development related challenges
***

## Guidelines for writing challenges
* 1. Don't be too vague, but don't be too specific. Make the challenge itself specific and measurable, but try not to impose a language or framework.
* 2. If you do want to create a framework/language specific challenge, try to focus on challenges that are unique to that framework/language.
* 3. Avoid "learn XYZ" style challenges - focus on challenges that can be DONE or shown in a Git repo.
* 4. Favor challenges that will teach a new, useful skill that is relevant to web development, or skills that teach devs how to solve real web dev problems. The challenge can be a fun, meaningless exercise, but its purpose should be to expose the developer to skills that are applicable to daily web dev tasks.

## Table of contents
1. [Accessibility](#accessibility)
2. [Api](#api)
3. [Auth and Service](#auth-and-sessions)
4. [CMS](#cms)
5. [CSS](#css)
6. [Database](#database)
7. [Environments and Server](#environments-and-servers)
8. [Git](#git)
9. [JavaScript](#javascript)
10. [Misc](#misc)
11. [Mobile/Hybrid](#mobilehybrid)
12. [PHP](#php)
13. [Task Runners](#task-runners)

## Challenges

### Accessibility
- [ ] Use a screen reader to test your pages
    - [ ] [Using NVDA to Evaluate Web Accessibility](http://webaim.org/articles/nvda/)
    - [ ] [Using VoiceOver to Evaluate Web Accessibility](http://webaim.org/articles/voiceover/)

### API
- [ ] Build a REST API for something.
- [ ] Build a SOAP API for something.
- [ ] Add API authentication.
- [ ] Add API request throttling.
- [ ] Add API versioning.
- [ ] Document your API.
- [ ] Display a Facebook feed on a page through its API.
- [ ] Display a Twitter feed on a page through its API.
- [ ] Create a web app that lets authenticated users post tweets to your Twitter account.
- [ ] Build a Reddit bot that follows you around and gives you random compliments when you post.
- [ ] Display LinkedIn work experience on a page through its API.
- [ ] Create a webapp using a weather API and an image API like flickr to display images based on the weather.
- [ ] Use the Spotify API to search for a particular song or artist and create a webpage with details on that particular song/artist.
- [ ] Create a custom-styled map using the Google Maps API

### Auth and Sessions
- [ ] Traditional form-based identifier/password.
- [ ] Traditional form-based Identifier/password w/remember-me feature.
- [ ] Implement JWT auth.
- [ ] SSO.
- [ ] Password-less auth.
- [ ] Auth via social network accounts.
- [ ] Implement an OAuth2 server and a fake service and a fake app to make use of it.
- [ ] Adding user registration.
- [ ] Incorporate email confirmation and forgotten password functionality.

### CMS
- [ ] Set up WordPress and create a custom theme ~ [Developing a WordPress Theme from Scratch](http://www.taniarascia.com/developing-a-wordpress-theme-from-scratch/)
- [ ] Set up Drupal and create a custom theme ~ [Drupal Theming Guide](https://www.drupal.org/documentation/theme)

### CSS
- [ ] Draw Homer Simpson using nothing but CSS.
- [ ] Create a sprite sheet of Simpsons character components and create your own FrankenSimpson from it.
- [ ] Vertically center a div.
- [ ] Create a responsive three column equal height layout divided by 1px borders/dividers.
- [ ] Create a sticky header.
- [ ] Create a sticky footer.
- [ ] Collapse a navigation bar to a hamburger menu when you're using any mobile device ~ [Responsive Dropdown Navigation Bar](http://www.taniarascia.com/responsive-dropdown-navigation-bar/)
- [ ] Create a responsive website by using CSS media queries.
- [ ] Collapse a navigation bar to a hamburger menu when you're using any mobile device ~ [Tutorial](http://www.taniarascia.com/responsive-dropdown-navigation-bar/)
- [ ] Do the same, as the above, but only for the iPhone 6 Plus.
- [ ] Create a basic CSS3 animation which uses opacity, transform and keyframes.
- [ ] Try a preprocessor like LESS, SASS or Stylus.
- [ ] Create a responsive grid with flexbox ~ [Easiest Flex Grid Ever](http://www.taniarascia.com/easiest-flex-grid-ever/)
- [ ] Create a basic website using Bootstrap
- [ ] Create a basic website using Foundation
- [ ] Create a pure CSS parallax scrolling effect

### Database
- [ ] Create a normalized database for storing comments and authors. Using that database, display the comments with authors, without incurring N+1 queries to do it.
- [ ] Create an app that stores users, movies, lets users favorite movies, tag movies with common tags, and tag movies with their own user-created tags.
- [ ] Use the entity-attribute-value pattern to create an app that lets you define and store any arbitrary characteristics about any video game.
- [ ] Replicate Reddit's comment system in as much detail as possible using the adjacency list pattern.
- [ ] Do the above, but with the closure table pattern.
- [ ] Do the above, but with the nested set pattern.
- [ ] Write a SQL query that removes all duplicate records from a table.

### Environments and Servers
- [ ] Create a Vagrant box that would let you host a new Rails site.
- [ ] Create a Vagrant box that would let you host a new WordPress site.
- [ ] Create a Vagrant box that would let you host a new Django site.
- [ ] Set up your own DigitalOcean server and provision it to host one of the three sites above.
- [ ] Set up public/private SSH keys for that server.
- [ ] Set up a local MAMP or WAMP environment ~ [MAMP Tutorial](http://www.taniarascia.com/local-environment/), [WAMP Tutorial](https://www.vultr.com/docs/setup-a-wamp-server-on-windows)
- [ ] Set up virtual hosts so each site can have its own local domain ~ [MAMP Tutorial](http://www.taniarascia.com/setting-up-virtual-hosts/), [WAMP Tutorial](https://john-dugan.com/wamp-vhost-setup/)
<<<<<<< HEAD
- [ ] Create a Bootstrap web application and link it to your server. http://getbootstrap.com/
- [ ] Create a simple Node.js application and host it on your server.
=======
- [ ] Create and run a Docker image that would let you host a Django site.
- [ ] Deploy using a Docker image on services such as DigitalOcean or AWS ECS.
>>>>>>> 2f62dc835ece8f2d193ac0fcb8b185934f9280dd

### Git
- [ ] Set up two different GitHub accounts, and learn how to SSH different projects with different accounts.
- [ ] Use command line to push a Git repository from a local environment to a live server. ~ [Getting Started with Git](http://www.taniarascia.com/getting-started-with-git/)
- [ ] Squash different Git commits together
- [ ] Try creating a pull request on another repository at the command line. You never know what good stuff could happen...

### JavaScript
- [ ] Create an image slider that accepts any number of slides and changes them every 5 seconds.
- [ ] Create a sticky element that doesn't attach to the top of the screen until you scroll to its position.
- [ ] AJAX submit a form, validate it server-side, and display those validation errors.
- [ ] Validate form data on the client-side.
- [ ] Build a date-picker plugin.
- [ ] Create a drag and drop functionality to upload files.
- [ ] Build a tic tac toe game.
- [ ] Build a simple multi-page app using Angular.js.
- [ ] Build a select-box replacement plugin.
- [ ] Build a plugin that provides a popup window functionality.
- [ ] Redo the exercises using jQuery.
- [ ] Create a navigation bar that tracks your scrolling activity and indicates which section of the page you're viewing.

### Misc
- [ ] Build a chrome extension that contains a content script which modifies the Facebook appearance.
- [ ] Build a chrome extension which provides a possibility of adding bookmarks with a form on the newtab page.
- [ ] Build a chrome extension that shows WHOIS information about the domain you're on.
- [ ] Build a scraper that aggregates all the hash tags and their links from Twitter's home page. Hint - requires you to be authenticated.
- [ ] Build a link shortener.
- [ ] Create a link/URL lengthener (making it much longer) with funny/meme/themed words in the URL, ex. Star Wars, Space Jam, etc.
- [ ] Build a simple portfolio website to showcase your work.

### Mobile/Hybrid
- [ ] Create a Ionic project using http://www.ionicframework.com/
- [ ] Build the hybrid app on the Android platform, resulting in a .APK file of your app.
- [ ] Build the hybrid app on the iOS platform, resulting in a .IPA file of your app.

### PHP
- [ ] Try to create a project using Laravel.
- [ ] Create basic login system.
- [ ] Create a custom form validation
- [ ] Create a small custom blog system that contains CRUD operations
- [ ] Implement a templating engine (smarty or twig)

### Task Runners
- [ ] Use Grunt to compile Sass into CSS, minify, and autoprefix. ~ [Getting Started with Grunt and Sass](http://www.taniarascia.com/getting-started-with-grunt-and-sass/)
- [ ] Use Gulp to compile Sass into CSS, minify, and autoprefix. ~ [Gulp for Beginners](https://css-tricks.com/gulp-for-beginners/)
- [ ] Use [npm scripts](http://substack.net/task_automation_with_npm_run) to compile Sass into CSS, minify and autoprefix
- [ ] Setup LiveReload with either Grunt or Grunt.

### Terminal / Shell
- [ ] Write a shell script that copies files from one location to another.
- [ ] Write a shell script that allows you to google a search term from the command line.
- [ ] Write a shell script that prints a unicorn in ASCII characters.
