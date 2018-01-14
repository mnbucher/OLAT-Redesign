# OLAT Redesign (UZH)

![This is how the new amazing OLAT Redesign will look like on your Browser](https://www.tinystudio.ch/docs/newolat.png)

## Introduction

This project was initially founded due to *incomprehension* about the User Interface of the updated Learning Management System (LMS) developed by the University of Zurich (UZH). 
See [here](https://en.wikipedia.org/wiki/OLAT) for more details about OLAT. The new version of the platform was published over the summer 2016 and not only the new UI is extremely ugly, but there are also some very bad UX practices.

With this in mind, we had the approach to clean up the messy platform to make it a tidier place with a reduced UI. At least we tried to make it a bit sexier. As students, we spend so many hours on this platform (daily). Our approach tries to make it aesthetically more enjoyable.

## Things we changed

* Whole new Login Page with cool hover effect 😎
* Simpler Navigation (We removed some unnecessary elements in the navigation, most of them are also reachable at the sidebar on the right)
* There is a max-width for the whole webapp for better readability and structure
* Changed typeface to System's Font for better readability
  * macOS: San Francisco
  * Android: Roboto
  * Microsoft: Segoe UI
  * Linux: Ubuntu

## Installation

### Step 1:

Get the «Stylish» Add-on for your Browser and install it.

Chrome: https://chrome.google.com/webstore/detail/stylish/fjnbnpbmkenffdnngjfgmeleoegfcffe?hl=de

Safari: http://sobolev.us/stylish/

### Step 2: 

1. Go to the settings of the Add-on (On Safari: Click on the «S» in the menubar and then click on «Manage»)
2. Edit / Write a new style
3. Copy and Paste the following code snippet [HERE](https://raw.githubusercontent.com/mnbucher/olat/master/olatPolishing.scss)
4. Under «Applies to» select «URL» or «URL Prefix» (see below) and type in the following ones:
- (URL) https://www.olat.uzh.ch
- (URL) https://lms.uzh.ch
- (URL) https://lms.uzh.ch/dmz/
- (URL Prefix) https://lms.uzh.ch

YOU'RE DONE! 👍🏼🎉

## License
This project is licensed under the Apache License – see the [LICENSE.md](LICENSE.md) file for details.
