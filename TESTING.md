## Testing

**Issue**       |       **How was the issue fixed** 
----------------|-------------------------------------|
Wireframes unable to load due to incorect code for wireframes and wrong format | Created a new folder in the wireframes called pc. In this folder i had to use Snipping Tool to convert&divide each wireframe individualy into a PNG format from the Balsamiq files and i had to rename each of the wireframe files to come in the appropriate order (1-7). Code unable to load the frames as was missing ! from front of the code and it had wrong file format. [link](/assets/testings/PNG.PNG)
Index.html, css, hover, bootstrap links checked to see if they are functioning | fully functioning [bootstrap test](/assets/testings/links.PNG)
Overall Website performance was at 91% | Hero Img was of a large file. converted the file via TinyPNG and then re-compressed via Compressor.io and set it used it as a pic instead of URL which brought the score between 96%-99%.
Iframe was not working properly due to an error | i posted on slack comunity on /ask-us-anything Eventyret_mentor sugested the URL link is wrong. then i googled how to obtain the correct url link for the google map. [Error link](/assets/testings/error1-iframe.PNG)
Screen reader users rely on frame titles to describe the contents of frames. | added a new title to all .html [Iframe error](/assets/testings/html-iframe.PNG)
lighthouse score for SEO of 92 | added a meta link with name and content to boost search engine maximization.
hero image | the picture size has been compressed several times. each time when lighthouse is run it states that the picture can still be compressed even more. if picture is compresed more it will have a bad quality. issue not fixed
Error 404 | Server error unknown reason unable to resolve [Error link](/assets/testings/server-error.PNG)
Bug 273 | Apearing 4 times unknown reason unable to resolve [Bug 273 link](/assets/testings/bug-273.PNG) 
Bug 86 | Apearing 16 times unknown reason unable to resolve [Bug 86 link](/assets/testings/bug-86.PNG)
Bug 238 | Apearing once unknown reason unable to resolve [Bug 238 link](/assets/testings/bug-238.PNG)
Bug 43 | Apearing 4 times unknown reason unable to resolve [Bug 43 link](/assets/testings/bug-43.PNG)
Bug 27 | Apearing 7 times unknown reason unable to resolve [Bug 27 link](/assets/testings/bug-27.PNG)
Footer | All footers in the html had overflow creating the scroll bar for x axes, resolved by adding a class to each footer and hiden the overflow in css [Footer link](/assets/testings/test1.PNG)
Gallery pictures wont load in Incognito mode or on actual mobile devices | The syntax was entered wrong as **"/assets/"** instead of **"assets/"**. Syntax corrected by removing the / [Gallery Error](/assets/testings/galleryerror.PNG)
Gym music | run the ligh house and was giving me 8 errors. The syntax in gym music was entered wrong in the audio source as **"/assets/"** instead of **"assets/"**. Syntax corrected by removing the /  [Music Error](/assets/testings/syntax-error.PNG)
Join Us | joinus.html scored 92% for accessibility as message "Form elements do not have associated labels" showed up. Fixed by removing the <p> and adding a <label> instead [Accessibility Score](/assets/testings/lighthousejoinus.PNG)








**Html valdiator**  | **How was the issue fixed** 
--------------------|----------------------------|
1. Error: Text not allowed in element iframe in this context.| deleted the <p> element and the context from the iframe.
2. Error: Text not allowed in element iframe in this context. | deleted the <p> element and the context from the iframe.
3. Error: Text not allowed in element iframe in this context. | deleted the <p> element and the context from the iframe.
4. Error: Text not allowed in element iframe in this context. | deleted the <p> element and the context from the iframe.
[Link for the error Description](assets/testings/html-classes.PNG)
5. HTML file checked for error by link | No errors found [Link](assets/testings/htmlvalidator.PNG)


**Web Site Testing results in Lighthouse**  

All the bellow pages have been tested in Incognito mode in Google Chrome.

1.1 Main Home Page [Link](/assets/testings/lighthouseindex.PNG)

1.2 Join Us [Link](/assets/testings/lighthjoinus.PNG)

1.3 Classes Main [Link](/assets/testings/lighthouseclasses.PNG)

1.4 Book your class [Link](/assets/testings/lighthousebookyourclass.PNG)

1.5 Gallery [Link](/assets/testings/lighthousegallery.PNG)

1.6 Why Us [Link](/assets/testings/lighthousewhyus.PNG)

1.7 Gym Music [Link](/assets/testings/lighthousegymmusic.PNG)
