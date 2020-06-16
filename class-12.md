# Docs for the HTML canvas Element & Chart.js

[Back to Home](https://rizo85.github.io/reading-notes/)

### HTML Canvas

##### Canvas Element docs

Canavas can be drawn on, but its not that easy: you are limited by your creative talent an by your ability to draw with javascript. However, this would be an incredible way to prove some u/i skills.

Canvas uses geometry and other css styles to create graphics

##### Canvas Methods 
![Events]( https://miro.medium.com/max/1334/0*ptjDrx_vJ27WulNd)

#### Images not needed with Canvas and element animations

[Back to Home](https://rizo85.github.io/reading-notes/)

<div class="loader">


<style>

.loader {
  animation:spin 4s linear;
  border:solid 2vmin transparent;
  border-radius:50%;
  border-right-color:#09f;
  border-top-color:#09f;
  box-sizing:border-box;
  height:20vmin;
  left:calc(50% - 10vmin);
  position:fixed;
  top:calc(50% - 10vmin);
  width:20vmin;
  z-index:1;
  &:before {
    animation:spin 2s infinite linear;
    border:solid 2vmin transparent;
    border-radius:50%;
    border-right-color:#3cf;
    border-top-color:#3cf;
    box-sizing:border-box;
    content:"";
    height:16vmin;
    left:0;
    position:absolute;
    top:0;
    width:16vmin;
  }
  &:after {
    animation:spin 4s  linear;
    border:solid 2vmin transparent;
    border-radius:50%;
    border-right-color:#6ff;
    border-top-color:#6ff;
    box-sizing:border-box;
    content:"";
    height:12vmin;
    left:2vmin;
    position:absolute;
    top:2vmin;
    width:12vmin;
  }
}

@keyframes spin {
  100% {
    transform:rotate(360deg);
  }
}

</style>


