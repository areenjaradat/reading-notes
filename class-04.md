# Reading of today

# HTML

#### What if you want to add a link to your web page and how you can add it by html

##### lets learn now how to add links

Links are created using the < a > element. Users can click on anything
between the opening < a > tag and the closing < /a > tag.

![link](images04/link.png)

you put the link you want it in the href and when you click the it the website will appear. 
it is will appear like this in your page:

![link1](images04/link1.png)

#### you can to lonk your pages in your website by relative urls and it's a shorthand way of telling the browser where to find your files.

![rel-link](images04/rel-link.png)

lets say you have these folders

so the examplearts folder it the parent of:
* images
* movies
* music
* theater 

and they are a child of examplearts folder
the examplearts folder grandparent of dvd folder

now how to link them in the webpage
lets assume we are in reviews.html how to link same page < a href="reviews.html">Review< /a >

now add child folder < a href="music/listings html">Listings< /a>
 now add Grandchild Folder < a href="movies/dvd/reviews.html">

 now add Parent Folder < a href="../index.html">Home< /a>

 finally add GrandParent Folder < a href="../../index.html">Home< /a>

 you can to link mail by add email to href

 ##### if you want make the link open in new tab you can add attribute  target:"_blank"


 #### Do youthink you can move to top page or bottom page 

 yes you can 

 by add id to the tag you want then link whenever you want <a href="#add thte id here">