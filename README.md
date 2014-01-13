(Per)sonal CSS Grid System
=====

## Description

(Per)sonal Grid System. An OOCSS Grid/Framework to build responvie web apps and websites.

(Per)sonal grid system is a simple css grid system which is slowly converting into a full stack framework, at the moment its in beta version and you may use it at your own discretion.

#### Grid Demo

http://sadiqevani.com/works/sonal/
http://sadiqevani.com/works/sonal/typography.html
http://sadiqevani.com/works/sonal/buttons.html
http://sadiqevani.com/works/sonal/forms.html

Code & Examples
=====

#### Containers

(Per)sonal has 3 main containers (classes):

- fixed - The fixed class has a 960px width.

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

PS:(Replace the number with a keyword number from one to twelve.)

All the classes must use an additional class called "column" / "columns", i have implemented it this way since i tend to use the classes as a width container, and set this classes on objects i want to give a specific width.

The grid classes can be also used to add width to additional elements like form fields, images etc (without including "column" or "columns").

#### Pull, Push and Offset Classes

The following classes move the grid system left to right and right to left by using positions and margins, so in this way you can reorder the grids the way you like:

- push-(number)
- pull-(number)
- offset-(number)

PS:(Replace the number with a keyword number from one to twelve.)

#### Button Classes

Sonal has 7 types of buttons, which can all be used on 3 type of sizes overall and with 4 different colors.

- Buttons classes may be used on button elements, input[type=button] elements and on link(a=href) elements:
```HTML
<button class="default"></button>
<button class="default red"></button>
<button class="default red small"></button>

<input type="submit" class="default" />
<input type="submit" class="default red" />
<input type="submit" class="default red small" />

<a href="#" class="default" ></a>
<a href="#" class="default red" ></a>
<a href="#" class="default red small" ></a>
```

#### Button Classes List

- default
- basic
- square
- minimal
- depth
- glass
- plastic

#### Button Colors Class List

- red
- blue
- green
- yellow

#### Button Size Class list

- small
- large

#### Helper Classes

Some additional classes which you can use are:

- centered (This class will center any grid to the middle)
- align-left (This class will align everything left)
- align-right (This class will align everything right)
- text-left (This class will align text left)
- text-right This class will align text right)
- text-center (This class will align text center)
- text-justify (This class will justify text)
- text-overline (This class will overline a text block)
- text-deleted (This class will put a middle line on the text, as it is deleted)
- text-underline (This class will underline a text)
- fluidimg (This class will set the max-width of the image to 100% so it will be fluid for responsive design)

# Code Examples:

### Container examples

```HTML
<div class="fixed">
	<div class="row">
		<div class="twelve-large columns">
		</div>
	</div>
</div>
```

```HTML
<div class="fixed-fluid">
	<div class="row">
		<div class="twelve-large columns">
		</div>
	</div>
</div>
```

```HTML
<div class="fluid">
	<div class="row">
		<div class="twelve-large columns">
		</div>
	</div>
</div>
```

### Grid Classes

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
		<div class="twelve-medium twelve-large columns">
		</div>
	</div>
</div>
```

```HTML
<div class="fixed">
	<div class="row">
		<div class="twelve-small twelve-medium twelve-large columns">
		</div>
	</div>
</div>
```

```HTML
<div class="fixed">
	<div class="row">
		<div class="twelve-nano twelve-small twelve-medium twelve-large columns">
		</div>
	</div>
</div>
```

### Push, Pull and Offset Classes

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
		<div class="six-large pull-four columns right">
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

### Additional Classes

```HTML
<div class="fixed">
	<div class="row">
		<div class="six-large columns centered">
		</div>
	</div>
</div>
```