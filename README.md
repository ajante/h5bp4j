H5BP4J
======
H5BP4J is a basic Joomla responsive template, based on excellent [HTML5 Boilerplate 3.0](http://html5boilerplate.com), and should be treated as a starting point for someone who knows CSS, HTML and a little bit of PHP and wants to create his own template.

Features
--------
* media queries in template.css for responsive design
* minimum number of CSS files for quick loading (only style.css and template.css)
* template parameters (more information ...)
    * site name or logo, tagline
    * viewport definition
    * Javascript library selection (jQuery, Mootools, none)
    * enable Modernizr
    * Google Analytics ID and recordOutboundLink function
    * hide iPhone adress bar
* Apple-touch-icon files from H5BP 2.0
* error.php for styling error messages
* html/modules.php for custom module titles

More information about the parameters: [H5BP4J description]  (http://www.bestjoomlahosting.com/extensions/32-h5bp4j-joomla-responsive-template-based-on-html5-boilerplate)

Layout
------
Template layout is based on horizontal header (with topmenu), content area (with breadcrumbs, left, main and right columns), bottom and footer, and is using `<div id="header">` rather than `<header>` tags.

For compatibility with the default Joomla template (Beez) modules named "position-xx" are included, e.g.:
    <div id="left">
        <jdoc:include type="modules" name="left" style="xhtml"/>
        <jdoc:include type="modules" name="position-4" style="xhtml"/>
        <jdoc:include type="modules" name="position-7" style="xhtml"/>
        <jdoc:include type="modules" name="position-5" style="xhtml"/>
    </div>

