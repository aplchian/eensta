## Introduction

Eensta is a tiny jQuery plugin that let's you fetch & display images from your Instagram account.

## Instructions


## Demo
http://theportraitofageek.com/eensta/


Add jQuery and the plugin in your page
```
<script src="jquery.js"></script>
<script src="jquery.eensta.js"></script>
```

Add a UL tag somewhere in your page (You can set your own ID or Class)
```
<ul id="eensta-feed"></ul>
```

Initialize it like this
```
<script>
$("#eensta-feed").eensta(
  username : "your_username",
  client_id: "your_client_id",
  how_many : 5 
  linkable: true
</script>
```

## Settings

#### username
No need to explain anything. Just use your Instagram username

#### client_id
You need to create an [Instagram application](http://instagram.com/developer/#) and grab the client ID.

#### how_many
**Default: 5**. The number of images that you want to display on your website

#### linkable
**Default: true**. Disable linking to your images by setting this to false

## Notes
Eensta won't load any inline styles or CSS files and will just produce a plain UL with your Instagram images.
