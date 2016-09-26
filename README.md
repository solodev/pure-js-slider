# pure-js-slider
Sliders are a great way to display the "best of" your website's content to users. Most sliders, however, rely on third party jQuery plugins to function. In this tutorial, [Solodev](https://www.solodev.com/) will teach you how to build an animated slider with pure JavaScript.

## Tutorial

For detailed instructions, view Solodev's [How to Build a Slider with Pure JavaScript](https://www.solodev.com/blog/web-design/how-to-build-an-animated-slider-with-js.stml) article.

## Demo

Check out a working example on [JSFiddle](https://jsfiddle.net/solodev/yokph2nh/).

## HTML

This slider contains the following basic HTML markup.
```
<div class="slider-container">
  <div class="slider-control left inactive"></div>
  <div class="slider-control right"></div>
  <ul class="slider-pagi"></ul>
  <div class="slider">
    <div class="slide slide-0 active">
      <div class="slide__bg"></div>
      <div class="slide__content">
        <svg class="slide__overlay" viewBox="0 0 720 405" preserveAspectRatio="xMaxYMax slice">
          <path class="slide__overlay-path" d="M0,0 150,0 500,405 0,405" />
        </svg>
        <div class="slide__text">
          <h2 class="slide__text-heading" style="font-family: 'Open Sans Condensed', sans-serif;">Big Data. Realtime Insight.</h2>
          <p class="slide__text-desc" style="font-family: 'Open Sans Condensed', sans-serif;"> Content is automatically generated, sales emails, customer retention emails, and custom landing pages are generated based on site content using natural language processing to create relevant marketing content and distribute it across multiple channels.</p>
          <a class="slide__text-link" style="font-family: 'Open Sans Condensed', sans-serif;">Learn More</a>
        </div>
      </div>
    </div>
    <div class="slide slide-1 ">
      <div class="slide__bg"></div>
      <div class="slide__content">
        <svg class="slide__overlay" viewBox="0 0 720 405" preserveAspectRatio="xMaxYMax slice">
          <path class="slide__overlay-path" d="M0,0 150,0 500,405 0,405" />
        </svg>
        <div class="slide__text">
          <h2 class="slide__text-heading" style="font-family: 'Open Sans Condensed', sans-serif;">Disrupting Industries</h2>
          <p class="slide__text-desc" style="font-family: 'Open Sans Condensed', sans-serif;">WebCorpCo is all about making sure your marketing stack is in alignment with your company as well as the customers you serve. There is no 'one size fits all' approach to marketing. Every business is unique, customers are unique, and your marketing should be as well.</p>
          <a class="slide__text-link" style="font-family: 'Open Sans Condensed', sans-serif;">Learn More</a>
        </div>
      </div>
    </div>
    <div class="slide slide-2">
      <div class="slide__bg"></div>
      <div class="slide__content">
        <svg class="slide__overlay" viewBox="0 0 720 405" preserveAspectRatio="xMaxYMax slice">
          <path class="slide__overlay-path" d="M0,0 150,0 500,405 0,405" />
        </svg>
        <div class="slide__text">
          <h2 class="slide__text-heading" style="font-family: 'Open Sans Condensed', sans-serif;">Moving Business Forward</h2>
          <p class="slide__text-desc" style="font-family: 'Open Sans Condensed', sans-serif;">Sales is the direct result of marketing and sales data is sometimes even more important than the sales themselves. Why did they buy? What did they buy? When? Who bought? How much did it cost? Then a comparison of sales YTD or Year over Year. This analysis can optimize your ability to sell with WebCorpCo Analytics.</p>
          <a class="slide__text-link" style="font-family: 'Open Sans Condensed', sans-serif;">Learn More</a>
        </div>
      </div>
    </div>
</div>

```

## CSS

All necessary CSS is included in pure-js.slider.css

## External Includes

This tutorial includes the following third party resources.
```
<link href="https://fonts.googleapis.com/css?family=Open+Sans+Condensed:300" rel="stylesheet">
<link href="pure-js-slider.css" rel="stylesheet">
<script src="https://code.jquery.com/jquery-2.2.0.min.js" type="text/javascript"></script>

```
