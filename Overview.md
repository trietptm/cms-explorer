# Overview #


CMS Explorer is designed to reveal the the specific modules, plugins, components and themes that various CMS driven web sites are running.

Additionally, CMS Explorer can be used to aid in security testing. While it performs no direct security checks, the "explore" option can be used to reveal hidden/library files which are not typically accessed by web clients but are nonetheless accessible. This is done by retrieving the module's current source tree and then requesting those file names from the target system. These requests can be sent through a distinct proxy to help "bootstrap" security testing tools like Burp, Paros, Webinspect, etc.

CMS Explorer can also search [OSVDB](http://osvdb.org/) for vulnerabilities with the installed components.

CMS Explorer currently supports module/theme discovery with the following products:

  * Drupal
  * Wordpress
  * Joomla!
  * Mambo

And exploration of the following products:

  * Drupal
  * Wordpress