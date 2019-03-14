# iop-5xx
WEB-240-3241-SP-2019 Responsive Design inside out project iop-5xx
 https://mrdbachl.github.io/iop-5xx/
 
 Preparing project for development
 - added html5 boilerplate _v6.1.0 files to application
 - added Google analytics code
 - Pushed and tested on production server
 
 Iop 5xx - | Step-500.0 | Branch 500-0
 - added starter template to begin our project
 - pulled template from https://startbootstrap.com/template-overviews/scrolling-nav/
 
Iop 5xx - | Step 501-0 | Branch 501-0
- Update title in head to: welcome to me | Chris Rickenbach
- change header bg class from primary to secondary
- add image to header: http://via.placeholder.com/150x150
	- alt should be full name
- update h1 in header to Chris Rickenbach
- update tagline in header to: "Don't declare your interest, show it."
- removed the services section and it's corresponding navigation link
- updated the h2 for about to: Who I am...
- updated the h2 for contact to: Contact me. 
- added the following sections and their corresponding navigation links
	- Experience
		- h2: What I have done...
		- content: Experience: Lorem Ipsum stock writing
	- Education
		- h2: What I have learned...
		- content: Experience: Lorem Ipsum stock writing
	- Skills
		- h2: What I can do...
		- content: Experience: Lorem Ipsum stock writing
	- Interests
		- h2: What inspires me...
		- content: Experience: Lorem Ipsum stock writing
	- Awards
		- h2: What makes me proud...
		- content: Experience: Lorem Ipsum stock writing
		
Iop 5xx - Step 502 | Iop-me updates
me WP Site Changes
	- updated WP bootstrap 4 starter theme
		- Version: 3.0.11
		- By afterimage designs
	- added the following pages to the me wp site
	- welcome to me (nested the following pages below this one)
		- home
			- copied content from header into this page
		- about, experience, education, skills, interests, awards, contact
			- copied content for each of the pages from the static site
				- "<p>-from me</p>" added to each page to allow for easy validation of successful
			- no content added to the "welcome to me" page - used as parent for API calls
	
		
Iop 5xx - | Step 502-0 | Branch 502-0
	README.md file changes
		- prepended the title to the production site link
		- added link to GitHub Pages to the top of the content
	- index.html
		- code changes https://www.diffchecker.com/TIzg6HtF
			- code compare shows many changes because of nesting code inside main element
		- removed comments and cleaned code
		- added main element and nested all section elements inside of it
		- added link to fontawesome to bottom of body for cog in splash screen
		- added link to app.js to bottom of body created in this step
	-app.js
		- created in this step
		- code changes https://www.diffchecker.com/44lvfHq9
		- Updated size of fontawesome gear from 1x to 4x
		- updated top-padding from 12% to 21%
		- updaded font size to 90%