# 令和6年能登半島地震 震央分布マップ
令和6年能登半島地震に関連して気象庁の震央分布をMapLibre GL JSで表示するデモサイトです。

## Public Website
https://shi-works.github.io/noto-hanto-earthquake-2024-jma-epicenter-map-on-maplibre-gl-js/

![image](https://github.com/shi-works/noto-hanto-earthquake-2024-jma-epicenter-map-on-maplibre-gl-js/assets/71203808/abf34d73-c0d2-41ae-94d9-c3d8aec400eb)

## Data Source
### 気象庁
- 震央分布データ（GeoJSON形式）
    - 出典：https://www.jma.go.jp/bosai/map.html#9/37.437/137.255/&contents=hypo
    - ライセンス：[気象庁ホームページ利用規約](https://www.jma.go.jp/jma/kishou/info/coment.html)

### 背景地図及び地形データ
- 国土地理院 最適化ベクトルタイル
    - 出典：https://github.com/gsi-cyberjapan/optimal_bvmap
    - ライセンス：[国土地理院コンテンツ利用規約](https://www.gsi.go.jp/kikakuchousei/kikakuchousei40182.html)に従い、出典明示により、転載も含め使用可
- 国土地理院 地理院タイル（デジタル標高地形図：【技術資料D1-No.959】）
    - 出典：https://maps.gsi.go.jp/development/ichiran.html#digiele
    - ライセンス：[国土地理院コンテンツ利用規約](https://www.gsi.go.jp/kikakuchousei/kikakuchousei40182.html)に従い、出典明示により、転載も含め使用可
- 産業技術総合研究所 シームレス標高タイル（統合DEM）
    - 出典：https://tiles.gsj.jp/tiles/elev/tiles.html
    - ライセンス：「[産総研地質調査総合センターウェブサイト利用規約](https://www.gsj.jp/license/license.html)」に従い、商用を含む自由な二次利用が可能です。この規約はCC BY 4.0と互換です。
