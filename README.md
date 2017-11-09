# nike-responsive-design
Here is a conceptional tweak and reimplementation of nike's https://www.nike.com/us/en_us/c/men page. I decided to add bootstrap as a css responsive framework as well as tilt.js and Jquery for some nice card tilting effects. Besides that I tried to keep the library as stripped down of dependacies and tools as possible.

# Structure
There is an ```index.html``` file for the main page. I then have two css pages, one ```main.css``` file, where I set standardized components and HTML dom element rules that all other pages should follow. Specific styles to the page that wouldn't be used I set in ```homepage.css```.

# TODO Work
I tried to timebox the amount of work I spent on the project; I got pretty far, but there is still a lot more that I would like to get done. Here is a list of what needs to be done next:
* Finish Base Styles. As you can see from my implementation there are still mistakes in the base screen implmentation. I need to go through and adjust padding/postioning of text as well as add correct background colors and general DOM structure.
* Fine Tune Bootstrap. Step one was to grab all the componets, images, and text then go through and implement a base html page with all the content. Step 2 was then to go through and add bootstrap to all the components. I did this, but breakpoints, and thresholds are off. You can see the start of a responsive page, but things still aren't perfect. I need to go through and fine tune these breakpoints.
* Add VueJS, Webcomponents, or StencilJs to make more HTML components. Some of these design patterns could easily be made into reusable web components so instead of having to code a slough of HTML for a common pattern all a developer would need to do is just code ```<card></card>```. This makes for simipler to read code as well as is a new common web pattern.
