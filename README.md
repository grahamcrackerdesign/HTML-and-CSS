# HTML-and-CSS
My own HTML and CSS

ProVia Site Theme: <br>
CSS I've written to make sure elements on the ProVia site adhere to the design system. I can drop in certain Elementor widgets and by applying a class name (e.g. .provia-new-tabs) and minor configurations, the widget will look the same as every other tabs widget across the site. This method to maintain our design systen was used for popups, tabs, images, horizontal scrolling galleries, buttons, carousels, dialog boxes, links and different "likeable" image collectons (images with a heart icon). It's a little messy and disorganized than I'd like, but I'm the only one accessing this. If we planned on scaling the design system in some way for some reason, some cleanup would be necessary. 

ProVia Mega Menu:<br>
Our mega menu was very heavy and took a serious toll on the sites performance. We used a Crocoblock plugin called JetMenu that enabled us to basically use a whole Elementor section/page as a mega menu. We have 5 product lines and had a mega menu section for each. Within each section I had a collection of multiple widgets. Realizing the toll all of these widgets and scripts were taking on the website, and not wanting to forsake the design, I took it upon myself to custom code the mega menu and compromised to have each menu triggered on hover instead of click. The result increased page speed by 1-3 seconds on average. 

ProVia Mobile Menu:<br>
This code was based on the markup of the current mobile menu, which used a plugin called JetMenu. The design is a nested multi-page style menu with numerous internal submenus, where clicking on the parent link, then takes you to a screen with a submenu, and so on. At the advice of our development partners I looked through a list of mobile menu's I thought could mimick what we have now and landed on <a href="https://www.jqueryscript.net/demo/Multi-Level-Sidebar-Menu-HC-MobileNav/">this example</a>. This is currently under development with our current development partners and is about 90% complete. 
