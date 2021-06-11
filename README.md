# ParsingHTML 1
This is a draft library project for parsing html pages/sites. In the context of the project, it is important to combine PHP language facilities (DOM, CURL) with external parsing libraries. Define a single user interface - generalizing the methods of various components. At the same time, preserve the ability to flexibly configure such functions. Also, on this basis, create the Functionality of highly customizable data analysis filters.
## Software release life cycle 2
- Formation of a general view of the project
 - What functionality should the library support?
 - What features will be used from the PHP core and which ones require third-party components? 
 - What design patterns are appropriate for this component? 
 - Do you need to change the php.ini config file?
 - Should I provide for changing the php.ini configuration file in separate scripts/settings?
- Implementation of preparatory measures
 - Test internal PHP classes / functions for DOM parsing.
 - Test third-party DOM parsing components. 
 - Create to UML diagram.
 - Test design patterns that combine different functions.
 - Define a pool of custom settings filters.
  - Analysis of page/site data for certain categories, topics.
  - Unloading of individual elements, blocks.
  - Сonnecting / disconnecting additional methods for successful returning of elements.
  - Configuring proxy server feed.
  - View of user dashboard.