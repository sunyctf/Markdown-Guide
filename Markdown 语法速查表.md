# Markdown 语法速查表

Markdown 语法参考手册 / 速查表。

## 总览

此 Markdown 语法速查表提供了所有 Markdown 语法元素的快速参考。但是此速查表无法涵盖所有极限用法，因此，如果您需要某些语法元素的详细信息，请参阅我们的 [基本语法](https://www.markdown.xyz/basic-syntax) 和 [扩展语法](https://www.markdown.xyz/extended-syntax) 手册。

## 基本语法

这些是 John Gruber 的原始设计文档中列出的元素。所有 Markdown 应用程序都支持这些元素。

| 元素                                                         | Markdown 语法                              |
| ------------------------------------------------------------ | ------------------------------------------ |
| [标题（Heading）](https://www.markdown.xyz/basic-syntax/#headings) | `# H1## H2### H3`                          |
| [粗体（Bold）](https://www.markdown.xyz/basic-syntax/#bold)  | `**bold text**`                            |
| [斜体（Italic）](https://www.markdown.xyz/basic-syntax/#italic) | `*italicized text*`                        |
| [引用块（Blockquote）](https://www.markdown.xyz/basic-syntax/#blockquotes-1) | `> blockquote`                             |
| [有序列表（Ordered List）](https://www.markdown.xyz/basic-syntax/#ordered-lists) | `1. First item2. Second item3. Third item` |
| [无序列表（Unordered List）](https://www.markdown.xyz/basic-syntax/#unordered-lists) | `- First item- Second item- Third item`    |
| [代码（Code）](https://www.markdown.xyz/basic-syntax/#code)  | ``code``                                   |
| [分隔线（Horizontal Rule）](https://www.markdown.xyz/basic-syntax/#horizontal-rules) | `---`                                      |
| [链接（Link）](https://www.markdown.xyz/basic-syntax/#links) | `[title](https://www.example.com)`         |
| [图片（Image）](https://www.markdown.xyz/basic-syntax/#images) | `![alt text](image.jpg)`                   |

## 扩展语法

这些元素通过添加额外的功能扩展了基本语法。但是，并非所有 Markdown 应用程序都支持这些元素。

| 元素                                                         | Markdown 语法                                                |
| ------------------------------------------------------------ | ------------------------------------------------------------ |
| [表格（Table）](https://www.markdown.xyz/extended-syntax/#tables) | `| Syntax | Description || ----------- | ----------- || Header | Title || Paragraph | Text |` |
| [代码块（Fenced Code Block）](https://www.markdown.xyz/extended-syntax/#fenced-code-blocks) | ````{ "firstName": "John", "lastName": "Smith", "age": 25}```` |
| [脚注（Footnote）](https://www.markdown.xyz/extended-syntax/#footnotes) | `Here's a sentence with a footnote. [^1][^1]: This is the footnote.` |
| [标题编号（Heading ID）](https://www.markdown.xyz/extended-syntax/#heading-ids) | `### My Great Heading {#custom-id}`                          |
| [定义列表（Definition List）](https://www.markdown.xyz/extended-syntax/#definition-lists) | `term: definition`                                           |
| [删除线（Strikethrough）](https://www.markdown.xyz/extended-syntax/#strikethrough) | `~~The world is flat.~~`                                     |
| [任务列表（Task List）](https://www.markdown.xyz/extended-syntax/#task-lists) | `- [x] Write the press release- [ ] Update the website- [ ] Contact the media` |
| [Emoji](https://www.markdown.xyz/extended-syntax/#emoji) (see also [Copying and Pasting Emoji](https://www.markdown.xyz/extended-syntax/#copying-and-pasting-emoji)) | `That is so funny! :joy:`                                    |
| [Highlight](https://www.markdown.xyz/extended-syntax/#highlight) | `I need to highlight these ==very important words==.`        |
| [Subscript](https://www.markdown.xyz/extended-syntax/#subscript) | `H~2~O`                                                      |
| [Superscript](https://www.markdown.xyz/extended-syntax/#superscript) | `X^2^`                                                       |

## 下载

你可以 [下载此速查表的 Markdown 源码文件](https://www.markdown.xyz/assets/markdown-cheat-sheet.md)，并在你自己的 Markdown 程序中使用。