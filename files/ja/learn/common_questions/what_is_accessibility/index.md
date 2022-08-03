---
title: What is accessibility?
slug: Learn/Common_questions/What_is_accessibility
translation_of: Learn/Common_questions/What_is_accessibility
---
<div class="summary">
<p>この記事はwebアクセシビリティの背景にある基本的なコンセプトを紹介します。</p>
</div>

<table class="learn-box nostripe standard-table">
 <tbody>
  <tr>
   <th scope="row">前提条件:</th>
   <td>なし</td>
  </tr>
  <tr>
   <th scope="row">対象:</th>
   <td>アクセスビリティが何なのか、なぜ重要なのかを学ぶ</td>
  </tr>
 </tbody>
</table>

<h2 id="概要">概要</h2>

<p>物理的、技術的制限のせいで、たぶんあなたの訪問者はあなたの望むような体験をあなたのウェブサイトからできません。 この記事では一般的なアクセシビリティの原則や平易ないくつかの規則を示します。</p>

<h2 id="能動的学習">能動的学習</h2>

<p><em>まだ可能な能動的学習がありません。 <a href="/ja/docs/MDN/Getting_started">Please, consider contributing</a>.</em></p>

<h2 id="深く掘っていく">深く掘っていく</h2>

<h3 id="アクセスビリティ_一般的な原則">アクセスビリティ: 一般的な原則</h3>

<p>まず、我々は負の制限に伴うアクセスビリティに関連付けられなければならないだろう。このビルはアクセスブルでなければならず、そうなのでトイレのサイズやエレベーターの設置場所のこれらの規制に従わなければならない。</p>

<p>それはアクセスビリティで考えられる狭い方法である。人々に委ねたり、より多くの顧客に出す、びっくりするような方法を考えてみて下さい。 ブラジルにいる人々に英語のサイトをどのように出しますか？ スマートフォンのブラウザが重く、大きなデスクトップモニターにデザインされたウェブサイトが乱雑であったり、帯域が制限されていないことなどできますか？それらは別の場所に行くべきでしょう。一般的に<em>ターゲット顧客の観点から我々のプロダクトを考え、変化を採用しなければなりません。</em>従って、アクセスビリティなのです。</p>

<h3 id="ウェブアクセシビリティ">ウェブアクセシビリティ</h3>

<p>ウェブの特定の文脈において、アクセシビリティは障害、場所、技術的な制約、他の事情などにも関わらずコンテンツからの利益を誰もが得られることを意味します。 </p>

<p>ビデオについて考えてみましょう</p>

<dl>
 <dt>聴覚障害</dt>
 <dd>ビデオを聴覚障害の人はどのようにみるのでしょうか？  字幕を提供しなくてはなりませんし、 —　もしくはそうであってもより良いのはフルテキストの写しです。</dd>
 <dd>もしくはその人に適応したボリュームに調整してあげることができます。</dd>
 <dt>視覚障害</dt>
 <dd>もう一度、ビデオを上映することなしにテキストの写しを説明してあげたり、音声説明を提供することができます。 (ビデオで何が起こっているか述べる画面外の音声)</dd>
 <dt>中断する能力</dt>
 <dd>ユーザーがビデオで何か理解できない事態に見舞われるかもしれません。ビデオを止めて、字幕や情報のプロセス読むでしょう。 </dd>
 <dt>キーボードの能力</dt>
 <dd>ビデオの内外のタブを使うことで、仕掛けなしにビデオの再生中断をします。</dd>
</dl>

<h4 id="ウェブアクセスビリティの基本">ウェブアクセスビリティの基本</h4>

<p>いくつかの必要性を基本的なウェブアクセスビリティは含みます。</p>

<ul>
 <li>あなたのサイトは意味を伝える画像がいつでも必要になります。見ようとするユーザーや低速回線のユーザーに選択的なテキストとして含む必要があります。</li>
 <li>すべてのユーザーが専らキーボードでグラフィカルインターフェース(メニューを折りたたまないような) 操作できることを確かめなさい。(例えばタブやリターンキーで).</li>
 <li>テキストのはっきりと明示的な言語の指定を提供しなさい。そして、スクリーンリーダーは適切に読まれます。</li>
 <li>ユーザーがキーボードで仕掛けなし(少なくともタブの出入りだけで)で単独にすべてのページ上のウィジットナビゲートできるよう確かめなさい。</li>
</ul>

<p>そして、今、始めよう。</p>

<h3 id="アクセスビリティのチャンピオンたち">アクセスビリティのチャンピオンたち</h3>

<p>1999年以来, the {{Glossary("W3C")}} は{{Glossary("WAI","Web Accessibility Initiative")}}と呼ばれるグループを動かしてきた。このグループはガイドライン、マテリアル、国際的なリソースを通じてアクセスビリティを促進してきた。</p>

<h2 id="より詳細には">より詳細には</h2>

<p>以下を参照して下さい:</p>

<ul>
 <li><a href="https://en.wikipedia.org/wiki/Accessibility">ウキィペディアの記事</a> （アクセスビリティに関する）</li>
 <li><a href="http://www.w3.org/WAI/">WAI (W3Cのアクセスビリティイニシアティブ)</a></li>
</ul>

<h2 id="次のステップ">次のステップ</h2>

<p>アクセスビリティはウェブデザインや技術構造の両方にインパクトを与えることができます。</p>

<ul>
 <li>私たちはデザインの観点から, <a href="/ja/docs/Learn/Design_for_all_types_of_users_101">すべてのタイプのユーザーのためのデザイン</a>の勉強を提案する。</li>
 <li>もし、技術的な側面の興味を持ったら、 <a href="/ja/docs/Learn/Using_images">ウェブページにおける埋め込みイメージ</a>の方法を勉強することができる。</li>
</ul>