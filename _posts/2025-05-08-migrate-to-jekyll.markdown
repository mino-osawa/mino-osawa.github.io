---
layout: post
title:  "サイトの管理を Jekyll に移行した"
running_head: "Jekyll 移行"
categories: Misc
misc: 快晴
---

この個人サイトに，いずれは研究解説や勉強したことのまとめ等の記事を掲載するようにしたいと思っている．そうすると，色々の再利用も見据えて基本はテキストファイルベースで運用したい．しかし見た目はそこそこイイ感じにしたい．気分で体裁を適宜自由に微調整したりもしたい．でもあんまり手間がかかるのは嫌だ……とあれこれ検討した結果 [Jekyll](https://jekyllrb.com/) で生成する方法に移行することにした．ぼちぼち綺麗に作ることができたと思う．

実はむかし [晴耕雨読](https://tex2e.github.io/blog/) さんを参考にブログを [JekyllDecent](https://jwillmer.github.io/jekyllDecent/) で作成しようとトライしてみたことがある．しかし，調べながら好みに合うようにカスタマイズするのが面倒で，ブログ投稿どころかブログ制作の試みそのものが三日坊主になった．今回は既存のテーマを採用するのではなく，ページ数が少なくあまり腰が重たくならないうちに自分の書いたベタ打ちの HTML をテンプレートにすることで最小限の構成の雛形を整え，あとから気が向いたタイミングで徐々に機能やデザインを追加していくという方針にした．ChatGPT に助けてもらったおかげで割とサクサクできた．体裁の修正も簡単にできるようになったはずだ．

というか前も思ったけれど Jekyll って便利だな．テンプレートをいじるだけのストレスの少ないワークフローになるのでありがたい．[Liquid](https://shopify.github.io/liquid/) が使えるので，記事のリストを作ったりするのが簡単で，CSV から論文のリストも作成できる．やはりページ数や内容が少ないうちに思い切ってよかった．将来的には数式入りのメモも載せられるように，MathJax も仕込んである．あとは書くだけ．

こんな自己満足作業の前にやるべきことがいっぱいあるよねという話が大いにある．アウトリーチとか社会への還元が国立大学に勤める研究者のひとつの義務だという話はある．でもこのサイトは現状なんの中身もないので，体裁いじりはただの趣味という感じである．昔からこういうのをやり始めるとつい熱中してしまう悪癖がある．細工仕事で身をたてるべきだったのかもしれない．関係があるかはわからないが父方の祖父は指物師だったらしい．とりあえず最初のうちはページ上部のナビでは非表示にしておこうかな……．フッターにはこっそり表示しておく．