# FlexNav

### [Check out the demo](http://flexnav.bitballoon.com/)

## What is it?
FlexNav is a fixed responsive navbar made with flexbox. Its purpose is to be easy to add to your site, simply by copying the css file and the html navigation. I created this navbar for my own use so that I didn't have to go through the pain of making a new responsive navbar for every site.

## How do I use it?
It's really simple to get started, all you need to do is to copy the **flexnav.css** file and put it into your own site. After that you copy this HTML:
```
<div id="nav-background">
  <div id="nav-container">
    <header id="nav-header">
      <h1><a href="#" id="nav-logo">FlexNav</a></h1>
      <div id="nav-menu-button">MENU</div>
    </header>
    <nav>
      <ul class="nav-ul hide-ul">
        <li><a class="nav-link active-link" href="#">Home</a></li>
        <li><a class="nav-link" href="#">News</a></li>
        <li><a class="nav-link" href="#">Contact</a></li>
        <li><a class="nav-link" href="#">About</a></li>
      </ul>
    </nav>
  </div>
</div>
```
and put it at the top of your body section.

## How does it work?
The navigation is based on a few different layers.

#### nav-background
This is the white background of the nav that spans across the whole width of the page. It encapsulates the whole navigation.

#### nav-container
I use this part to switch between ```column``` and ```row``` when displaying the navbar on different screen sizes. Column for mobiles, row for desktops.

#### nav-header
This is where the logo (right now it's just text) is located.

#### nav-ul and hide-ul
```nav-ul``` adds styling to the navigation items while ```hide-ul``` toggles the mobile menu on and off if you click the menu button.

## What will change?
This navigation is a work in progress. It is not well documented yet and there's still a lot of stuff to iron out. I still haven't done much testing of how it actually works when implementing it on a variety of sites, so use with caution. My plan is to keep making it more stable and efficient until it will be an eady Plug & Play menu usable on all sites.