# OLAT 10.0 (UZH) Polishing

![This is how the new amazing OLAT Redesign will look like on your Browser](https://www.tinystudio.ch/docs/newolat.png)

## Introduction

This project was initially founded due to *incomprehension* about the new User Interface of the updated Learning Management System (LMS) developed by the University of Zurich (UZH). 
See [here](https://en.wikipedia.org/wiki/OLAT) for more details about OLAT. The new version of the platform was published over the summer 2016 and not only the new UI is extremely ugly, but there are also some very bad UX practices.

So with this in mind, we have the approach, to clean up this messy platform to make it a much more asthetic place with less overloaded content and to polish the whole User Interface. As students, we daily spend a lot of time on this platform. So we want to make this thing a more beeautiful place.

## Things we changed

* Whole new Login Page with cool hover effect 😎
* Simpler Navigation (We removed some unnecessary elements in the navigation, most of them are also reachable at the sidebar on the right)
* There is a max-width for the whole webapp for better readability and structure
* Minor UI / Design changes
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

1. Go to the settings of the Add-on (the name of the menu item depends on your Add-on version of Stylish).
2. Edit / write a new style
3. Copy & Paste the following code snippet [HERE](https://raw.githubusercontent.com/mnbucher/olat/master/olatPolishing.scss)
4. under «Applies to» select «URL» or «URL Prefix» (see below) and type in the following ones:
- (URL) https://www.olat.uzh.ch
- (URL) https://lms.uzh.ch
- (URL) https://lms.uzh.ch/dmz/
- (URL Prefix) https://lms.uzh.ch

### Step 3

YOU'RE DONE! 👍🏼🎉

## Contributors

* **Martin Bucher** - *Initial work* - [mnbucher](https://github.com/mnbucher)

See also the list of [contributors](https://github.com/mnbucher/olat/contributors) who participated in this project.

## License
This project is licensed under the Apache License – see the [LICENSE.md](LICENSE.md) file for details.
