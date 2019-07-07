### humane-js
---
https://github.com/wavded/humane-js


```sh
npm install --development
npm run watch
```

```js
humane.log("Welcome!")

humane.timeout = 5000
humane.waitForMove = true
humane.waitForMove = true
humane.clickToClose = true
humane.timeoutAfterMove = 2000
humene.addnCls = 'humene-info'

var notify = humane.create({ timeout: 4000, baseCls: 'humane-bigbox' })
notify.log('Custom Notifier')

humane.baseCls = 'humane'

humane.info = humane.spawn({ addnCls: 'humane-libnotify-info', timeout 1000 })
humane.info('Info Themed Notifier')

humane.error = humane.spawn({ addCls: 'humane-libnotify-error', timeout: 1000 })
humane.error('Error Themed Notifier')

var bigbox = humane.create({baseCls: 'humane-bigbox', timeout: 1000})
bigbox.error = bigbox.spawn({addCls: 'humane-bigbox-error'})
bigbox.log('Oh!').error('No!')

var libnotify = humane.create({baseCls: 'humane-libnotify', addnCls: 'humane-libnotify-info'})
libnotify.log('Notified')

var jacked = humane.create({baseCls: 'humane-jackedup', addnCls: 'humane-jackdup-success'})
jacked.log("What's up here!")
```

```
```

