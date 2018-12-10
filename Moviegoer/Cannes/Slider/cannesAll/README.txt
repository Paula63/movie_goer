Image Slider Maker README
=========================
ImageSliderMaker.com


Using in your website
---------------------

Please first make sure you have fully extracted the contents of the zip file.
In Windows, right-click on imageslidermaker.zip and select Extract All...

To get your slider working in your web page, you must add
my-slider.css, ism-2.2.min.js and the slide images to your project
directory and paste the markup (included below) into your HTML.

The directory structure of this package:

  imageslidermaker/
    README.txt
    example.html
    ism/
      css/
        my-slider.css
      js/
        ism-2.2.min.js
      image/
        slides/
          _u/1542059321951_645362.jpg
          _u/1542059321929_807376.jpg
          _u/1542059321880_741292.jpg
          _u/1542059321839_241771.jpg
          _u/1542059321809_55982.jpg
          _u/1542059321792_995489.jpg
          _u/1542059321702_548580.jpg

For a working example, open example.html in your web browser or
follow the instructions below to integrate the slider into your
project.


Step by step instructions
-------------------------

1. Paste the following into the head of your HTML file:

<link rel="stylesheet" href="ism/css/my-slider.css"/>
<script src="ism/js/ism-2.2.min.js"></script>


2. Paste this into the body of your HTML file (at the location where:
   you would like your slider to appear in the page):

<div class="ism-slider" id="my-slider">
  <ol>
    <li>
      <img src="ism/image/slides/_u/1542059321951_645362.jpg">
      <div class="ism-caption ism-caption-0">Grand Prix Spike Lee</div>
    </li>
    <li>
      <img src="ism/image/slides/_u/1542059321929_807376.jpg">
      <div class="ism-caption ism-caption-0">Actor Marcello Fonte</div>
    </li>
    <li>
      <img src="ism/image/slides/_u/1542059321880_741292.jpg">
      <div class="ism-caption ism-caption-0">Screenplay — TIE Alice Rohrwacher</div>
    </li>
    <li>
      <img src="ism/image/slides/_u/1542059321839_241771.jpg">
      <div class="ism-caption ism-caption-0">Jury Prize Nadine Labaki</div>
    </li>
    <li>
      <img src="ism/image/slides/_u/1542059321809_55982.jpg">
      <div class="ism-caption ism-caption-0">Palme d'Or  Hirokazu Kore-eda</div>
    </li>
    <li>
      <img src="ism/image/slides/_u/1542059321792_995489.jpg">
      <div class="ism-caption ism-caption-0">Director Pawel Pawlikowski</div>
    </li>
    <li>
      <img src="ism/image/slides/_u/1542059321702_548580.jpg">
      <div class="ism-caption ism-caption-0">Actress Samal Yeslyamova</div>
    </li>
  </ol>
</div>
<p class="ism-badge" id="my-slider-ism-badge"><a class="ism-link" href="http://imageslidermaker.com" rel="nofollow">generated with ISM</a></p>


3. Copy the ism/ directory into the root directory of your project.

   The css, js and image paths are relative, meaning the ism/
   directory should be in the same directory (path) as your HTML
   file containing the slider.


