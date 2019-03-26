# THREE.TextSprite

`class THREE.SSAOPass extends THREE.Sprite`

An instance of `SSAOPass` to be used with effectComposer

## demo

[Try it out!](https://threejs.org/examples/webgl_postprocessing_ssao.html)

## dependencies

- [THREE](https://www.npmjs.com/package/three)

## setup

### npm

```shell
npm i three.SSAOPass
```

### ES module

```javascript
import SSAOPass from 'three.SSAOPass';
```

The class `SSAOPass` will be available under the namespace `THREE`.

## members

```
.constructor({
  material,
  maxFontSize,
  minFontSize,
  redrawInterval,
  textSize,
  texture,
})
```

| argument | description |
| ---: | :--- |
| `material` | The parameters to pass to the constructor of [`SpriteMaterial`](https://threejs.org/docs/index.html#api/materials/SpriteMaterial). |
| `texture` | The parameters to pass to the constructor of [`TextTexture`](https://github.com/SeregPie/THREE.TextTexture). |

```javascript
let sprite = new THREE.TextSprite({
  material: {
    color: 0xffbbff,
    fog: true,
  },
  redrawInterval: 250,
  textSize: 10,
  texture: {
    fontFamily: 'Arial, Helvetica, sans-serif',
    text: 'Carpe Diem',
  },  
});
scene.add(sprite);
```

---
