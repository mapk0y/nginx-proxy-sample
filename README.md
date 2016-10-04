docker で nginx の proxy 環境を docker-compose で立てるサンプル


#### 調査が必要なこと

- [ ] アプリ側（python）で SIGTERM が無視される。これは pid 1 だから？ pid 1 の場合は、python のインタプリタのシグナルの制御の設定次第のはず。ruby は機能する。
- [ ] アプリ側のログが表示されれない。strace しても stdout に出力していない。手で動かした時は出力される。tty?

