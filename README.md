# Open Weather API を使った気象情報サイト

## 仕様

TailwindCss + Reactで作成

## 前提

1. Open Weather のサイトでアカウント作成
2. ログイン
3. API キーを取得

4. プロジェクトのルートディレクトリに.env ファイル作成

.envに以下記述

```javascript
REACT_APP_OW_API_URL = 'http://api.openweathermap.org/data/2.5'
REACT_APP_OW_API_KEY = 'YOUR_API_KEY(example: "8888ef")'
REACT_APP_OW_ICON_URL = 'https://openweathermap.org/img/w'
```
