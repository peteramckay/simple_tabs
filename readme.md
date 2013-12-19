Simple Tabs
===========

This code in this project can be used to set up very basic tabbed navigation for a website with just a few lines of HTML and CSS. (No JavaScript necessary!)

I included a minimal number of CSS properties here, just enough to demonstrate how the navs work. This approach is also intended to keep the code as flexible and customizable as possible for other people's projects as you fork and/or re-use the code, add in other colors, fonts, hover effects, et cetera for different projects.

To add tabbed navigations to your project: 

1- Add the simpletabs.css file to your site server.

2- Add a link to it in the HTML header of any page that you want to include tabbed navigation, like so... 

`<link href="simpletabs.css" rel="stylesheet">`

3- Add an unordered list with the nav elements to the page's HTML as well... 

	<ul class="navbar">
		<a href="tab1.html"><li id="activetab">Tab 1</li></a>
		<a href="tab2.html"><li>Tab 2</li></a>
		<a href="tab3.html"><li>Tab 3</li></a>
		<a href="tab4.html"><li>Tab 4</li></a>
	</ul>

Note the ID attribute "activetab," which is meant to make the tab for the current page differentiated in appearance from the other tabs in the navbar. In the demo files, for instance, the "activetab" is white while the other tabs are a light grey. 

You'll want to make sure the "activetab" ID is used only once the markup for each page of your site. Change the ID's location in the markup as needed to highlight different tabs on different pages. In the demo's html files, for instance, you'll notice that the "activetab" ID is applied to Tab 1 in the tab1.html file, to Tab 2 in the tab2.html file, and so forth.

That's it for now. Always glad to hear any suggestions to improve the Simple Tabs code and/or feedback from anyone who uses the code in a project. Best way to reach me is by email at peteramckay@gmail.com.

Of course, forks and pull requests via GitHub welcome as well. All Simple Tabs code is open source under MIT license.

Cheers,

Peter McKay

