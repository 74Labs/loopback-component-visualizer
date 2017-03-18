# loopback-component-visualizer

### Introduction

Visualizing a model is sometimes a difficult task. Its becomes more worse when the data model gets larger,
trying to understand how models relate to eachother.

loopback-component-visualizer helps you in creating a model diagram with the relation for you loopback application.

### Table of contents
* Installation
* Usage

#### Installation

```sh
$ npm install 74Labs/loopback-component-visualizer
```

#### Usage

Inside your component-config.json, add the loopback-component-visualizer and a '/visualize' api will be mounted to your server.

You can browse @ http://host:port/visualize

```sh
"loopback-component-visualizer": {
  "mountPath": "/visualize"
}
```
