# How to use the PlantUML
## 環境構築
### 前提
 - Javaがインストール済み

### Graphvizのインストール
```bash
brew install graphviz
```

### PlantUMLのインストール
 1. 拡張機能からPlantUML を選択し、[インストール]を押す
 2. インストール完了後に[再度読み込む]を押して Visual Studio Code を再起動する

## 使い方
#### プレビューの仕方
Alt + D

#### 画像エクスポート
1. Command + Shift + P
2. PlantUML: ファイル内のダイアグラムをエクスポートを選択
3. pngを選択

#### エクスポート先の設定
settings.jsonに下記を記載しておくと、エクスポート先が設定できます
```
    "plantuml.exportOutDir": "output",
    "plantuml.diagramsRoot": "/",
    "plantuml.exportSubFolder": false
```

## シーケンス図書き方
http://yohshiy.blog.fc2.com/blog-entry-153.html

