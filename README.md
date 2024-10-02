## Japanese Manager Version 1.5 Release Note  Mar. 5,1993　(2024.10.2 修正)
　Japanese Manager (JM) は Apple IIGS のデスクトップ環境で日本語テキストを表示できるようにする Init です.  
　JM を動かすには 1.5M バイト以上の RAM と System 5.0.4 以上の OS が必要です.  
　本バージョンはフリーウェアです.  無料で第 3 者にコピーを配布することができます.

* JM1.0b3 版からの主な変更点  
  * JMT コードを変更し第 2 バイトが ASCII の記号にあたらないようにした.  
  * キャラクタイメージを 16 x 8 ドットにした.  
  * JIS X0201 片仮名互換文字と GS 拡張キャラクタ互換文字を表示できるようにした.  
  * メニュー用にチェックマークとオープンアップルマークを表示できるようにした.  
  * Toolbox 化により 各種サービスルーチンを サポートした.  
  * アクティブ/インアクティブを切り換える CDev をつけた.  
  * アイコンのデザインを変更した.  
  
* JM1.1 版からの主な変更点
  * JMT -> シフト JIS 変換のバグをとった.  
  * アクティブ/インアクティブの切り替えに伴う暴走を防いだ.  
  * おまけとして JM Gothic (en) という 8 x 8 ドットの JIS X0201 互換フォントをつけた.  
  
* JM1.2 版からの主な変更点
  * 大部分を C 言語で書き直した.  
  * 1 バイト文字を半角で表示するようにした.  
  
* JM1.3 版からの主な変更点  
  * JMT -> シフト JIS 変換のバグをとった.  
  * JM Gothic がバンクをまたいでロードされたときの不正表示を防いだ.  
  * JM Gothic のベースラインのずれを修正した.  
  * JM Gothic (en) の高さとベースラインを修正した.  
  
* JM1.4 版からの主な変更点  
  * JM Gothic がバンクをまたいでロードされたときの不正表示を防いだ.  
  * JM Gothic フォントをオリジナルデザインのものに置き換えた.  
  * JMT コード $A0xx に縦書き用フォントを割り当てた.  
  
＊ ファイル構成  
  JM 第 1.5 版は次のファイルから構成されます。  
  
　System (フォルダ)  
　　System.Setup (フォルダ)  
　　　'JM                   JM 本体'  
　　CDevs (フォルダ)  
　　　JM.CDev              日本語表示 ON/OFF CDev  
　　Fonts (フォルダ)  
　　　JMGothic.08          フォントストライクホルダ  
　　　JMGothic.08.en       半角フォント (おまけ)  
　　Japanese (フォルダ)  
　　　JMGothic.08L0        JM Gothic 第 0 水準フォントイメージ  
　　　JMGothic.08L1        JM Gothic 第 1 水準フォントイメージ  
　Icons (フォルダ)  
　　JM.Icons             JM アイコン  

  質問等は Facebook FAPPLE2 グループまでおねがいします。
