# Vue.js Template

![Node](https://img.shields.io/badge/Node.js-v18.7.0-fb7185.svg?logo=&style=flat-square) ![License](https://img.shields.io/badge/License-MIT-0284C7.svg?logo=&style=flat-square)

面倒なセットアップをを避けて、個人用テンプレートの Repository です

### スタック

| Name        | Ver |
| ----------- | --- |
| Vue.js      | 3   |
| Vite        | 4   |
| TailwindCSS | 3   |
| TypeScript  | 4.9 |

### 利用

```bash
git clone https://github.com/kensoz/vue-template.git
```

### セットアップ

ESLint

```sh
yarn add -D eslint eslint-plugin-vue @vue/eslint-config-typescript @typescript-eslint/eslint-plugin @typescript-eslint/parser eslint-plugin-html
```

Prettier

```sh
yarn add -D prettier @vue/eslint-config-prettier
```

TailwindCSS

```sh
yarn add -D tailwindcss postcss autoprefixer
npx tailwindcss init -p
yarn add -D prettier-plugin-tailwindcss
```

Editorconfig

```sh
yarn add -D editorconfig-checker
```
