Sublime Text 2 Snippets - Selenium (Python bindings) 
====================================================

ST2 snippets for the [Selenium WebDriver](http://seleniumhq.org/docs/03_webdriver.jsp) Python bindings.

Install
-------
Copy the files to your Packages directory.

### Mac OS X
    git clone git://github.com/sloria/sublime-selenium-snippets.git ~/Library/Application\ Support/Sublime\ Text\ 2/Packages/Selenium/snippets

### Windows
    git clone git://github.com/sloria/sublime-selenium-snippets.git %userprofile%\AppData\Roaming\Sublime Text 2\Packages\Selenium\snippets



Examples
--------
`sel:css` expands to `self.driver.find_element_by_css_selector("selector")`
`sel:plinks` expands to `self.driver.find_elements_by_partial_link_text("link_text")

