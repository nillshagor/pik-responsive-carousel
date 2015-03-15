# pik-responsive-carousel
Pik is a responsive slider which you included on your template. It is totaly responsive and all major browser support.

# uses
  adding markup
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

							<li>
								<img src="" alt="" />
								<div class="sc-content">
									<h2></h2>
								</div>
								<div class="sc-author">
									<h2></h2>
								</div>	<h2>Leslie Lawson</h2>
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
