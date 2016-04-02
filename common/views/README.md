# Views

以下、レンダリングに必要なコンポーネントなどを設置するディレクトリ。
*※コンポーネントはReact.jsの扱うコンポーネントの事。ここではレイヤーごとにディレクトリでまとめている。*
*※コンポーネントに関連するCSSは同じディレクトリに置く。*

- utils: Cssの変数関連やVendorのコード類、どのコンポーネント群にも関連できそうな共通関数など
- ui-parts: UIデザイン都合のUI部品類のコンポーネント
  - Form
  - Heading
  - Button
  - Anchor
  - etc...
- components: 単一概念（機能）のコンポーネント
- aggregations: 集約（コンポーネントのWrapper的なまとめ、get/postなどを担う）のコンポーネント
- screens: 遷移を伴う画面のコンポーネント
