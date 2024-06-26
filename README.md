# excel-to-markdown-table README

This VSCode extension converts Excel data to Markdown table format. Available through command `Excel to Markdown table` and keyboard shortcut `Shift+Alt+V`.

![excel-to-markdown-table](https://user-images.githubusercontent.com/1297882/35767301-2fd0c490-08ea-11e8-89d7-933238fed3f2.gif)

Optionally align columns by prepending the headers with `^[lcr]` for left, center and right alignment. E.g `^lHeader` for left aligning the columns named *Header*.

Based on https://github.com/thisdavej/copy-excel-paste-markdown and the work of @jonmagic and @thisdavej

## Contributors
* @deshorsley for bug fix and test coverage!
* @tylerhaigh for refactoring and test coverage!
* @usagi for new line handling and refactoring!
* @trackds for migrating to internal VSCode clipboard API


## Build / Install
- typescriptをインストールする
    `% npm install typescript`
- 依存パッケージインストール
    `% npm install`
- vsixパッケージ作成
    `% npx vsce package`
- vsixパッケージをインストールする
    `% code --install-extension excel-to-markdown-table-1.3.1.vsix --profile Document`

## Known Issues
* None
