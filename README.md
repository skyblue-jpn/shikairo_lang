<h1 align="center">Welcome to shikairo_lang 👋</h1>
<p>
  <a href="https://github.com/skyblue-jpn/shikairo_lang/blob/main/README.md" target="_blank">
    <img alt="Documentation" src="https://img.shields.io/badge/documentation-yes-brightgreen.svg" />
  </a>
  <a href="https://github.com/skyblue-jpn/shikairo_lang/blob/main/LICENSE" target="_blank">
    <img alt="License: MIT License" src="https://img.shields.io/badge/License-MIT License-yellow.svg" />
  </a>
</p>

> シカ部のためのプログラミング言語

### 🏠 [Homepage](https://github.com/skyblue-jpn/shikairo_lang)

## Author

👤 **skyblue-jpn**

-   Github: [@skyblue-jpn](https://github.com/skyblue-jpn)

## About

アニメ「しかのこのこのここしたんたん」とプログラミング言語 "Nyaruko" "Kemono" にインスパイアされて作られたプログラミング言語です。
[r-fxxk](https://github.com/masarakki/r-fxxk) を用いて作成されました。
作成にあたっての取り組みは Qiita に記載しています。

## Spec

Brainfuck 系言語です。

-   `しか` データポインタを 1 進める
-   `こし` データポインタを 1 戻す
-   `のこ` データポインタの示す値を 1 増やす
-   `たん` データポインタの示す値を 1 減らす
-   `ぬーん` データポインタの示す値を出力する
-   `ぬぅん` 入力された値をデータポインタの示すバイトに代入する
-   `ぬん。` データポインタの示す値が 0 ならば，対応する次の`]`までジャンプする
-   `ぬん！` データポインタの示す値が 0 でなければ，対応する前の`[`までジャンプする

それ以外の文字や改行は全て無視されます。

## Sample

```hello.deer
のこのこのこのこのこのこのこのこのこのこ
ぬん。
しかのこのこのこ
しかのこのこのこのこのこのこのこ
しかのこのこのこのこのこのこのこのこのこのこ
しかのこのこのこのこのこのこのこのこのこ
しかのこのこのこのこのこのこのこのこのこのこのこ
しかのこのこのこのこのこのこのこのこのこのこ
こしこしこしこしこしこしたん
ぬん！
しかしかのこのこぬーん
しかのこぬーん
のこのこのこのこのこのこのこぬーんぬーん
のこのこのこぬーん
こしこしのこのこぬーん
しかしかしかたんたんたんぬーん
こしぬーん
しかしかのこのこのこのこぬーん
こしこしたんたんたんぬーん
しかしかしかぬーん
```

_execute_

> ./shikairo hello.deer

_output_

> Hello World

## SEE ALSO

<http://ja.wikipedia.org/wiki/Brainfuck>

## Show your support

Give a ⭐️ if this project helped you!

## 📝 License

Copyright © 2024 [skyblue-jpn](https://github.com/skyblue-jpn).<br />
This project is [MIT License](https://github.com/skyblue-jpn/shikairo_lang/blob/main/LICENSE) licensed.

---

_This README was generated with ❤️ by [readme-md-generator](https://github.com/kefranabg/readme-md-generator)_
