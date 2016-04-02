# Views

以下、レンダリングに必要なコンポーネントなどを設置するディレクトリ。
*※コンポーネントはReact.jsの扱うコンポーネントの事。ここではレイヤーごとにディレクトリでまとめている。*
*※コンポーネントに関連するCSSは同じディレクトリに置く。*

- utils
  - styles: Cssの変数関連やVendorのコード類
  - scripts: コンポーネントにはできない共通関数など（サービス層的な位置づけ）
  - images: 画像・フォント・favicon類
    - svg
    - png
    - gif
    - jpeg
    - favicon
    - font
- ui-parts: UIデザイン都合のUI部品類のコンポーネント
  - Form
  - Heading
  - Button
  - Anchor
  - etc...
- components: 単一概念（機能）のコンポーネント
- aggregations: 集約（コンポーネントのWrapper的なまとめ、get/postなどを担う）のコンポーネント
- screens: 遷移を伴う画面のコンポーネント
