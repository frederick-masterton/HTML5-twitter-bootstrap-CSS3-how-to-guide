'''

No frills guide to the twitter bootstrap CSS framework making a responsive webapp.

'''

Prerequisites:
1. Download and extract the twitter bootstrap files,
"bootstrap.zip" from their github :http://twitter.github.io/bootstrap/index.html

2.Place your index.html on the same level as the directories 
extracted from bootstrap.zip.

Ex. 
    Project/

			css/
			
			img/
			
			js/
			
			index.html

Note: Twitter bootstrap is used with HTML5, so you need to have a <!DOCTYPE html> 
tag to activate it in your html file.

Note: I'll be purposely using "#"s in the code to show you what code creates what 
elements in the webpapp and using <!-- --> for comments in the code to narrate what is going on.

Note:
The Twitter Bootstrap uses set of predefined classes for each element in your HTML.
These predefined classes are used on a design area measured by a unit of "spans",
which must 12 "spans" in total.

Ex. I want my Descriptive content and side bar to be share an area. 66% for Content 33% for Sidebar:

<code><div class="container"></code>
   <code><div class="row-fluid">
           <div class="span8">
		     The Main Content (It's 66.6..%) of the area.
            </div>
            <div class="span4">
		      The Side Bar (It's 33.3..%) of the area.
            </div>
        </div>
    </div> </code>


 Here's the layout of the site we're going to be thinking up a pretty generic website frontpage:
 
1.Header - Site's logo image and navigation.

2.Main Splash - Site's jQuery image slider or something eye catching.

3.A side bar - Site may have some kind of new deals, best selling items usually.

4.Footer - Copyright information, follow on social media etc.

5.Descriptive content - Maybe special collections, A sale or an in depth look for a product.

Please see index.html for the code. 

Enjoy!