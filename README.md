# v-hub

A vue plugin working as event bus.

## Install

```bash
yarn add v-hub

# or
npm install --save v-hub
```

## Import

```javascript
// import
import vHub from 'v-hub';
Vue.use(vHub);

// use
created() {
  this.$hub.on('EVENT_NAME', () => {
    // ...
  });
},
destroy() {
  this.$hub.off();
}
```

## API

- `.on`
- `.once`
- `.emit`
- `.off`

