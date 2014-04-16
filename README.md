# DOCUMENTATION FOR ACDIS  WEBSITE WITH MODX
Hey, I'm Peixian Wang, student developer for spring 2014. The ACDIS website is a dynamically generated website with ModX as the backend, and there was absolutely no documentation for the website when I came in, so I decided to write one. In theory, this should always be on my [github account](https://github.com/6210xi/acdis_documentation), with git source control. However, this might may not hold in the future, so I'll leave a copy of this inside the server. If you're approaching this with a scorched earth tactic, don't worry about this and wipe the content. 

### How this is organized
I won't go into detail about how to use modx, you can find that information on the [modx site](http://rtfm.modx.com/). I will however, go into detail on individual changes I've made and things that you might need to use. 

###modX basics
ModX is organzized into various parts, with content in the left pane (I'll call it a "gutter"), a top navigation, and a main window. Here's an image of what I'm talking about (complete with terrible photoshopping): 
![Modxmain](images/modxmain.png)
#### Gutter
The Gutter is where the actual content on the site resides, as in the child pages and parent pages. A child page is simply a page underneath the parent page. Think of it like the parent is the topic, and the child is the details. After you click on a page, it'll change the main window to the details view. You can use the Edit button to change the contents of the page. ![Gutter](images/gutter_edit.png)
Note that you should <i>NOT</i> be using the source to edit pages! Instead go into edit mode and change the source from there. 
#### Editing
Hit the edit button, and you'll see this brought up: ![Edit](images/edit.png)
You have your standard WYSIWYG editor, with changing it into HTML if you need.
The stuff at the top is the metadata for the page, most pages have a URL alias, which is simply what the URL is. 
![Metadata](images/metadata.png)
For example, the about ACDIS page has the URL alias, which means that the url for the webpage is going to be acdis.illinois.edu/aboutacdis.html If you changed the URL alias to "nginx4lyfe", the URL will be acdis.illinois.edu/nginx4lyfe.html
Uses temple will let you change the template of the page, change it according to what the content is. 
Everything else doesn't have that many use cases, but you can hover over the small dialog icon to find out more. 