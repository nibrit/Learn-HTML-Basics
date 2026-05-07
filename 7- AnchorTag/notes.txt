# What is Anchor Tag?
-> Anchor tag is used to create Hyperlinks in HTML.
-> Anchor tag is used to join multiple webpages with the help of Hyperlinks.
-> With the help of Anchor tag we can navigate from one page to another page.
-> Anchor tag is paired tag in HTML.
-> Anchor tag will accept 2 attributes: href and target

# Syntax: <a href="reference/path" target="_self"> Content </a>
Here, 
    href = Hyper reference
    target = It is used to decide where we want to open the reference/path  provided in the href.
    It will accept 4 values -> _self(default), _blank, _top, _parent

    Same tab = _self
    New or Blank tab = _blank

# Appearance of HTML Anchor Tag:
  a. Unvisited Link → Displayed underlined and blue.  
  b. Visited Link → Displayed underlined and purple.  
  c. Active Link → Underlined and red color. 

# How to prevent refresh / reload of a anchor tag:
-> By passing # inside the href.
-> Example = <a href="#"> Content </a>

# Link to same tab:
-> Example = <a href="https://www.google.com/" target="_self"> Visit Google </a>

# Link to new / other tab:
-> Example = <a href="https://www.google.com/" target="_blank"> Visit Google </a>

# How to download source on clicking link (download):
-> The  download attribute specifies that the target (the file specified in the  href attribute) will be downloaded when a user clicks on the hyperlink.
-> Example:  <a href="/assets/devlogo.jpg" download>Download</a>

-> NOTE ⇒ If we do not provide the value for download attribute by default it will take the name of the file name that we have provided in the href attribute as source.
-> Example: <a href="/assets/devlogo.jpg" download="Developer">Download</a>

# How to add Icons in a Webpage:
-> Use the font awesome icon website.
-> Website: https://fontawesome.com/icons
-> Search any icons and make sure use the free one icons, don't use pro icons.
-> After copy pasting the icon tag use the cdn link of font awesome.
-> Search in browser = font awesome cdn link
-> Open the website called as => cdnjs (font-awesome - Libraries)
-> And copy the first Link tag and paste it into the <head> tag of HTML.
-> Below is the link tag of font awesome:


<link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/7.0.1/css/all.min.css" integrity="sha512-2SwdPD6INVrV/lHTZbO2nodKhrnDdJK9/kg2XD1r9uGqPo1cUbujc+IYdlYdEErWNu69gVcYgdxlmVmzTWnetw==" crossorigin="anonymous" referrerpolicy="no-referrer" />
