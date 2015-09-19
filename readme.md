# Project Name
The official site of GuanPlus developed by Concordya INC.

# IE Support
* Basic Function: IE9+;
* Full Experience: IE10+;

# Setup Information (Windows)
* IMPORTANT!!!! Before running npm install to setup all package, you need to perform the following instruction
	1.	Backup existing gulpfile.js and package.json as they contain gulp plugin imagemin which is not compatible with windows OS.
	2. Rename gulpfile-windows.js and package-windows.json to gulpfile.js and package.json respectively.
	3. If you have not install gulp, you need to install gulp by typing the following command:
		'npm install -g gulp'
	4. Run npm install to install all npm plugin
	5. Install bower components: 'bower install'
	6. To run the project: 'gulp' . In the browser navigate to http://localhost:8080/bin

# To build source code for release:
1. Change the style.less

Look for code:
@url: "../src";
@url_img: "../src";

Change to
@url: "..";
@url_img: "..";

2. Run 'Gulp release'


# Main Version
Versions that have important updates are listed.

1. V 1.0.0 Basic Version
2. V 2.0.0 Current Main Version
	* Layout and Design Restructure
	* CSS3 Animation Added In Index Page
	* Click Ripple Effects
3. V 2.0.1
	* Add Microsoft YaHei UI Font for Chrome Browser
	* Slide 3 1600 and 1920 width viewport optimization
	* Footer Friends Block and Footer Main Block Alignment
	* Fixed Footer Friends Block Collapse
	* Regular Content Updates
4. V 2.1.0
	* Hash Router Function Added
	* Layout: Banner Height Extend
	* Regular Content Update

5. v 2.2.0
	* Router Function extended to view change
	* Restructure HTML Orgnization with EJS Template
	* Regular Content Update
6. v 2.2.5
	* Main.JS restructure with OOP;
	* Footer sitemap anchor direction and animation function added
	* .gitignore Modified;
	* Regular Content Update;

# TODOS
1. Protimize Main.JS Espcially The Structure of the Code or Try OOP
2. Portimize Website Loading Efficiency Via
	* CSS Sprites in Index Page
	* Lazy Loading with Reference to Echo.js
3. Try JS Template (DONE)
