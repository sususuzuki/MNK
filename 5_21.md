# MNK
亀に岩ガキ
## 5/21
class MyApp extends StatelessWidget {  
  const MyApp({Key? key}) : supper(key: key);  
  final title = 'Flutterサンプル';  
  final message = 'サンプル・メッセージ。';  

> final
  変更しないことを表す

child: Icon(Icon.airport_shuttle),

## 5/27
#### テキストの色々な変更
body:
          new Text(  
          "MNKMNKMNKMNKMNKMNK",<出力したい文字の入力  
            style: new TextStyle(fontSize:64.0, <フォントサイズの設定  
            color: const Color(0xFFa526ea), <テキストの色指定。Colorクラスで指定する。  
            fontWeight: FontWeight.w700, <フォントの太さ。FontWeightというクラスのw100~W900で指定する。  
            fontFamily: "Roboto"), <フォントファミリー。テキスト(String)で指定。  
          ),  

#### Containerクラスについて　　
"""Containerクラスはコンテナ(他のウィジェットを自身の中に格納できるウィジェット)の基本的なくらす"""
 
 body:  
          new Container( <Containerクラス  
            color: const Color(0xFFff0a0a), <色の指定  
            padding: const EdgeInsets.fromLTRB(40.0, 10.0, 50.0, 1.0), <余白幅の設定。(左、上、右、下)の順になっている  
            alignment: Alignment.topLeft,　<配置場所の指定。上下左右を九か所に分けて選択する  
            width: 100.0, <Sizedで表示サイズを最大化するためのもの  
            height: 500.0, <Sizedで表示サイズを最大化するためのもの  
          ),  
