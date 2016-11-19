# riot-carousel

A simple carousel component

## Demo

[RIOT Carousel](https://acousticseagull.github.io)

## Usage

```javascript
<carousel>
  <carousel-item style="background-image: url('http://placehold.it/1080x768?text=First+Slide')"></carousel-item>
  <carousel-item style="background-image: url('http://placehold.it/1080x768?text=Second+Slide')"></carousel-item>
  <carousel-item style="background-image: url('http://placehold.it/1080x768?text=Third+Slide')"></carousel-item>
</carousel>

<script src="path/to/riot.js"></script>
<script src="path/to/carousel.js" type="riot/tag"></script>

<script>  
  riot.mount('carousel');
</script>
```

## Attributes

| Attribute | Description | Type | Default |
| --------- | ----------- | ---- | ------- |
| index     | sets the starting slide | number | 0
| interval  | sets delay between slides | number | 5000 |
| height    | the height of the carousel | string | 480px |
