# Vue 3 + Vite + Vuetify3　＋Storybook

## vue-cliの準備
```
npm install -g @vue/cli
vue --version
```

## プロジェクト作成
```
yarn create vite vite-vue-vuetify-app --template vue
```

## 起動確認
```
cd vite-vue-vuetify-app
yarn
yarn dev
```

## いったん終了し、Vuetifyの追加(vue-cliを使って追加 yarnではない)
```
vue add vuetify
```

以下の設問があるので「Vite Preview (Vuetify 3 + Vite)」を選択   
```
? Choose a preset:
  Configure (advanced)
  Default (recommended)
> Vite Preview (Vuetify 3 + Vite)
  Prototype (rapid development)
  Vuetify 3 Preview (Vuetify 3)
```


## 起動確認
```
yarn dev
```


「Welcome to the Vuetify 3 Alpha」のページに変わっていることを確認



## リポジトリに追加
```
git init
git add *
git commit -m "first commit"
git branch -M main
git remote add origin https://github.com/refrain62/vite-vue-vuetify-app.git
git push -u origin main
```

## Storybookの追加と起動
```
npx sb@next init --builder storybook-builder-vite
yarn storybook
```

This template should help get you started developing with Vue 3 in Vite. The template uses Vue 3 `<script setup>` SFCs, check out the [script setup docs](https://v3.vuejs.org/api/sfc-script-setup.html#sfc-script-setup) to learn more.

## Recommended IDE Setup

- [VSCode](https://code.visualstudio.com/) + [Volar](https://marketplace.visualstudio.com/items?itemName=johnsoncodehk.volar)
