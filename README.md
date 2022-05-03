# Vue-Setup

## プロジェクトの作成
```
vue create project
```

## 機能選択
```
? Please pick a preset: Manually select features
? Check the features needed for your project: (Press <space> to select, <a> to toggle all, <i> to invert selection)
・Default
・Manually select features
```

### 手動で機能を選択する場合（使用するものを選ぶ）
```
・Router
・Vuex
...etc

※Routerを使用する時はあとでUse history mode for router?と聞かれるので → history modeを選択(y)
```

## Versionの選択
```
・2.x
・3.x
```

## linterの選択
```
? Pick a linter / formatter config: (Use arrow keys)
・ESLint with error prevention only( → デフォルト)
・ESLint + Airbnb config
・ESLint + Standard config
・ESLint + Prettier
```

## 追加のlint機能の選択
```
・Lint on save( → デフォルト)
・Lint and fix on commit
```
## 各機能の設定ファイルの保存の方法の選択
```
? Where do you prefer placing config for Babel, PostCSS, ESLint, etc.? (Use arrow keys)
　 In dedicated config files
❯  In package.json
```

## 設定を保存するかの確認
```
? Save this as a preset for future projects? (y/N) (→N)
```

## ローカルサーバー立ち上げ
```
$ cd project
$ npm run serve
```
