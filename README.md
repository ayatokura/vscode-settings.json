# Visual Studio Code ワークスペースの設定方法
Visual Studio Codeは、**settings.json**というJSON形式で記述されるファイルの中で設定を行うことができます。　　

## Settngs.jsonについて
VSCodeの「**ファイル(F)**」メニュー→「**基本設定(P)**」→「**設定(S)**」を選択すると左側に**デフォルト設定リスト**、右側に**Settings.json**が表示されます。設定を変更したい場合には、Settings.jsonファイルを編集し保存して適用します。

## Settings.json格納先
お使いの環境によって格納先が異なります。  
* **Windows** %APPDATA%\Code\User\settings.json  
* **Mac** $HOME/Library/Application Support/Code/User/settings.json  
* **Linux** $HOME/.config/Code/User/settings.json

# ここに格納しているSettings.jsonファイルについて
VSCodeのバージョンによって **Setting.json** で定義できる設定内容や、記述方法が異なる場合があります。過去のデフォルト設定を見直したい場合や、どんな設定が行えるのか閲覧したい場合などに参考にしてください。

# 記述方法
1. Setting.jsonを起動する　　
2. 設定したい項目をデフォルト設定リストからコピペする  
※例えばフォントサイズを大きくしたい場合には **"editor.fontSize": 18** をコピペする。この時に **{ }** (ブレイス/中括弧) も忘れずに。
>{  
>   "editor.fontSize": 18  
>}

3. 保存する

## 参考文献
[Visual Studio Code User and Workspace Settings](https://code.visualstudio.com/docs/getstarted/settings)
