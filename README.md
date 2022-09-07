# react vite template

### 触るファイルは基本 components 内で完結いたします

- hooks ここではプラグインや機能を格納しています
  - media.ts 　 styled-components の media を書いています
  - ScrollAnimation.tsx で囲むとふわっと表示されます
- Layout 文字どうり Layout にまつわるものを格納してください
  - Section,Container は props で data-top 等受け取り余白を決めれます
- page page コンポーネントを入れてください
- parts コンポーネント設計として最小もしくは大きいまとまり,単一などを格納してください
- Router react-router-dom を格納しています。必要に応じて追加してください
- tools コンポーネント設計としてある程度があるものを格納してください

### style

- styled-components
- tailwindcss

### 画像

public は以下の images で管理してください
圧縮機能は入れています

### seo

可変するものの作り方がわからなかったので必要タグは index.html に直接書いてください

### その他

ホットリロードに対応しています

必要に応じて追加してください
