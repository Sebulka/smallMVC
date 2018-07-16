# smallMVC
Advertising websites mvc.
	Hellow,


   Basically, this is small MVC for simply advertising websites.
 Do not have data base connections.
 .htaccess is prepared for SSL certificated pages.
 
   It is free licence to use as you want.

   How to use it.
First you have to change few thigs:
everywhere where is -- something -- , you have to deleted all-- -- and what is between, 
and replace with your code.

-sMVC
	change name of this directory as you like, pageName/companyName as you will use in htaccess in line 7

- sMVC/Main.htaccess, 
	line 5 --domainName--
	line 5 --TLD(after dot secondPartDomainName)--
	line 6 --full domainName--
	line 7 -- pageName/companyName --

- sMVC/main/attached/footer.php
 	line 1 place in div your footer content
	this code will be displayed on any page 

- sMVC/main/attached/header.php
	line 12 place your code for header content, like navbar
	this code will be displayed on any page 

- sMVC/main/attached/css/style.css
	prepared for your css styling, place your code

- sMVC/main/attached/css/style.js
	prepared for your js styling, place your code

- sMVC/main/attached/img
	directory for graphics, you can add name of image to data, 
	echo out IMGROOT.$data['imgName'] and it will display image 	

- sMVC/main/attached/libraries
	all ready aded fontAwesome https://fontawesome.com/ and, 
	vivify css for animations https://github.com/Martz90/vivify
	space for your libraries,

- sMVC/main/controllers/Page.php
	create function/method named same as page you want to display
	take home() as example, below is your template, remove comments tags /**/,
	and make many function as you want have a pages.

- sMVC/main/library/Initiate.php
	line 3 --your server url root--
	line 3 -- pageName/companyName --

- sMVC/main/views/home.php
	line 1 clear all and add your code

- sMVC/main/views/
	add many pages as you like, remember to create functions/methods for them
	in sMVC/main/controllers/Page.php
