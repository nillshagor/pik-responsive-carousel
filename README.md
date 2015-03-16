# pik-responsive-carousel
Pik is a responsive slider which you included on your template. It is totaly responsive and all major browser support.
[Demo](http://nillshagor.github.io/pik-responsive-carousel/).

# uses


	<div class="pik-carousel">
		<div class="pik-carousel-wrapper">
			<ul class="pik-carousel-container">
	
				<li>
					<img src="" alt="" />
					<div class="sc-content">
						<h2></h2>
					</div>
					<div class="sc-author">
						<h2></h2>
					</div>	
				</li>
	
			</ul>
		</div>
	</div>
		
# Configuration
	<link href="css/tooltip_skin_variation.css" type="text/css" rel="stylesheet" />
      	<script type="text/javascript" src="js/jquery.pik.carousel-1.0.2.js"></script>

	Then - 
	<script type="text/javascript">
	      $(function() {
	      	$('.pik-carousel').carousel({
	      		itemWidth: 260,
	      		itemHeight: 260,
	      		distance: 12,
	      		selectedItemDistance: 75,
	      		selectedItemZoomFactor: 0.6,
	      		unselectedItemZoomFactor: 0.3,
	      		unselectedItemAlpha: 0.6,
	      		motionStartDistance: 210,
	      		topMargin: 115,
	      		selectByClick: true,
	      		
	      	});
	      });	
	</script>
	
Refer to the **Options** section below for more info on the various options
available.

Options:
--------
A complete listing of the options that can be passed to the `carousel` method is below.

<table>
<tr>
	<th>Parameter</th>
	<th>Default</th>
	<th>Description</th>
</tr>

<tr>
	<td>itemWidth</td>
	<td>300</td>
	<td>The width of the carousel item images.</td>
</tr>
<tr>
	<td>itemHeight</td>
	<td>450</td>
	<td>The height of the carousel item images.</td>
</tr>
<tr>
	<td>distance</td>
	<td>15</td>
	<td>The distance between the carousel items.</td>
</tr>
<tr>
	<td>startIndex</td>
	<td>'auto'</td>
	<td>The index of the carousel item to show at start-up. Use 0 for the first item and 'auto' for the middle.</td>
</tr>
<tr>
	<td>enableKeyboard</td>
	<td>true</td>
	<td>If it's set to true, you can use the direction keys on your keyboard to navigate between the carousel items.</td>
</tr>
<tr>
	<td>enableMouseWheel</td>
	<td>true</td>
	<td>If it's set to true, you can use the mouse wheel to switch between the carousel items.</td>
</tr>
<tr>
	<td>reverseMouseWheel</td>
	<td>false</td>
	<td>Indicates whether the direction of the mouse wheel navigation will be reversed.</td>
</tr>
<tr>
	<td>autoSlideshow</td>
	<td>false</td>
	<td>Indicates whether to display the items in auto slideshow mode.</td>
</tr>
<tr>
	<td>autoSlideshowDelay</td>
	<td>2.5</td>
	<td>The number of seconds to wait for each carousel item during auto slideshow mode.</td>
</tr>
<tr>
	<td>loop</td>
	<td>true</td>
	<td>If it's set to true, the auto slideshow returns to the first item after showing the last one. This option only works when the autoSlideshow parameter is set to true.</td>
</tr>
<tr>
	<td>selectedItemDistance</td>
	<td>50</td>
	<td>The distance between the currently selected item and other items.</td>
</tr>
<tr>
	<td>selectedItemZoomFactor</td>
	<td>1.0</td>
	<td>The scale factor for the currently selected item. It should be equal to or less than 1.0.</td>
</tr>
<tr>
	<td>unselectedItemZoomFactor</td>
	<td>0.6</td>
	<td>The scale factor for the unselected items. It should be equal to or less than 1.0.</td>
</tr>
<tr>
	<td>unselectedItemAlpha</td>
	<td>0.6</td>
	<td>The opacity of the unselected carousel items.</td>
</tr>
<tr>
	<td>motionStartDistance</td>
	<td>150</td>
	<td>The distance between the center and the place on each side where item scaling and other property updates will begin changing. (Such as opacity, scale)</td>
</tr>
<tr>
	<td>topMargin</td>
	<td>30</td>
	<td>The distance between the top of the plugin and the currently selected item.</td>
</tr>
<tr>
	<td>preload</td>
	<td>true</td>
	<td>Indicates whether to preload all of the items at start and then start the plugin.</td>
</tr>
<tr>
	<td>showPreloader</td>
	<td>true</td>
	<td>Indicates whether a preloader will be shown while loading the images.</td>
</tr>
<tr>
	<td>navigationButtonsVisible</td>
	<td>true</td>
	<td>Indicates whether the navigation buttons will be visible.</td>
</tr>
<tr>
	<td>gradientStartPoint</td>
	<td>0.15</td>
	<td>The color start point for the gradient overlays. It should be between 0 and 1.0</td>
</tr>
<tr>
	<td>gradientEndPoint</td>
	<td>1.0</td>
	<td>The color end point for the gradient overlays. It should be between 0 and 1.0</td>
</tr>
<tr>
	<td>gradientOverlayVisible</td>
	<td>true</td>
	<td>Indicates whether the gradient overlays will be visible.</td>
</tr>
<tr>
	<td>gradientOverlayColor</td>
	<td>'#fff'</td>
	<td>The color of the gradient overlays.</td>
</tr>
<tr>
	<td>gradientOverlaySize</td>
	<td>215</td>
	<td>The width of the gradient overlays.</td>
</tr>
<tr>
	<td>reflectionVisible</td>
	<td>false</td>
	<td>Indicates whether the item image reflection will be visible.</td>
</tr>
<tr>
	<td>reflectionDistance</td>
	<td>4</td>
	<td>The distance between the image and the reflection.</td>
</tr>
<tr>
	<td>reflectionSize</td>
	<td>100</td>
	<td>The height of the reflection.</td>
</tr>
<tr>
	<td>reflectionAlpha</td>
	<td>0.38</td>
	<td>The opacity of the reflection.</td>
</tr>
<tr>
	<td>slideSpeed</td>
	<td>0.45</td>
	<td>The slide transition speed in seconds.</td>
</tr>
<tr>
	<td>selectByClick</td>
	<td>false</td>
	<td>Indicates whether a carousel item can be selected with a single click.</td>
</tr>
</table>

#License:
pik carousel is released under the [MIT license](http://www.opensource.org/licenses/MIT).
