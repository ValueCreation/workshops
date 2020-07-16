# 環境構築
ArcGIS 開発者のための最新アプリ開発塾 2020 にご参加する方は以下手順に沿って環境構築をお願いします。

## ArcGIS プラットフォームを活用したデータ構築
### データの配置
1. [ハンズオン用データ](https://github.com/EsriJapan/workshops/blob/master/20200825_app-development-hands-on/HandsOn_Data.zip)をダウンロードし、解凍してください。

2. 解凍したデータをDドライブ直下に配置してください（D:\EJWater となるように配置してください）。

   ※Cドライブに配置していただいても構いませんが、配置先にあわせて EJWater フォルダにある「project.config」の4,6行目を書き換えて頂く必要があります。

   <img src="./img/data_config2.png" width="500px">

3. 「project.config」ファイルの 5行目の value をご自身の環境に合わせて変更してください（例：C:\Program Files\ArcGIS\Pro\bin\Python\envs\arcgispro-py3\pythonw.exe）

   <img src="./img/data_config.png" width="500px">

### ArcGIS Pro の環境設定
1. ArcGIS Pro をインストールしてください。

   ArcGIS Pro をお持ちでない方は[トライアルライセンス](https://www.esrij.com/form/arcgis/trials/)を配布していますので、そちらを使ってインストールしてください。ArcGIS Pro をすでにお持ちの方はそちらをご使用いただいて構いません（ただし、バージョンは2.5にしていただく必要があります）。

2. [ArcGIS Pro SDK](https://pro.arcgis.com/en/pro-app/sdk/) で作成されたこちらの[アドイン](https://github.com/EsriJapan/workshops/blob/master/20200825_app-development-hands-on/Environment/Addin.zip)をインストールしてください。

3. [アドインファイル](https://github.com/EsriJapan/workshops/blob/master/20200825_app-development-hands-on/Environment/Addin.zip)をダウンロードし、解凍してください。

4. アドインファイルをダブルクリックし、インストールしてください。

   <img src="./img/prosdk.png" width="500px">

5. D:\EJWater\EJWater.aprx をダブルクリックし、起動確認をしてください。

   <img src="./img/pro_boot.png" width="500px">

6. 「オフラインデータ」タブが存在し、リボン上のアイテムが活性状態であることを確認してください。

   <img src="./img/pro_addin.png" width="500px">

### ArcGIS API for Python の環境設定

## ArcGIS プラットフォームを活用した現地調査アプリ開発ハンズオン

### ArcGIS Runtime SDK for .NET の環境設定

## ArcGIS プラットフォームを活用したWebアプリ開発ハンズオン

### ArcGIS API for JavaScript の環境設定
1. [Visual Studio Code](https://code.visualstudio.com/) をインストールしてください。

2. [Google Chrome](https://www.google.com/chrome/?brand=CHBD&gclid=EAIaIQobChMIqszkqJLO6gIVCFdgCh1CbgnjEAAYASAAEgIfY_D_BwE&gclsrc=aw.ds)(最新バージョン)をインストールしてください。