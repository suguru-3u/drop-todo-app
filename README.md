package.json の生成
npm init

tsconfig.json の生成
npx tsc --init

■ コードを複数のファイルに分割する方法　　
・namespace とファイルのバンドリング
namespace 構文を使ってコードをグループ化
ファイル単位 or バンドルでのコンパイル

・ES6 import export
ES6 import export 構文の利用
ファイル単位のコンパイル
サードパティーツールでのバンドリング

・Webpack
複数のファイルをひとつ（バンドラ）にまとめることができる。
→ それにより HTTP リクエストを行うことが少なるなり、動作が速くなる
　 また、ビルドやコードの最適化（ファイルのサイズを小さくする）を行うことができる。
