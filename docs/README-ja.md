# Blue Theme by taikun114
[English](https://github.com/taikun114/Blue-Theme-by-taikun114/blob/main/README.md) | **日本語**

![Blue Theme](https://raw.githubusercontent.com/taikun114/Blue-Theme-by-taikun114/main/docs/Blue%20Theme.png)

## スクリーンショット

### ダッシュボード
#### ライト
![Dashboard Light](https://raw.githubusercontent.com/taikun114/Blue-Theme-by-taikun114/main/docs/Dashboard%20Light.png)

#### ダーク
![Dashboard Dark](https://raw.githubusercontent.com/taikun114/Blue-Theme-by-taikun114/main/docs/Dashboard%20Dark.png)

### マップ

#### ライト
![Map Light](https://raw.githubusercontent.com/taikun114/Blue-Theme-by-taikun114/main/docs/Map%20Light.png)

#### ダーク
![Map Dark](https://raw.githubusercontent.com/taikun114/Blue-Theme-by-taikun114/main/docs/Map%20Dark.png)

### ログブック

#### ライト
![Logbook Light](https://raw.githubusercontent.com/taikun114/Blue-Theme-by-taikun114/main/docs/Logbook%20Light.png)

#### ダーク
![Logbook Dark](https://raw.githubusercontent.com/taikun114/Blue-Theme-by-taikun114/main/docs/Logbook%20Dark.png)

### 履歴

#### ライト
![History Light](https://raw.githubusercontent.com/taikun114/Blue-Theme-by-taikun114/main/docs/History%20Light.png)

#### ダーク
![History Dark](https://raw.githubusercontent.com/taikun114/Blue-Theme-by-taikun114/main/docs/History%20Dark.png)

### 開発者ツール

#### ライト
![Developer Tools Light](https://raw.githubusercontent.com/taikun114/Blue-Theme-by-taikun114/main/docs/Developer%20Tools%20Light.png)

#### ダーク
![Developer Tools Dark](https://raw.githubusercontent.com/taikun114/Blue-Theme-by-taikun114/main/docs/Developer%20Tools%20Dark.png)

### 設定

#### ライト
![Configuration Light](https://raw.githubusercontent.com/taikun114/Blue-Theme-by-taikun114/main/docs/Configuration%20Light.png)

#### ダーク
![Configuration Dark](https://raw.githubusercontent.com/taikun114/Blue-Theme-by-taikun114/main/docs/Configuration%20Dark.png)

### プロファイル

#### ライト
![Profile Light](https://raw.githubusercontent.com/taikun114/Blue-Theme-by-taikun114/main/docs/Profile%20Light.png)

#### ダーク
![Profile Dark](https://raw.githubusercontent.com/taikun114/Blue-Theme-by-taikun114/main/docs/Profile%20Dark.png)

## インストール

### 初めてテーマを使用する場合

以下のコードを、お使いの `configuration.yaml` ファイルに追加します（再起動が必要です）。

```yaml
frontend:
  themes: !include_dir_merge_named themes
```
すでに存在している場合は、何もする必要はありません。

### フォントのセットアップ
このテーマで指定されているフォントを使用するには、ダッシュボードの設定からリソースを追加する必要があります。

Home Assistantの`設定` -> `ダッシュボード` -> `リソース`へ行き、以下の設定でリソースを追加してください。

#### URL:
```
https://fonts.googleapis.com/css2?family=Cousine:wght@400;700&family=Inter:ital,opsz,wght@0,14..32,100..900;1,14..32,100..900&family=Noto+Sans+JP:wght@100..900
```

#### リソースの種類:
`Stylesheet`を選択します。

### HACS

1. コミュニティストアを開きます。
2. 右上にあるアイコンをクリックして、`Custom repositories`を開きます。
3. `Repository`セクションに、こちらを追加します： `https://github.com/taikun114/Blue-Theme-by-taikun114`
4. `Type`セクションは、`Theme`を選択して`ADD`をクリックします。
5. `Blue Theme by taikun114`をクリックして`Download`をクリックします。
6. プロファイル設定を開き、ダウンロードしたテーマに変更すれば完了です！

### 手動

1. こちらのテーマファイルをダウンロードします：[Blue-Theme-by-taikun114.yaml](https://raw.githubusercontent.com/taikun114/Blue-Theme-by-taikun114/main/themes/Blue-Theme-by-taikun114.yaml)
2. Home Assistantのコンフィグフォルダにある`themes`フォルダを開き、その中に`Blue-Theme-by-taikun114`という名前のフォルダを作成します。
3. 作成したフォルダ内に、先ほどダウンロードした`Blue-Theme-by-taikun114.yaml`を入れます。
4. Home Assistantの開発者ツールを開き、`YAML設定の再読込`の下にある`すべてのYAML設定`をクリックします。
5. プロファイル設定を開き、ダウンロードしたテーマに変更すれば完了です！

## 重要
このテーマは、[Mushroom](https://github.com/piitaya/lovelace-mushroom) Title Cardの余白を変更します。
Mushroom Title Cardをお使いの場合、レイアウトが少し崩れてしまう可能性がありますので、ご注意ください。

レイアウトが崩れて欲しくない場合は、テーマファイルの`Mushroom Card Specific`にある`Spacing`で指定されているコードを削除してください。

テーマのアップデートを行うと、テーマファイルはリセットされます。
そのため、テーマをアップデートするたびに、同様の手順を繰り返す必要がありますのでご注意ください。
