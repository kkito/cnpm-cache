cnpm-cache
=========

fork from [npm-cache](https://github.com/swarajban/npm-cache)

the only difference is use [cnpm](http://npm.taobao.org/) instead of npm

## why use it

- npm command is very slow in china , some package can't even install. cnpm can resolve this problem.
- for ci, some upload whole "node_module" , but i prefer leave it empty. so accelerate npm install in every ci build.



## Installation
```
npm install -g cnpm 
npm install -g git+https://github.com/kkito/cnpm-cache.git
```

## Usage
```
cnpm-cache install
```
visit [npm-cache](https://github.com/swarajban/npm-cache) for more infomation


