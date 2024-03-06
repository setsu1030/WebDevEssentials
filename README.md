# WebDevEssentials
Web開発で用いられる技術の概要を載せています。  
**概要はChatGPTを使用して生成したものです。内容が誤っている可能性もあります。**

**目次**
- [HTML](#html)
- [JavaScript](#javascript)
- [CSS](#css)
- [jQuery](#jquery)
- [Java](#java)
- [Apache Tomcat](#apache-tomcat)
- [Struts](#struts)
- [Spring Framework](#spring-framework)

## HTML
### ロゴ
<img src="images/logos_html-5.svg" height="300">

### 概要
HTMLはウェブページの作成に使用される標準的なマークアップ言語であり、`<html>`、`<head>`、`<body>`などのタグを用いて文書の構造を定義します。  
これらのタグには属性を設定することができ、ウェブページの動作や表示を詳細に制御することが可能です。  
HTML文書は、メタデータ、表示されるコンテンツ、リンク、画像、リスト、テーブル、フォームなどから構成され、セマンティックHTMLを活用することでコンテンツの構造を明確にし、アクセシビリティを高めることができます。  
また、HTMLはCSSやJavaScriptと組み合わせることにより、動的かつインタラクティブなウェブページを作成することが可能です。
### サイト
- [HTML の基本 - ウェブ開発を学ぶ | MDN](https://developer.mozilla.org/ja/docs/Learn/Getting_started_with_the_web/HTML_basics)
## JavaScript
### ロゴ
<img src="images/logos_javascript.svg" width="300">

### 概要
JavaScriptはウェブページに動的要素とインタラクティブ機能を加えるプログラミング言語です。  
主にクライアントサイドでブラウザ内で実行されるものの、Node.jsなどを使用してサーバーサイドでも適用可能です。  
イベント駆動プログラミング、DOM操作、非同期通信（Ajax）、および現代のフレームワークやライブラリ（React、Angular、Vue.js）を活用することで、開発を効率化することができます。  
JavaScriptは、多様なデータ型、関数、ECMAScript標準の発展、プロミスやasync/awaitを用いた非同期処理のサポートを通じて、ウェブ開発におけるインタラクティビティとユーザーエクスペリエンスを向上させます。
### サイト
- [JavaScript | MDN](https://developer.mozilla.org/ja/docs/Web/JavaScript)

## CSS
### ロゴ
<img src="images/logos_css-3.svg" height="300">

### 概要
CSSはウェブページのスタイリングに用いられ、HTML要素に色、フォント、レイアウトなどの視覚的スタイルを適用する言語です。  
セレクタを用いて特定の要素にスタイルを定義し、カスケーディングルールによりスタイルの優先順位を決定します。  
ボックスモデルに基づく要素の配置、FlexboxやGridによるレイアウト設計、メディアクエリを活用したレスポンシブデザインの実装、アニメーションやトランジションを使用した動的効果の追加など、多様な機能を提供します。  
さらに、CSS変数や前処理器の使用により、スタイルシートの管理と記述が効率化されます。  
CSSは、HTMLとJavaScriptとともに、ウェブ開発の核となる技術です。
### サイト
- [CSS: カスケーディングスタイルシート | MDN](https://developer.mozilla.org/ja/docs/Web/CSS)

## jQuery
### ロゴ
<img src="images/logos_jquery.svg" width="300">

### 概要
jQueryはJavaScriptのライブラリであり、DOM操作、イベントハンドリング、Ajax通信を容易にし、クロスブラウザ互換性を提供します。  
これにより、要素の選択や変更、ユーザーイベントの処理、ビジュアルエフェクトの適用が容易になります。  
jQueryのメソッドはチェーン可能であり、複数の操作を簡潔なコードで記述でき、多様なプラグインによって機能を拡張できます。  
その軽量さと広範囲な利用により、jQueryはウェブ開発における標準的なツールの一つとして広く採用されています。
### サイト
- [jQuery](https://jquery.com/)

## Java
### ロゴ
<img src="images/logos_java.svg" height="300">

### 概要
Javaはオブジェクト指向プログラミング言語で、1995年にSun Microsystemsによって開発され、現在Oracleが所有しています。  
その「Write Once, Run Anywhere」の理念のもと、Java Virtual Machine（JVM）上でプラットフォームに依存せず実行可能です。  
クラスベースのオブジェクト指向性を持ち、再利用可能なコードモジュールの作成を容易にします。  
また、ファイル処理、ネットワーク通信、データベース接続などをサポートする豊富な標準ライブラリを備えています。  
自動メモリ管理によるガベージコレクションを用いてメモリリークのリスクを減らし、実行時のコード検証、メモリ管理、例外処理により安全なプログラミングを実現します。  
Javaはウェブ、エンタープライズ、モバイル（特にAndroid）、組み込みシステムなど多様なアプリケーションで使用されており、Eclipse、IntelliJ IDEA、NetBeansなどの強力な開発ツールをサポートします。  
広範な開発者コミュニティ、学習資料、ドキュメント、フォーラムが存在し、その汎用性、安全性、移植性の高さから、世界中で広く使われています。
### サイト
- [Java | Oracle](https://www.java.com/ja/)

## Apache Tomcat
### ロゴ
<img src="images/logos_tomcat.svg" width="300">

### 概要
Apache Tomcatは、JavaサーブレットとJavaServer Pages（JSP）を実行するオープンソースのWebサーバーおよびサーブレットコンテナです。  
このソフトウェアは無料で提供されており、ソースコードにもアクセスできます。  
Javaを利用したWebアプリケーション開発に特化し、軽量性とスケーラビリティのバランスが取れているため、小規模から大規模なWebアプリケーションの開発に適しています。  
Apache Software Foundationが管理し、定期的な更新を通じてその信頼性と最新性を保証しています。  
設定と管理の容易さにより、開発者は迅速に開発環境を構築でき、多数の商用およびオープンソースWebアプリケーションで使用されています。  
Apache Tomcatは、信頼性と拡張性に優れたJavaベースのWebアプリケーションの開発および展開に適した選択肢です。
### サイト
- [Apache Tomcat® - Welcome!](https://tomcat.apache.org/)

## Struts
### ロゴ
<img src="images/logos_struts.svg" width="300">

### 概要
Strutsは、JavaでのWebアプリケーション開発を支援するオープンソースフレームワークです。  
これはMVC（Model-View-Controller）アーキテクチャに基づき設計されており、フォームデータのバリデーション、多言語対応の国際化、プラグインによる拡張性など、様々な特徴を備えています。  
リクエストをアクションクラスにマッピングするアクションベースの仕組みを採用している点も特徴の一つです。  
Apache Software Foundationによって管理されているこのフレームワークは、その拡張性の高さから多くの開発者に利用されています。  
しかし、近年ではSpring MVCなどの他のフレームワークへの移行が増えている状況です。
### サイト
- [Welcome to the Apache Struts project](https://struts.apache.org/)

## Spring Framework
### ロゴ
<img src="images/logos_spring.svg" width="300">

### 概要
Spring FrameworkはJava用のオープンソースアプリケーションフレームワークであり、プログラミングと設定のための包括的なモデルを提供します。  
その主要な特徴は、依存性注入（DI）による疎結合アプリケーションの開発支援、アスペクト指向プログラミング（AOP）に基づく宣言的トランザクション管理、モジュラーなコンポーネントの使用による開発の支援、Spring MVCを利用したWebアプリケーション開発の簡素化、そしてJDBCとORMフレームワークの統合によるデータアクセスの抽象化と簡易化にあります。  
これらの機能によって、Spring Frameworkは企業向けアプリケーション開発において柔軟性、強力な機能性、簡潔な開発モデルを提供し、広く採用されています。
### サイト
- [Spring Framework](https://spring.io/projects/spring-framework)
