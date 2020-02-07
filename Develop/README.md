# 01 HTML CSS Git: Code Refactor

This project was based on the implementation of HTML5 semantic tags, cleaning up the HTML & CSS code, adding accessibility through <alt> tags, movement from links in <nav> to their corresponding <id>s.

Switching over to HTML5 was a simple task, once you understood the point of refracting. HTML5 semantic tags are the industry standard in naming tags to make elements easily identifiable. They make it easier for other web developers to look into your code and be able to find exactly what they are looking for. Rather than having a <div id=”that-one-vague-part”> or <div id=”system-only-you-know”>, you can make the tag <section> so colleagues will know relatively what part is affected by the tag. By adding these into the Horiseon page, it allows for other developers to work with the site immediately without having to decipher your personal <id>s. 

I also cleaned up the HTML and CSS files by going through and removing repetitive <div id> s. This makes working with the elements much more intuitive. Starting all your CSS in one place allows quick transitions to new styles and makes understandable changes to specific elements when branching off into a specific <id> or element. HTML5 tags combined with cleaning unnecessarily cluttered CSS will make the lives of your fellow peers so much better.

The accessibility aspect was a bit confusing to start, as I believed the point was to make the site W3c compliant. I added descriptions of the images in the <alt> as if it were being read aloud by a screen reader. While I am glad I now understand the capabilities of screen readers (regardless of how obnoxious the robotic voice was for the mere few hours I worked with it), the SEO side of the <alt> tag descriptions is also important. On top of adding <alt> tag descriptions to all the images, I also converted the .hero background-image in CSS into an <img> tag on HTML in order to add an accessible <alt> tag description. This makes our Horiseon site appear closer to the top of searches in digital media/marketing, thus potentially increasing traffic and, eventually, revenue for our client.

Finally, I correctly linked the <nav> bar at the top of the Horiseon site to the corresponding <id>s further down. I did this through the initial <a href=”#X”> elements on the <nav> bar and adding <h2 id=”X”> tags further down where I wished for the user to end up upon clicking the links. This was to improve the basic UX/UI (user experience / interface) by routing around having to scroll down to different sections of the website.

Overall - I found this project easy and basic, but I believe that is kind of the point. Converting <div> to HTML5, creating a usable <nav> bar, and adding <alt> tag descriptions to improve SEO visibility are all aspects of web development we will need to know how to do seamlessly once we move into our new (or improve our current) careers. 





