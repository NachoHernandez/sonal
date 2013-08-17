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

(number)-large
(number)-medium
(number)-small
(number)-nano

All the classes must use an additional class called "column" / "columns".

The grid classes can be also used to add width to additional elements like form fields, images etc (without including "column" or "columns").

Live Demo
=====

http://sadiqevani.com/works/sonal/