# univalent-tools
-----

## なにこれ
えーなんだろこれ。簡単に言うとBashとかで動くシステム設定用ソフトでーす。
Alter Linuxのi3-wm版に搭載されているヤツに影響されて「こんなのがあるといいなー」みたいな考えで作りました。

以下の事を行なえます。
- 画面設定 (ARandR)
- ネットワーク設定 (Network Manager)
- 音声設定 (PulseAudio Volume Control)
- パッケージ管理 (Yet Another Yogurt)
	- 全てのパッケージの更新
	- パッケージの検索
	- パッケージの導入
	- パッケージの削除
- 時刻設定
	- 標準時間帯の変更
	- NTPによる時刻の同期
	- ハードウエアクロックへの書き込み
	- NTPの有効化及び無効化

## 依存パッケージ
- arandr
- networkmanager
- ntp
- pavucontrol
- yay

`yay -S arandr networkmanager pavucontrol ntp`

## Special Thanks
わたすけ (@watasuke102)