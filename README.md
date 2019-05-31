### vue-flip-card
[demo](https://andersponders.github.io/vue-flip-card/demo/)


Generic flip card that allows for completely arbitrary content on each side. Slot-ified version of Karakanb's awesome **vue-info-card** component, which you can find [here.](https://github.com/karakanb/vue-info-card)

## Installation
FlipCard uses vuetify with md-icons as the icon that you click to flip the cards, but you can put whatever you want in there instead if you dont use vuetify.

## Usage

Take a look at this sick example, right here boys:

```html
<template>
  <FlipCard>
    <template slot="front">
      <span>Hey loser</span>
    </template>
    <template slot="back">
      <span>Thought u could get rid of me loser?</span>
    </template>
  </FlipCard>
</template>

<script>
import FlipCard from 'vue-flip-card';

export default {
  components: {
    FlipCard,
  }
};
</script>
```
### Props

Throw whatever you want in those slots

## Credits

Addtl credits from Karakanb:


The component is based on two main features: spark line and flip effect. The spark line is created with the amazing [vuetrend](https://github.com/QingWei-Li/vue-trend) component, which creates cool and customizable graphs. The flipping effect is implemented in pure CSS, and influenced from the tutorial [here](https://davidwalsh.name/css-flip). 

## Browser Support
The component supports all of the modern browsers, with least versions: Firefox 37, Chrome 42, Safari 8, Opera 29, and IE 10.

## License
The project is under MIT License.
