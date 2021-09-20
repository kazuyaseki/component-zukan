# Button

## どんな時に使うか

Use the button component to help users carry out an action like starting an application or saving their information.

何らかのアクション(Form の送信, オブジェクトの新規作成など)を実行する時にユーザがクリックする対象として使う。

## どんな状態があるか

- focus
- hover
- active
- disabled
- loading


## どんな分類があるか

- primary
- secondary
- neutral
- danger

## UI パターン

高さは 32px - 48px ぐらいの幅で設定されていることが多い。

### 最近のよく見るフラットデザインパターン


### 微妙に３D

## Link について
よくあるのが見た目は Button で Link として振る舞うパターン。
これに対しては次の点から Link は区別したコンポーネントとしてデザインした方がいい

- 役割が違い、遷移はアクションでは無いためユーザに正しい印象を与えるため
- 実装的にも一つのコンポーネントで二つの役割を担おうとすると可読性が下がるため


## 参考リンク
https://design-system.service.gov.uk/components/button/
https://uxdesign.cc/button-design-user-interface-components-series-85243b6736c7