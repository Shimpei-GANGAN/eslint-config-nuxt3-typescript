<div align="center">
  <!-- タイトル -->
  <h1>
    ESLint rules for Nuxt3 + TypeScript
  </h1>
  <!-- バッジ一覧 -->
  <span>
    <!-- Nuxt -->
    <a href="https://github.com/nuxt/nuxt">
      <img
        src="https://img.shields.io/badge/Nuxt-v3.2.0-00DC82.svg?logo=Nuxt.js"
        alt="Nuxt Version Badge"
      >
    </a>
    <!-- Vuetify -->
    <a href="https://github.com/vuetifyjs/vuetify">
      <img
        src="https://img.shields.io/badge/Vuetify-v3.1.4-1867C0.svg?logo=Vuetify"
        alt="Vuetifty Version Badge"
      >
    </a>
  </span>
</div>

ESLint rules for Nuxt3 + TypeScript for myself.

### Installation

```shell
$ npm i -D @nuxtjs/eslint-config \
        prettier \
        eslint-config-prettier \
        eslint-plugin-unused-imports \
        @ianvs/prettier-plugin-sort-imports \
        eslint-plugin-vuetify
```

## [eslint-config-nuxt3-typescript/base](./lib/configs/base.js)

<span>
  <!-- Nuxt3 ESLint packages -->
  <a href="https://github.com/nuxt/eslint-config">
    <img
      src="https://img.shields.io/badge/Nuxt3 ESLint packages-v12.0.0-00DC82.svg?logo=Nuxt.js"
      alt="Nuxt3-ESLint-Packages Version Badge"
    >
  </a> 
</span>

- Created based on [@nuxtjs/eslint-config-typescript](https://github.com/nuxt/eslint-config#typescript).

  The following settings are extended in based.

  - [eslint-plugin-vue/vue3-recommended](https://github.com/vuejs/eslint-plugin-vue)
  - [@typescript-eslint/eslint-plugin](https://github.com/typescript-eslint/typescript-eslint/tree/main/packages/eslint-plugin)

- Add ESLint rules and Prettier plugins with custom.

  - [prettier](https://github.com/prettier/prettier)
  - [eslint-config-prettier](https://github.com/prettier/eslint-config-prettier)

## [eslint-config-nuxt3-typescript/recommended](./lib/configs/recommended.js)

- Based on [eslint-config-nuxt3-typescript/base](./lib/configs/base.js).
- Add ESLint rules and Prettier plugins with custom.
  - [eslint-plugin-unused-imports](https://github.com/sweepline/eslint-plugin-unused-imports)
  - [@ianvs/prettier-plugin-sort-imports](https://github.com/ianvs/prettier-plugin-sort-imports)
    - forked from [@trivago/prettier-plugin-sort-imports](https://github.com/trivago/prettier-plugin-sort-imports).

## [eslint-config-nuxt3-typescript/vuetify3-base](./lib/configs/vuetify3-base.js)

<span>
  <!-- Vuetify3 ESLint packages -->
  <a href="https://github.com/vuetifyjs/eslint-plugin-vuetify">
    <img
      src="https://img.shields.io/badge/Vuetify3 ESLint packages-v2.0.0 beta.2-1867C0.svg?logo=Vuetify"
      alt="Vuetify3-ESLint-Packages Version Badge"
    >
  </a> 
</span>

- Based on [eslint-config-nuxt3-typescript/base](./lib/configs/base.js).
- Add ESLint rules for Vuetify3
  - [eslint-plugin-vuetify](https://github.com/vuetifyjs/eslint-plugin-vuetify)

## [eslint-config-nuxt3-typescript/vuetify3-recommended](./lib/configs/vuetify3-base.js)

- Based on [eslint-config-nuxt3-typescript/recommended](./lib/configs/recommended.js) and [eslint-config-nuxt3-typescript/vuetify3-base](./lib/configs/vuetify3-base.js).
