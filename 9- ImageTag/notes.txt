# What is Image Tag?
-> Image tag is used to provide the images in a webpage or website.
-> Images will play a important role in website to make more attractive.

# Syntax of Image Tag:
    <img src="url/local Path" alt="text" />
    Here,
        src = Source -> You can pass the source of the images
        alt = Alternative Option -> It will only accept a text.

-> By default image will take the original resoultion, if we want to control use the width and height attribute inside the image tag.
-> For Ex: <img src="url" alt="text" width="100" height="100" />

# How to make image as Hyperlink?
-> We can make image as Hyperlink with the help of anchor tag in HTML.
-> Put the image tag inside the anchor tag it will become hyperlink.
-> For Ex:
    <a href="">
        <img src="" alt=""/>
    </a>

# How to download the image by clicking on the image?
-> We can download the image just clicking on the image for that we have to wrap the image tag inside the anchor tag and use the download attribute.
-> For Ex: 
    <a href="local_path_for_image" download="new_fileName">
        <img src="local_path_for_image" alt="" />
    </a>
    Here,
    href = The path passed in the href for download purpose.
    src = The path passed in the src is used to displaying the image on the browser (webpage / website).

# What is Figure and Figcaption in HTML?
-> In HTML, <figure> and <figcaption> are semantic elements used to group media (like images, diagrams) with a descriptive caption. 


1. <figure> -> The <figure> tag as a container for self-contained content. While most commonly used for images (<img>), it can also hold videos, charts, tables, or code blocks.

2. <figcaption> -> The <figcaption> tag defines it as the tag that provides a caption or legend for its parent <figure>. It must be nested inside a <figure> and can be placed as the first or last child.

-> For Ex:
    <figure>
        <img src="mountain.jpg" alt="A snowy mountain peak">
        <figcaption>Figure 1: The summit of Mount Everest at sunrise.</figcaption>
    </figure>
