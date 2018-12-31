# 電子ペーパー

富士通およびソニーからOEMで販売されているリンフィニー[^1]の電子ペーパーについての解析及びライブラリです。

[^1]: ソニーとイーインクの合弁会社、旧称は元力テクノロジー。

**現在未完成です。完成時期は未定です。**

## 対応機器

現在の所、富士通製電子ペーパーFMV-DPP02でのみ確認しています。他の機器は持っていないので、検証できません。違う所があったらIssueに投げてください。

* [ ] FMV-DPP01 富士通製 A4サイズ 白
* [x] FMV-DPP02 富士通製 A5サイズ 白
* [ ] DPT-RP1 ソニー製 A4サイズ 白
* [ ] DPT-CP1 ソニー製 A5サイズ 白

## フォルダ構成

* [doc](doc) ドキュメント
* [lib](lib) Ruby ライブラリ
* [bin](bin) Ruby ツール
* [tool](tool) 解析用のツール

## 免責事項およびサポート

ドキュメント内容およびライブラリはすべて無保証です。信頼性の担保はありません。これらによって機器の故障等の損害が発生した場合、作者および電子ペーパー販売元は一切の責任を負わない事とします。

ここのドキュメント内容およびライブラリについて電子ペーパー販売元に問い合わせをしないでください。問題はここのIssueへ投げてください。

## 謝辞

この調査にあたり、[dpt-rp1-py](https://github.com/janten/dpt-rp1-py)のソースコードが大いに参考になりました。

## TODO

* API調査と整理
    * [ ] 検索と基本情報取得
    * [ ] クライアント登録
    * [ ] 認証処理
    * [ ] 機器情報取得
    * [ ] ディレクトリとファイルの操作
    * [ ] 機器設定変更
* プログラム
    * [ ] Ruby ライブラリ (Ruby)
    * [ ] CUI ツール (Ruby)
    * [ ] Cインターフェースライブラリ (Go)
    * [ ] Webベース管理サーバー (Go)
* ツール
    * [x] 通信データ閲覧ツール
    * [ ] ツール動作用Vagrantfile
