
WebDAV Client CarotDAV Ver. 1.14.6

概要
	Windows用のWebDAVクライアントです。
	おまけで各種オンラインサービスにアクセスできるかもしれません。
	ローカル用の簡易WebDAVサーバーもつけました。

動作環境
	Windows 2000, XP, 2003, Vista, 2008, 7, 2011, 2012, 8, 10
	要.Net Framework 2.0/4.0
	(IIS6、IIS7、Apache2.2/2.1、その他のサーバーで動作確認)

対応規格等
	WebDAV
	FTP/FTPS
	DropBox / GoogleDrive / OneDrive / Box / SugarSync / AmazonCloudDrive / HubiC / OpenStack Swift
	Host-specific file names
	IMAP
	Unicode正規化(Unicode Standard Annex #15)
	ダウンロード・アップロードレジューム
	自動分割
	暗号化・ファイル検証
	マスターパスワード(XML-Enc)
	TLS1.1/1.2 (.Net4.5以降)
	簡易WebDAVサーバー
	GUI/CUI
	詳細は一次配布サイト(http://rei.to/carodav.html)を参照ください。

インストール方法
	Microsoft Windows Installer用のファイルを含むインストーラー版、
	実行形式をzip形式にまとめたポータブル版の2種類の形で配布しています。
	インストーラー版はMicrosoft Windows Installerを用いてインストールしてください。
	通常はmsiファイルをダブルクリックすればインストールできます。
	ポータブル版は適当な場所に展開し、そのまま利用してください。

使用方法
	直接URLを入力するか、各種設定を保存して使います。
	詳細は一次配布サイト(http://rei.to/carodav.html)を参照ください。

アンインストール方法
	インストーラー版はコントロールパネルから行うか、Windows Installerでアンインストールしてください。
	設定情報も削除したい場合は「%APPDATA%\Rei Software\CarotDAV」を削除してください。

	ポータブル版は実行形式を含むフォルダを削除してください。
	ポータブル版の設定情報は実行形式を含むフォルダに生成されます。

ライセンス・利用料・寄付
	このソフトは無料で利用して構いません。今後有料化の予定もありません。ご自由にお使いください。 
	2次配布、商用利用、改造、リバースエンジニアリングなどもご自由にどうぞ。
	ソースコードは置いていませんが、欲しい人にはお渡しできます。 
	また、寄付を受け付けています。詳細は一次配布サイト(http://rei.to/carodav.html)を参照ください。

連絡先・著作者・一次配布サイト
	http://rei.to/carotdav.html
	Rei HOBARA reichan@white.plala.or.jp
	連絡をする場合、件名に「CarotDAV」の文字列が含まれるようにしてください。

ファイル構成
	インストーラー版
		CarotDAVx.x.x.msi
			インストール用パッケージ。
		readme_ja.txt
			CarotDAVの説明書き。このファイル。日本語。
		readme_en.txt
			CarotDAVの説明書き。英語。
		xxx.xml
			設定のサンプルファイルです。

	ポータブル版
		CarotDAV.exe および *.dll
			CarotDAV実行形式およびライブラリ。
		CarotDAV.exe.config
			CarotDAV.exeの構成ファイル
		CarotDAVC.exe
			CarotDAVのCUI版の実行形式。
		readme_ja.txt
			CarotDAVの説明書き。このファイル。日本語。
		readme_en.txt
			CarotDAVの説明書き。英語。
		xxx.xml
			設定のサンプルファイルです。

	xmlファイルは設定用のサンプルファイルです。インポートして使ってください。
		TeraCloud.xml
			TeraCloud(https://teracloud.jp/)用の設定ファイルです。
		DRiVEE.xml
			DRiVEE(http://www.drivee.jp/)用の設定ファイルです。
		04WebServer.xml
			04WebServer(http://soft3304.net/04WebServer/)用設定ファイルです。
		IIS.xml
			IIS用の設定ファイルです。

	以下のファイルが必須ファイルです。
	それ以外のDLLは各サービス・プロトコルのサポート用です。
	必要なければ削除しても動作します。
		CarotDAV.exe
		CarotDAV.exe.config
		Rei.Com.dll
		Rei.Fs.dll
		Rei.Fs.Webdav.dll
		Rei.Net.HttpServer.dll

注意事項
	http://rei.to/carotdav.html を参照してください。
