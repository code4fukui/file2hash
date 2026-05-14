# file2hash

ファイルのハッシュを計算するシンプルなクライアントサイドのウェブアプリケーションです。ファイルをドラッグ＆ドロップするだけで、SHA-512、SHA-256、SHAKE-128、MD5のハッシュを瞬時に生成できます。すべての処理はお使いのブラウザ内でローカルに行われ、ファイルがアップロードされることはありません。

## デモ

**[ライブデモ](https://code4fukui.github.io/file2hash/)**

## 機能

- **複数のアルゴリズム:** SHA-512、SHA-256、SHAKE-128 (128ビット)、MD5のハッシュを計算します。
- **複数のフォーマット:** 各ハッシュをBase32およびBase16（16進数）の両方の形式で表示します。
- **ファイル情報:** 入力ファイルのサイズをバイト単位で表示します。
- **簡単な操作:** シンプルなドラッグ＆ドロップのインターフェースです。
- **セキュア＆プライバシー:** すべての計算はクライアントサイドで行われます。ファイルがサーバーにアップロードされることはありません。

## 使い方

1. [デモサイト](https://code4fukui.github.io/file2hash/)にアクセスします。
2. ページ内の任意の場所にファイルを1つドラッグ＆ドロップします。
3. ファイルサイズと計算されたハッシュが、対応するテキストフィールドに即座に表示されます。

## 依存ライブラリ

このツールは以下のオープンソースライブラリを使用して構築されています:

- [SHA512](https://github.com/code4fukui/SHA512)
- [SHA256](https://github.com/code4fukui/SHA256)
- [SHAKE128(SHA3)](https://github.com/code4fukui/SHA3)
- [MD5](https://github.com/code4fukui/MD5)
- [Base32](https://github.com/code4fukui/Base32)
- [Base16](https://github.com/code4fukui/Base16)

## ライセンス

MIT License — 詳細は [LICENSE](LICENSE) を参照してください。
