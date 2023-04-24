## Markdownとは

Markdownは書式づけられた要素を平文のドキュメントに追加できる、軽量なマークアップ言語です。[John Gruber](https://daringfireball.net/projects/markdown/)によって2004年に作成され、Markdownは今や世界でも有数の人気を誇るマークアップ言語です。

Markdownを使うことは[WYSIWYG](https://ja.wikipedia.org/wiki/WYSIWYG)エディターを使うこととは異なります。Microsoft Wordのようなアプリケーションでは、 ボタンをクリックして単語やフレーズをフォーマットすると、すぐに表示が変わります。Markdownはそうではありません。Markdownでは、Markdownの構文をテキストに追加することで、単語やフレーズをどのように表示させるかを示すことができます。

例えば、見出しを示すときには、見出しの前にシャープを追加します （例： `# 見出し1`）。フレーズを太字にするには、フレーズの前後にアスタリスクを2つ追加します （例： `**このテキストは太字です**`）。特にあなたがWWYSIWYGアプリケーションに慣れている場合には、Markdownの構文に慣れるのには時間がかかるかもしれません。下のスクリーンショットは[Visual Studio Codeコードエディター](/tools/vscode/)でMarkdownファイルがどのように表示されるかを示しています。

{% include image.html file="/assets/images/vscode.png" alt="Markdown file in the Visual Studio Code text editor" %}

テキストエディターを使うことで、平文のテキストファイルにMarkdownで書式づけされた要素を追加することができます。macOSやWindows、Linux、iOS、Android向けのたくさんのMarkdown用アプリケーションを使うこともできます。Markdownを書くために設計されたwebアプリケーションもいくつかあります。

お使いのアプリケーションによりますが、リアルタイムでフォーマットされたドキュメントをプレビューできないこともあるでしょう。でも問題ありません。[Gruberによると](https://daringfireball.net/projects/markdown/)、Markdownの構文は読みやすく、邪魔にならないので、もしレンダリングされていなかったとしても、Markdownファイルのテキストを読み取ることができます。

> Markdownのフォーマット構文の設計目標の最優先事項は、可能な限り読みやすくすることです。Markdownでフォーマットされた文書は、タグやフォーマットの指示でマークアップされたように見えることなく、プレーンテキストとしても公開できるべきという考え方です。
