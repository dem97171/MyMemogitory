## PWAとは
> Progressive Web Appsの略。モバイルユーザーのUX向上を目的とした、WEBページ／WEBアプリケーションとネイティブアプリの利点をいいとこ取りできる仕組み。モバイル端末でページを表示する時にネイティブアプリのような挙動をさせることが出来る。Google（Android Chrome）を中心に策定・展開されており、ユーザーとのエンゲージメントの向上やコンバージョン・リテンションの改善に効果があるとされる。


## はじめてのプログレッシブ ウェブアプリ
https://developers.google.com/web/fundamentals/codelabs/your-first-pwapp/?hl=ja

pwa web starter kit (beta)  
[ここ](https://developers.google.com/web/tools/starter-kit/)からプロジェクトのベースをダウンロードできる。  
babelにgulpにsassにbrowsersyncにsw-cacheと、必要なライブラリが一通り揃ってるが要はオフラインキャッシュを意識したwebページ+service workerなわけで、
全部頼らなくても必要な部品だけ参考にすれば良い。

## 参考
> Appleが、iOSとmacOSの次バージョンにバンドルされるSafari 11.1で、Progressive Web Apps（PWA）の重要な構成要素であるService Workerをサポートすることが分かりました。

http://www.publickey1.jp/blog/18/apple_ios_macos_progressive_web_apps.html

## メモ
今はandroidしか対応してないが、
2018年からiOSの対応も進みそうとのことなので、勉強しておくと良さそう。  
windows10のデスクトップでもserviceworkerに対応するとの発表があったらしい。（対応時期未定）
