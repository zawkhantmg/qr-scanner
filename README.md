# QR-SCANNER

## Setup
  - Run nuxt project.
  - ````yarn run nuxt --port=8888````


## Installation :package:

### With NPM

Run

```bash
npm install vue-qrcode-reader
```

You can import the components independantly

```javascript
import { QrcodeStream, QrcodeDropZone, QrcodeCapture } from 'vue-qrcode-reader'

const MyComponent = {

  components: {
    QrcodeStream,
    QrcodeDropZone,
    QrcodeCapture
  },

  // ...
))
```

or register all of them globally right away

```javascript
import Vue from "vue";
import VueQrcodeReader from "vue-qrcode-reader";

Vue.use(VueQrcodeReader);
```

## Without NPM

Include the following JS file:

https://unpkg.com/vue-qrcode-reader/dist/VueQrcodeReader.umd.min.js

Make sure to include it after Vue:

```html
<script src="./vue.js"></script>
<script src="./VueQrcodeReader.umd.min.js"></script>
```

All components are automatically registered globally.
Use kebab-case to reference them in your templates:

```html
<qrcode-stream></qrcode-stream>
<qrcode-drop-zone></qrcode-drop-zone>
<qrcode-capture></qrcode-capture>
```


## Ref Link

  - https://www.npmjs.com/package/vue-qrcode-reader
  - https://gruhn.github.io/vue-qrcode-reader/demos/Upload.html
  
