# Bothell-Racing-Development
A website for UW Bothell's Formula SAE team. Made by [Abby Hoyt](https://github.com/AbbyHoyt) and [Charlotte Hoyt](https://github.com/CharlotteHoyt). 

<br>

Below are some instructions for anyone who may need to update/maintain the website in the future!

<br>

**Updating Text Content:**
* Go to the `index.html` file. 
* Find the text to update. Just update it (haha). Make sure the text is between opening (`<p>`) and closing (`</p>`) tags. Write between the tags (for example, `<p>Cool stuff here!</p>`, where "Cool stuff here!" is the text that will actually show up.).
* For body text, the `<p>` tag defines paragraph text. For subheaders, we have used the `<h1>` tag.
* The `<br>` tag creates a line break. 
* An `<a>` tag defines a hyperlink. Links have an `href` attribute. This is the link's destination. 

<br>

**Adding a Picture to the Gallery:**
* Add the photo to the `assets` folder. Give it a descriptive name. To name the photos, we have been using PascalCase (capital letters to delineate words), but anything should work. 
* In the `index.html` file, find the `galleryContainer` div (`<div class="galleryContainer"></div>`).
* Copy and paste one of the `img` tag lines. (For example, `<img class="galleryImage" src="assets/ImageName.jpeg" alt="Descriptive alternative text of the image.">`.)
* Change the `src` attribute to the name of the new image path. (Just change `ImageName`, you will still need `assets/` to show that the photo is in the `assets` folder.)
* Write `alt` text for the image. This specifies a descriptive text alternative for the image. This is an important fallback if the image fails to display. It is also necessary to keep the website accessible for those with visual impairments who may be using a screen reader. What you need to do here is write a brief description of the image (provide a text-based equivalent of the information). 

<br>

**Updating Social Media Links or the Sponsorship Form:**
* Social media links are in the `footer` div (`<div class="footer"></div>`).
* Find the link to update and change the `href` attribute (this is the link). You will need to make this change in both the `index.html` file and the `sponsors.html` file.
* To update the embedded sponsorship form, go to the `sponsors.html` file. Find the `embedSection` div (`<div class="embedSection"></div>`).
* In this div, there is an `iframe` with the class attribute called `sponsorForm`. Update the `src` attribute (this is the link to the form to embed). 


