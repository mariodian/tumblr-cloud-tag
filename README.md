TumblrCloudTag is a simple plugin that let's you retrieve all tags from your blog and display it in a list. 

It has no external dependencies other than jQuery.

##How to Use##

Include css inside a head element:

    <link rel="stylesheet" href="jquery.tumblr.cloud-tag.css">

Include javascript inside a head element:

    <script src="jquery.tumblr.cloud-tag.js"></script>

Load the plugin:
    
    <script>
    $(document).ready(function(){
	    $('#cloud-tag').cloudTag({
		    apiKey: 'your-api-key',
		    tumblrSite: 'your-blog.tumblr.com',
	    });
    });
    </script>
    
Add little bit of html where tags would be inserted:

    <ul id="cloud-tag"></ul>
    
##Parameters##
**apiKey** - your tumblr API key that you need to [register](http://www.tumblr.com/oauth/apps)

**tumblrSite** - link to your tumblr site e.g. mariodian.tumblr.com

**sortBy** (count | alpha) - sort the list of tags by number of occurance or alphabeticaly

**showCount** (true | false) - show a number of each tags used in posts

**countDelimeterLeft** - left delimeter for a number of tags

**countDelimeterRight** - right delimeter for a number of tags
