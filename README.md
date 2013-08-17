(Per)sonal CSS Grid System
=====

## Description

(Per)sonal Grid System. An OOCSS Grid/Framework with Fixed, Fixed-Fluid and Fluid Layout.

(Per)sonal grid system is a simple css grid system which may or may not convert it a full stack framework, at the moment its in alpha version and its not meant for production sites, but you can use the piece of codes at your liking.


Code & Examples
=====

#### Containers

(Per)sonal has 3 main containers (classes):

- fixed - The fixed class has a 960px width and all the columns inside this class are pixel based width.

```HTML
<div class="fixed">
	<div class="row">
	</div>
</div>
```

- fixed-fluid - This class has a max-width and its also fluid all the columns inside this class are percengage based width.

```HTML
<div class="fixed-fluid">
	<div class="row">
	</div>
</div>
```

- fluid - This class has a 90% width and whatever the screen size is the width of this class will expand on 90% of the width of the screen, and all the columns inside this classes use percenage based width.

```HTML
<div class="fluid">
	<div class="row">
	</div>
</div>
```

#### Grid Columns

(Per)sonal has 4 main grid column classes which will help you to be more flexible on the way you want to re-order your website in PC Screens, Tablet Screens, Smartphone screens and Shitty Smartphone screens.

The classes are:

- (number)-large
- (number)-medium
- (number)-small
- (number)-nano

All the classes must use an additional class called "column" / "columns".

The grid classes can be also used to add width to additional elements like form fields, images etc (without including "column" or "columns").

#### Pull/Push and Offset Classes

The following classes move the grid system left to right and right to left by using positions and margins:

- push-(number)
- pull-(number)
- offset-(number)

(Replace the number with a keyword number from one to twelve.)

#### Additional Classes

Some additional classes which you can use are:

- centered (This class will center any grid to the middle)
- left (This class will align everything left)
- right (This class will align everything right)
- text-left (This class will align text left)
- text-right This class will align text right)
- text-center (This class will align text center)
- text-justify (This class will justify text)
- fluidimg (This class will set the max-width of the image to 100% so it will be fluid for responsive design)

##### Code Examples:

```HTML
<div class="fixed">
	<div class="row">
		<div class="twelve-large columns">
		</div>
	</div>
</div>
```

```HTML
<div class="fixed">
	<div class="row">
		<div class="six-large columns centered">
		</div>
	</div>
</div>
```

```HTML
<div class="fixed-fluid">
	<div class="row">
		<div class="six-large push-four columns">
		</div>
	</div>
</div>
```

```HTML
<div class="fluid">
	<div class="row">
		<div class="six-large pull-four columns">
		</div>
	</div>
</div>
```

```HTML
<div class="fixed">
	<div class="row">
		<div class="six-large offset-four columns">
		</div>
	</div>
</div>
```

Live Demo
=====

http://sadiqevani.com/works/sonal/