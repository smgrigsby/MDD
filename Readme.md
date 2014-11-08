Deployment Plan 
======

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
