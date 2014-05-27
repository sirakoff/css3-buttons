## Flat CSS3 Buttons


Flat buttons built from css3.

#### Default Button

In order to use the default button add the classes `btn` and `default` to any appropriate element

```html
<a href="" class="btn default">Button</a>
<button class="btn default">Button</button>
<input type="submit" class="btn default" value="Submit">
```

#### Colored Buttons
The buttons framework support 20 colors listed at <a href="http://flatuicolors.com/">http://flatuicolors.com/</a>

To use the colored buttons simply add the color name to class 

```html
<a href="#" class="btn turcuoise rd">Turcuoise</a>
<a href="" class="btn emerald">Emerald</a>
<a href="#" class="btn peter_river">Peter River</a>
<a href="#" class="btn amethyst">Amethyst</a>
<a href="#" class="btn wet_asphalt">Wet Asphalt</a>
<a href="#" class="btn green_sea">Green Sea</a>
<a href="#" class="btn nephritis">Nephritis</a>
<a href="#" class="btn belize_hole">Belize Hole</a>
<a href="#" class="btn wisteria">Wisteria</a>
<a href="#" class="btn midnight_blue">Midnight Blue</a>
<a href="#" class="btn sunflower">Sunflower</a>
<a href="#" class="btn carrot">Carrot</a>
<a href="#" class="btn alizarin">Alizarin</a>
<a href="#" class="btn clouds">Clouds</a>
<a href="#" class="btn concrete">Concrete</a>
<a href="#" class="btn orange">Orange</a>
<a href="#" class="btn pumkin">Pumkin</a>
<a href="#" class="btn pomegranate">Pomegranate</a>
<a href="#" class="btn silver">Silver</a>
<a href="#" class="btn asbestos">Asbesto</a>
```

#### Button Sizes

You can use the the classes `lg`, `sm`, `xs` for large,small and extra small respectively
```html
<a href="" class="btn default lg">Button</a>
<a href="" class="btn default sm">Button</a>
<a href="" class="btn default xs">Button</a>
```

#### Round Buttons

For round buttons simply add the class `rd` to the button element
```html
<a href="" class="btn default rd">Button</a>
```

#### 3D Buttons
To use the 3D buttons simply add `-3d` to the button's color class
```html
<a href="#" class="btn turcuoise-3d">Turcuoise</a>
```

#### Icons - Iconic Font by Font Awesome
The buttons framework uses the Font Awesome. To add icons to the button add `<i class="fa fa-icon-name"></i>` Check out a full list of available icons and their class at <a href="http://fontawesome.io/icons/" target="_blank">http://fontawesome.io/icons/</a>

```html
<button class="btn asbestos"><i class="fa fa-icon-name"></i>Button</button>
```

##### Icon position
If you are adding the icon before the button text add class `left` to the i element

```html
<button class="btn asbestos"><i class="fa fa-icon-name left"></i>Button</button>
```

If you are adding the icon after the button text add class `right` to the i element

```html
<button class="btn asbestos">Button<i class="fa fa-icon-name right"></i></button>
```
