JavaScript Slider
==========

Description
-----------
This is a open source JavaScript slider. It uses jQury as a dependencies.

The features are <br/>
1. Platform oriented <br/>
2. Responsive <br/>
3. Any number of image may used <br/>

Installation
-----------
1. Add the following css and js files.
  ```javascript
  <link rel="stylesheet" href="styles/kheyaslider.css" type="text/css" media="screen" />
  <link rel="stylesheet" href="styles/font-awesome.min.css" type="text/css" media="screen" />

  <script type="text/javascript" src="scripts/jquery-1.9.1.min.js"></script>
  <script type="text/javascript" src="scripts/jquery.kheya.slider.js"></script>
  ```
2. Call the slider form page header. The JavaScript code is as follows. <br/>
  ```javascript
    <script type="text/javascript">
      
        $(document).ready(function () {
            $('.kheya-slider').KheyaJQSlider({
                SlideDuration: 3000,
                MaxWidth:"1200px",
                MaxHeight:"600px"
            });
        });
        
    </script>
  ```
3. The html code is as follows.
  
  ```javascript
  <div class="kheya-slider">
      <div class="slider-container">
          <div class="slider-piece">
              <img src="images/1.jpg" alt="Image" />
          </div>
          <div class="slider-piece">
              <img src="images/2.jpg" alt="Image"/>
          </div>
          <div class="slider-piece">
              <img src="images/3.jpg" alt="Image"/>
          </div>
          <div class="slider-piece">
              <img src="images/4.jpg" alt="Image" />
          </div>
      </div>
  </div>
  ```
The Slider output is as follows.
-----------
<p align="center">
  <img src="https://s10.postimg.org/m88iljjbt/slider.jpg" width="700"/>
</p>

