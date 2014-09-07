# bounce-in-animation
[Polymer][polymer] web component for a bounce in effect.

## Install

```bash
bower install --save mbykovskyy/bounce-in-animation
```

## Usage

```html
<link rel="import" href="bounce-in-animation.html">

<div id="box"></div>
<bounce-in-animation id="bounce-in" duration="500" easing="ease-out"></bounce-in-animation>

<script>
  document.addEventListener('polymer-ready', function() {
    var animation = document.getElementById('bounce-in');
    animation.target = document.getElementById('box');
    animation.play();
  });
</script>
```

See [component page][bounce-in-animation] for details and demo.

[polymer]: http://polymer-project.org "Polymer"
[bounce-in-animation]: http://mbykovskyy.github.io/bounce-in-animation "Component Page"
