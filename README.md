# Parrot
## Summary
* Node.js・Julius・OpenJTalkを使用した、喋ったことをオウム返ししてくれるアプリ
* Linux環境推奨:Debian9.4で動作確認済み

## Usage
* 初回は(通信環境の良い場所で)`npm install`,`npm run setting`を行ってください。
* `npm run server`の後、別の端末で`npm start`を実行するとアプリが起動します。
* マイクに向かって喋り、Julius(`npm run server`を実行している端末)を終了させると、音声が帰ってきます(mei:normal)。

## Bugs
* 時々音声出力に失敗する

## Future Releases
* 実行方法の改善
* アプリの実行時にサーバーも同時に立てるようにする
* Bugの修正

## Requirement
* Node.js : v9.10.1
* npm     : v5.8.0

## License
[MIT](./LICENSE)
