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
          _u/1542064196184_52755.jpg
          _u/1542064196156_442831.jpg
          _u/1542064202147_94425.jpg
          _u/1542064196168_843303.jpg
          _u/1542064258280_714033.jpg
          _u/1542064258267_940296.jpg
          _u/1542064258214_747542.jpg
          _u/1542064258258_925416.jpg

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
      <img src="ism/image/slides/_u/1542064196184_52755.jpg">
      <div class="ism-caption ism-caption-0">Actor Denzel Washington</div>
    </li>
    <li>
      <img src="ism/image/slides/_u/1542064196156_442831.jpg">
      <div class="ism-caption ism-caption-0">Actor Daniel Day-Lewis</div>
    </li>
    <li>
      <img src="ism/image/slides/_u/1542064202147_94425.jpg">
      <div class="ism-caption ism-caption-0">Actor Tom Hanks</div>
    </li>
    <li>
      <img src="ism/image/slides/_u/1542064196168_843303.jpg">
      <div class="ism-caption ism-caption-0">Actor Timothee Chalamet</div>
    </li>
    <li>
      <img src="ism/image/slides/_u/1542064258280_714033.jpg">
      <div class="ism-caption ism-caption-0">Actress Sally Hawkins</div>
    </li>
    <li>
      <img src="ism/image/slides/_u/1542064258267_940296.jpg">
      <div class="ism-caption ism-caption-0">Actress Michelle Williams</div>
    </li>
    <li>
      <img src="ism/image/slides/_u/1542064258214_747542.jpg">
      <div class="ism-caption ism-caption-0">Actress Jessica Chastain</div>
    </li>
    <li>
      <img src="ism/image/slides/_u/1542064258258_925416.jpg">
      <div class="ism-caption ism-caption-0">Actress Meryl Streep</div>
    </li>
  </ol>
</div>
<p class="ism-badge" id="my-slider-ism-badge"><a class="ism-link" href="http://imageslidermaker.com" rel="nofollow">generated with ISM</a></p>


3. Copy the ism/ directory into the root directory of your project.

   The css, js and image paths are relative, meaning the ism/
   directory should be in the same directory (path) as your HTML
   file containing the slider.


