---
layout: default
title: Markdown早見表
description: Markdownの構文の早見表です。
last_modified_at: 2021-12-05
---

## 概要

このMarkdown早見表は全てのMarkdown構文要素の概要を簡単にを説明します。全てのエッジケースまでカバーすることはできないので、各要素についてさらに情報が必要な場合は、[basic syntax](/basic-syntax)と[extended syntax](/extended-syntax)リファレンスガイドを参照してください。

## 基本構文

これらはJohn Gruberのオリジナルデザインドキュメントに記載されている要素です。全てのMarkdownアプリケーションはこれらの要素に対応しています。

<table class="table table-bordered">
  <thead class="thead-light">
    <tr>
      <th>要素</th>
      <th>Markdown構文</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td><a href="/basic-syntax/#headings">見出し</a></td>
      <td><code># H1<br>
          ## H2<br>
          ### H3</code></td>
    </tr>
    <tr>
      <td><a href="/basic-syntax/#bold">太字</a></td>
      <td><code>**太字のテキスト**</code></td>
    </tr>
    <tr>
      <td><a href="/basic-syntax/#italic">斜体</a></td>
      <td><code>*イタリックのテキスト*</code></td>
    </tr>
    <tr>
      <td><a href="/basic-syntax/#blockquotes-1">ブロッククォート</a></td>
      <td><code>> ブロッククォート</code></td>
    </tr>
    <tr>
      <td><a href="/basic-syntax/#ordered-lists">順序付きリスト</a></td>
      <td><code>
        1. 一つ目のアイテム<br>
        2. 二つ目のアイテム<br>
        3. 三つ目のアイテム<br>
      </code></td>
    </tr>
    <tr>
      <td><a href="/basic-syntax/#unordered-lists">順序なしリスト</a></td>
      <td>
        <code>
          - 一つ目のアイテム<br>
          - 二つ目のアイテム<br>
          - 三つ目のアイテム<br>
        </code>
      </td>
    </tr>
    <tr>
      <td><a href="/basic-syntax/#code">コード</a></td>
      <td><code>`code`</code></td>
    </tr>
    <tr>
      <td><a href="/basic-syntax/#horizontal-rules">水平罫線</a></td>
      <td><code>---</code></td>
    </tr>
    <tr>
      <td><a href="/basic-syntax/#links">リンク</a></td>
      <td><code>[タイトル](https://www.example.com)</code></td>
    </tr>
    <tr>
      <td><a href="/basic-syntax/#images-1">画像</a></td>
      <td><code>![代替テキスト](image.jpg)</code></td>
    </tr>
  </tbody>
</table>

## 拡張構文

これらの要素は基本構文を追加機能で拡張します。全てのMarkdownアプリケーションが対応しているわけではありません。

<table class="table table-bordered">
  <thead class="thead-light">
    <tr>
      <th>要素</th>
      <th>Markdown構文</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td><a href="/extended-syntax/#tables">テーブル</a></td>
      <td><code>
          | 要素         | 説明        |<br>
          | ----------- | ----------- |<br>
          | 見出し       | タイトル     |<br>
          | 段落         | テキスト     |
      </code></td>
    </tr>
    <tr>
      <td><a href="/extended-syntax/#fenced-code-blocks">囲まれたコードブロック</a></td>
      <td><code>```<br>
      {<br>
      &nbsp;&nbsp;"firstName": "John",<br>
      &nbsp;&nbsp;"lastName": "Smith",<br>
      &nbsp;&nbsp;"age": 25<br>
      }<br>
      ```
      </code></td>
    </tr>
    <tr>
      <td><a href="/extended-syntax/#footnotes">脚注</a></td>
      <td><code>
        脚注付きの文章を紹介します。[^1]<br><br>
        [^1]: これは脚注です。
      </code></td>
    </tr>
    <tr>
      <td><a href="/extended-syntax/#heading-ids">見出しID</a></td>
      <td><code>### 偉大な見出し {#custom-id}</code></td>
    </tr>
    <tr>
      <td><a href="/extended-syntax/#definition-lists">説明リスト</a></td>
      <td><code>
        用語<br>
        : 定義
      </code></td>
    </tr>
    <tr>
      <td><a href="/extended-syntax/#strikethrough">取り消し線</a></td>
      <td><code>~~地球は平面。~~</code></td>
    </tr>
    <tr>
      <td><a href="/extended-syntax/#task-lists">Todoリスト</a></td>
      <td><code>
        - [x] プレスリリースを書く<br>
        - [ ] ウェブサイトを更新する<br>
        - [ ] マスコミに連絡する
      </code></td>
    </tr>
    <tr>
      <td><a href="/extended-syntax/#emoji">絵文字</a><br>（<a href="/extended-syntax/#copying-and-pasting-emoji">Copying and Pasting Emoji</a>も参照してください）</td>
      <td><code>
        超楽しい！ :joy:
      </code></td>
    </tr>
    <tr>
      <td><a href="/extended-syntax/#highlight">ハイライト</a></td>
      <td><code>
        とても ==大事な単語== をハイライトしたい。
      </code></td>
    </tr>
    <tr>
      <td><a href="/extended-syntax/#subscript">添え字</a></td>
      <td><code>
        H~2~O
      </code></td>
    </tr>
    <tr>
      <td><a href="/extended-syntax/#superscript">上付き文字</a></td>
      <td><code>
        X^2^
      </code></td>
    </tr>
  </tbody>
</table>

## ダウンロード

この早見表を<a href="/assets/markdown-cheat-sheet.md" download="markdown-cheat-sheet.md">Markdownファイルとしてダウンロード</a>できます。お好きなMarkdownアプリケーションで使用してください。
