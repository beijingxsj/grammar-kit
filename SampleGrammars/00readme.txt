Julius 用の音声認識用文法のサンプル
=====================================
							updated 2011.07.07


◆内容
========

これは，Julius 用の認識文法のサンプル文法群です．
各ディレクトリに，Julius で用いることのできる文法のサンプルが
収められています．


◆ファイル構成
===============

各文法の詳細は，各ディレクトリ下の "00readme.txt" をご覧下さい．

○基本的な文法

  digit/	数字(１桁ずつ)
  number/	数字(十進数字)
  datetime/	日付・時間
  persons/	人数
  price/	価格(円)
  yesno/	はい／いいえ

○音節タイプライタ

  type/		音節タイプライタ

○特定タスク用文法

  fruit/	果物購入
  railroard/	切符購入
  attendant/	受付タスク（人の呼び出し）
  vfr/		服装着せかえ


◆使い方
==========

各ディレクトリ下の "Test.bat" （Linuxでは Test.sh）を実行すると，
その文法を読み込んでJuliusを起動することができます．

Julius 起動時のオプションで指定する場合は，
"-C 各ディレクトリ/jconf" と指定するか，あるいは
それぞれ .dfa ファイルを "-dfa" で，.dictファイルを "-v" で指定するこ
とで，使用できます．


◆文字コードについて
==========

文法ファイルの文字コードは SJIS です。
認識結果の文字コードも SJISです。
また，XML 文法ファイルは utf-8 です．


以上
