---
title: 見出し
syntax-id: headings
syntax-summary: |
  # H1
  ## H2
  ### H3
description: "見出しを作成するには、シャープ(`#`)を単語やフレーズの前に付けます。シャープの数は見出しレベルに対応させる必要があります。例えばレベル3の見出し(`<h3>`)を作成するには、シャープを3つ使います(例：`### 見出し`)。"
examples:
  - markdown: "# 見出しレベル1"
    html: "<h1>見出しレベル1</h1>"
  - markdown: "## 見出しレベル2"
    html: "<h2>見出しレベル2</h2>"
  - markdown: "### 見出しレベル3"
    html: "<h3>見出しレベル3</h3>"
  - markdown: "#### 見出しレベル4"
    html: "<h4>見出しレベル4</h4>"
  - markdown: "##### 見出しレベル5"
    html: "<h5>見出しレベル5</h5>"
  - markdown: "###### 見出しレベル6"
    html: "<h6>見出しレベル6</h6>"
additional-examples:
  - name: "h1代替構文"
    description: "Alternatively, on the line below the text, add any number of == characters for heading level 1."
    markdown: |
      Heading level 1
      ===============
    html: "<h1>Heading level 1</h1>"
  - name: "Alternative H2 Syntax"
    description: "Alternatively, on the line below the text, add any number of -- characters for heading level 2."
    markdown: |
      Heading level 2
      ---------------
    html: "<h2>Heading level 2</h2>"
---

見出しを作成するには、シャープ(`#`)を単語やフレーズの前に付けます。シャープの数は見出しレベルに対応させる必要があります。例えばレベル3の見出し(`<h3>`)を作成するには、シャープを3つ使います(例：`### 見出し`)。

<table class="table table-bordered">
  <thead class="thead-light">
    <tr>
      <th>Markdown</th>
      <th>HTML</th>
      <th>描画された出力</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td><code class="highlighter-rouge"># 見出しレベル1</code></td>
      <td><code class="highlighter-rouge">&lt;h1&gt;見出しレベル1&lt;/h1&gt;</code></td>
      <td><h1 class="no-anchor" data-toc-skip>見出しレベル1</h1></td>
    </tr>
    <tr>
      <td><code class="highlighter-rouge">## 見出しレベル2</code></td>
      <td><code class="highlighter-rouge">&lt;h2&gt;見出しレベル2&lt;/h2&gt;</code></td>
      <td><h2 class="no-anchor" data-toc-skip>見出しレベル</h2></td>
    </tr>
    <tr>
      <td><code class="highlighter-rouge">### 見出しレベル3</code></td>
      <td><code class="highlighter-rouge">&lt;h3&gt;見出しレベル3&lt;/h3&gt;</code></td>
      <td><h3 class="no-anchor" data-toc-skip>見出しレベル3</h3></td>
    </tr>
    <tr>
      <td><code class="highlighter-rouge">#### 見出しレベル4</code></td>
      <td><code class="highlighter-rouge">&lt;h4&gt;見出しレベル4&lt;/h4&gt;</code></td>
      <td><h4 class="no-anchor">見出しレベル4</h4></td>
    </tr>
    <tr>
      <td><code class="highlighter-rouge">##### 見出しレベル5</code></td>
      <td><code class="highlighter-rouge">&lt;h5&gt;見出しレベル5&lt;/h5&gt;</code></td>
      <td><h5 class="no-anchor">見出しレベル5</h5></td>
    </tr>
    <tr>
      <td><code class="highlighter-rouge">###### 見出しレベル6</code></td>
      <td><code class="highlighter-rouge">&lt;h6&gt;見出しレベル6&lt;/h6&gt;</code></td>
      <td><h6 class="no-anchor">見出しレベル6</h6></td>
    </tr>
  </tbody>
</table>

### 代替構文

`#`の代わりに、テキストの下の行に、いくつかの`==`を追加し、レベル1の見出しを、または`--`を追加してレベル2の見出しを作成することができます。

<table class="table table-bordered">
  <thead class="thead-light">
    <tr>
      <th>Markdown</th>
      <th>HTML</th>
      <th>描画された出力</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td><code class="highlighter-rouge">見出しレベル1<br/>===============</code></td>
      <td><code class="highlighter-rouge">&lt;h1&gt;見出しレベル1&lt;/h1&gt;</code></td>
      <td><h1 class="no-anchor" data-toc-skip>見出しレベル1</h1></td>
    </tr>
    <tr>
      <td><code class="highlighter-rouge">見出しレベル2<br/>---------------</code></td>
      <td><code class="highlighter-rouge">&lt;h2&gt;見出しレベル2&lt;/h2&gt;</code></td>
      <td><h2 class="no-anchor" data-toc-skip>見出しレベル2</h2></td>
    </tr>
  </tbody>
</table>

### 見出しのベストプラクティス

Markdownアプリケーションはシャープ(`#`)と見出しの名前の間にスペースがないと見出しとして認識しません。互換性のために、常にシャープと見出しの間にはスペースを入れてください。

<table class="table table-bordered">
  <thead class="thead-light">
    <tr>
      <th>✅&nbsp; Do this</th>
      <th>❌&nbsp; Don't do this</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>
        <code class="highlighter-rouge">
          # Here's a Heading<br><br>
        </code>
      </td>
      <td>
        <code class="highlighter-rouge">
          #Here's a Heading
        </code>
      </td>
    </tr>
  </tbody>
</table>

You should also put blank lines before and after a heading for compatibility.

<table class="table table-bordered">
  <thead class="thead-light">
    <tr>
      <th>✅&nbsp; Do this</th>
      <th>❌&nbsp; Don't do this</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>
        <code class="highlighter-rouge">
        Try to put a blank line before...<br><br>

        # Heading<br><br>

        ...and after a heading.
        </code>
      </td>
      <td>
        <code class="highlighter-rouge">
        Without blank lines, this might not look right.<br>
        # Heading<br>
        Don't do this!
        </code>
      </td>
    </tr>
  </tbody>
</table>