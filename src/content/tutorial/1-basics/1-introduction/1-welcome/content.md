---
type: lesson
title: Nx Graph Error
focus: /counter.js
---

# Nx Graph Error

If you run `nx graph` in the terminal it will throw this error:

```
Error: spawn /home/tutorial/node_modules/open/xdg-open EACCES
    at __node_internal_captureLargerStackTrace2 (https://httplocalhost4321-zfes.w-corp-staticblitz.com/builtins.5bf3667c.js:101:5335)
    at __node_internal_errnoException2 (https://httplocalhost4321-zfes.w-corp-staticblitz.com/builtins.5bf3667c.js:101:6592)
    at ChildProcess._handle.onexit (https://httplocalhost4321-zfes.w-corp-staticblitz.com/builtins.5bf3667c.js:52:3320)
    at https://httplocalhost4321-zfes.w-corp-staticblitz.com/blitz.dc4d7514.js:40:964896
    at _0x4fd871 (https://httplocalhost4321-zfes.w-corp-staticblitz.com/blitz.dc4d7514.js:40:508718)
    at https://httplocalhost4321-zfes.w-corp-staticblitz.com/blitz.dc4d7514.js:40:508484 {
  errno: -13,
  code: 'EACCES',
  syscall: 'spawn /home/tutorial/node_modules/open/xdg-open',
  path: '/home/tutorial/node_modules/open/xdg-open',
  spawnargs: [ 'http://127.0.0.1:4211/projects' ]
}

Node.js 18.20.3
```

If you run `nx graph --open=false` the graph will open correctly.
