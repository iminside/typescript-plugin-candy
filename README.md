# Typescript Plugin Candy

A TypeScript language service plugin providing support for CSS Candy Modules

<div align="center">
<img src="https://img.shields.io/github/workflow/status/iminside/typescript-plugin-candy/Node.js%20CI/master" alt="GitHub Workflow Status (branch)" /> 
<img src="https://img.shields.io/github/languages/top/iminside/typescript-plugin-candy" alt="language" />
<img src="https://img.shields.io/npm/l/typescript-plugin-candy" alt="license" />  
</div>

![](https://habrastorage.org/webt/1g/5v/uo/1g5vuorp3cjov5rejpuxbgdy43c.gif)

## Install

```bash
npm i -D typescript-plugin-candy
```

Once installed, add this plugin to your `tsconfig.json`:

```json
{
    "compilerOptions": {
        "plugins": [{ "name": "typescript-plugin-candy" }]
    }
}
```

Use workspace typescript version

![](https://habrastorage.org/webt/hn/zr/_k/hnzr_kimoimx66k_t_xxhkrkkkg.png)

## Features

Auto-support intellisense for `.css`, `.scss`, `.sass`, `.styl` modules

## Thanks

Brody McKee for [typescript-plugin-css-modules](https://github.com/mrmckeb/typescript-plugin-css-modules)
