![Tiles](http://jambler.se/demos/tiles/tiles_img.png)

## What's this?
Tiles is a CSS3 animation library that makes it really easy to attach animation to document object models.
## Usage
To use this library simply put the following snippet within the `<head>` tag of your html document:
```html
<link href="https://rawgithub.com/victoralveflo/tiles/master/tiles.css" 
  rel="stylesheet" 
  media="screen">
```
## API
#### "Document load" functionality
`.bounceIn` - Performs a bouncing effect on the parent element
#### Hover functionality
`.scale-dec` - Decreasing the size of the parent element

`.scale-inc` - Increasing the size of the parent element

`.rotate` - Rotates the parent element by 90 degrees

`.fade` - Fades out the parent element

`.highlight` - Inverts all colors in the parent element
#### Other
`.tile` - A basic tile element

## Example
Check out the example live [here](http://jambler.se/demos/tiles/)!
```html
<!DOCTYPE html>
<html>
	<head>
		<link href="https://rawgithub.com/victoralveflo/tiles/master/tiles.css" 
			rel="stylesheet" 
	  		media="screen">
	  	<style>
	  		body {
			  background-color: #fff;
			}

			#container {
				height: auto;
				width: 315px;
				margin-left:auto;
				margin-right: auto;
				margin-top: 100px;
			}

	  	</style>
	</head>
	<body>
		<div id="container">
			<center>
		  	  <img src="tiles_img.png" class="bounceIn"><br>
			  <button class="tile scale-dec">			scale decrease</button>
			  <button class="tile scale-inc">			scale increase</button>
			  <button class="tile rotate">				rotate</button>
			  <button class="tile fade">				fade</button>
			  <button class="tile bounceIn scale-dec">	bounce in + scale</button>
			  <button class="tile highlight">			highlight</button>
			</center>
		</div>
	</body>
</html>
```
