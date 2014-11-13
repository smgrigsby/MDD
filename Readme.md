Deployment Plan 
======

Release Schedule
------
* 1.0.0 Static Site Design 
	* 1.1.0 
		* Portfolio
		* List of Design Projects
		* List of Development Projects
	* 1.1.1 
		* Basic Styling
		* #nav and #container tags

* 2.0.0 Responsive Design Update
	* 2.1.0
		* Optimize layout for mobile devices
		* move sidebar navigation to footer
	* 2.2.0
		* convert to multi-page layout
			* resume
			* academic projects
			* contact
		* content audit and update
		* optimize images
	* 2.2.1
		* sub-navigation menus

* 3.0.0 Dynamic Features Update
	* 3.1.0 
		* minimize/expand menus
		* photo gallery
	* 3.2.0
		* link to github files
		* insert dynamic examples


Merge Dev Branch into Master
------
* $ git checkout master
* $ git pull github master
	* Resolve any conflicts

Update Files
------
* Test
* Promote to Staging
	* $ git push staging master
* Test Again
	* replicate issue within local dev enviroment
* Promote to Production 
