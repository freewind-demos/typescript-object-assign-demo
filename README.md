TypeScript "Object.assign" Demo
===============================

如果没有特别设置，在typescript中使用`Object.assign`时会无法编译：

```
TS2339: Property 'assign' does not exist on type 'ObjectConstructor'
```

需要在`tsconfig.json`-> `compilerOptions`中增加以下某种方式：

- `"target": "es6"`
- `"lib": ["es6"]`

```
npm install
npm run demo
```

