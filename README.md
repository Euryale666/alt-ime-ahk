# alt-ime-ahk

## 概要

右 Alt キーの空打ちで IME を OFF/ON（トグル） する AutoHotKey スクリプトです。
karakaram氏の作ったものを一部改変しました。
メニューが隠れていて、Alt キー空打ちで表示する必要があるアプリもあるため、左 Alt キーは通常のままです。


* 右 Alt キーの空打ちで IME を「かな」←→「英数」に切り替え
* 右 Alt キーを押している間に他のキーを打つと通常の Alt キーとして動作

## 動作環境

* Windows10
* Windows7

Windows8 は試していませんが多分動きます

## 使い方

[releases](https://github.com/Euryale666/alt-ime-ahk/releases) から alt-ime-ahk.exe をダウンロードして好きな場所に置き、起動してください。 タスクトレイに常駐します。

終了する場合はタスクトレイのアイコンを右クリックし、「終了」をクリックしてください。

アンインストールは alt-ime-ahk.exe を削除するだけで OK です。

## JetBrains 製の IDE で使う場合は Tool Buttons をオンに

IntelliJ IDEA, PhpStorm など JetBrains 製の IDE をお使いの方は「上部メニューバー　＞　View　＞　Tool Buttons」をオンにしてください。

オフのまま使うと Alt キーを離した際に alt-ime-ahk.exe がエラー終了します。

## karakaram氏のブログの紹介ページ

[Altの空打ちで日本語入力(IME)を切り替えるツールを作った](http://www.karakaram.com/alt-ime-on-off)
