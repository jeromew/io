## io

## Input Output format handling for the JSCAD projects

[![GitHub version](https://badge.fury.io/gh/jscad%2Fio.svg)](https://badge.fury.io/gh/jscad%2Fio)

## Overview

This repository includes all the input/output format handling for the JSCAD projects, and can also be used seperatly.

### Input Format Handling (deserializers)

ie: file data => jscad code (that can be evaluated to CSG/CAG)
> note : currently serializers & deserializers are NOT symetrical as deserializers
do not generate CSG/CAG objects

Following formats are supported as inputs:
 - [AMF](https://github.com/jscad/io/blob/master/packages/amf-deserializer)
 - [gcode](https://github.com/jscad/io/blob/master/packages/gcode-deserializer)
 - [JSON](https://github.com/jscad/io/blob/master/packages/json-deserializer)
 - [OBJ](https://github.com/jscad/io/blob/master/packages/obj-deserializer)
 - [STL (binary, ASCII)](https://github.com/jscad/io/blob/master/packages/stl-deserializer)
 - [SVG](https://github.com/jscad/io/blob/master/packages/svg-deserializer)

### Output Format Handling (serializers)

ie: CSG/CAG => blob

Following formats are supported as outputs:
  - [AMF](https://github.com/jscad/io/blob/master/packages/amf-serializer)
  - [DXF](https://github.com/jscad/io/blob/master/packages/dxf-serializer)
  - [JSON](https://github.com/jscad/io/blob/master/packages/json-serializer)
  - [STL (binary, ASCII)](https://github.com/jscad/io/blob/master/packages/stl-serializer)
  - [SVG](https://github.com/jscad/io/blob/master/packages/svg-serializer)
  - [X3D](https://github.com/jscad/io/blob/master/packages/x3d-serializer)


## Table of Contents

- [Installation](#installation)
- [Usage](#usage)
- [Contribute](#contribute)
- [License](#license)


## Installation

```
npm install @jscad/io
```

## Usage

- as Node module :

```
const io = require('@jscad/io')
```


## Contribute

This library is part of the JSCAD Organization, and is maintained by a group of volunteers. We welcome and encourage anyone to pitch in but please take a moment to read the following guidelines.

* If you want to submit a bug report please make sure to follow the [Reporting Issues](https://github.com/jscad/csg.js/wiki/Reporting-Issues) guide. Bug reports are accepted as [Issues](https://github.com/jscad/io/issues/) via GitHub.

* If you want to submit a change or a patch, please see the [Contributing guidelines](https://github.com/jscad/io/blob/master/CONTRIBUTING.md). New contributions are accepted as [Pull Requests](https://github.com/jscad/io/pulls/) via GithHub.

* We only accept bug reports and pull requests on **GitHub**.

* If you have a question about how to use the IO library, then please start a conversation at the [OpenJSCAD.org User Group](https://plus.google.com/communities/114958480887231067224). You might find the answer in the [OpenJSCAD.org User Guide](https://github.com/Spiritdude/OpenJSCAD.org/wiki/User-Guide).

* If you have a change or new feature in mind, please start a conversation with the [Core Developers](https://plus.google.com/communities/114958480887231067224) and start contributing changes.

Small Note: If editing this README, please conform to the [standard-readme](https://github.com/RichardLitt/standard-readme) specification.

## License

[The MIT License (MIT)](https://github.com/jscad/io/blob/master/LICENSE)
(unless specified otherwise)
