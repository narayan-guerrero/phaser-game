# Phaser 3 + React + TypeScript

Live [demo available here](https://s3.eu-central-1.amazonaws.com/phaser3-typescript/phaser3-with-react-example/index.html)

This example is based on the [Phaser 3 TypeScript Template](https://github.com/yandeu/phaser-project-template#readme), with few modifications:

- Added **react react-dom @types/react @types/react-dom**
- Added **"jsx": "react"** to tsconfig.json
- Added
  `<div id="react"></div><div id="phaser"></div>` to index.html
- Renamed files which are using React to **.tsx**

Bugs:

- [[SOVLED in #1361](https://phaser.discourse.group/t/scalemanager-ignore-virtual-keyboard/1361)] When the Keyboard in open on a mobile phone, the Game resizes
- [[SOVLED in #1656](https://phaser.discourse.group/t/click-on-div-under-phaser-object/1656/18)] Don't know how to make something similar to this (`this.input.setTopOnly(true)`) work

The MIT License (MIT) 2019 - [Yannick Deubel](https://github.com/yandeu). Please have a look at the [LICENSE](LICENSE) for more details.
