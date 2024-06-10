# cncjs-pendant-boilerplate
A bare minimum example to develop a cncjs pendant.

![image](https://cloud.githubusercontent.com/assets/447801/22881387/2b60de08-f221-11e6-9372-288e118788a9.png)

## Installation
```
npm install
```

## Usage
Run `bin/cncjs-pendant-boilerplate` to start the interactive client. Pass --help to `cncjs-pendant-boilerplate` for more options.

```
bin/cncjs-pendant-boilerplate --help
```

## Changes to boilerplate

Added custom commands to move the cnc head:

* tri: Makes the CNC head move in one triangle

* multiPoint: moves the CNC head through points in a list

* loopPoins: a command that loops through different coordinates until the space button is pressed.
