#  Java プロジェクトのビルドと実行
### 1. Java ファイルのコンパイル
プロジェクトのルートディレクトリで、以下のコマンドを実行してください:

`javac -d bin src/*.java`

または、文字コードが原因のエラーを回避するために UTF-8 指定でコンパイルする場合:

 `javac -encoding UTF-8 -d bin src/*.java`

- `javac` Java コンパイラ
- `-d bin` コンパイルされた `.class` ファイルを `bin` フォルダに出力.
- `src/*.java`: `src` ディレクトリ内のすべての Java ソースファイルをコンパイル

### 2. コンパイル後の Java プログラムを実行
コンパイルが完了したら、以下のコマンドで Java アプリケーションを実行できます:

`java -cp bin App`

 オプションの説明

- `-cp bin` `bin` ディレクトリをクラスパスとして指定
