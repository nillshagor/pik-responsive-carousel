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
    <th>Option</th>
    <th>Data Attribute</th>
    <th>Description</th>
  </tr>
  <tr>
    <td><i>from</i></td>
    <td><i>data-from</i></td>
    <td>The number to start counting from. <i>(default: 0)</i></td>
  </tr>
  <tr>
    <td><i>to</i></td>
    <td><i>data-to</i></td>
    <td>The number to stop counting at. <i>(default: 100)</i></td>
  </tr>
  <tr>
    <td><i>speed</i></td>
    <td><i>data-speed</i></td>
    <td>The number of milliseconds it should take to finish counting.
        <i>(default: 1000)</i></td>
  </tr>
  <tr>
    <td><i>refreshInterval</i></td>
    <td><i>data-refresh-interval</i></td>
    <td>The number of milliseconds to wait between refreshing the counter.
        <i>(default: 100)</i></td>
  </tr>
  <tr>
    <td colspan="2"><i>formatter (value, options)</i></td>
    <td>A handler that is used to format the current value before rendering to
        the DOM.  The true current value and options set is passed to the
        function, and it is run in the context of the DOM element.  It must
        return the formatted value. <i>(default:
        <code>value.toFixed(options.decimal)</code>)</i></td>
  </tr>
  <tr>
    <td colspan="2"><i>onUpdate (value)</i></td>
    <td>A callback function that is triggered for every iteration that the
        counter updates.  The currently rendered value is passed to the
        function, and it is called in the context of the DOM element.
        <i>(default: null)</i></td>
  </tr>
  <tr>
    <td colspan="2"><i>onComplete (value)</i></td>
    <td>A callback function that is triggered when counting finishes.  The
        final rendered value is passed to the function, and it is called in the
        context of the DOM element. <i>(default: null)</i></td>
  </tr>
</table>

#License:
pik carousel is released under the [MIT license](http://www.opensource.org/licenses/MIT).
