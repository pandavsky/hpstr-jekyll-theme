---
layout: post
title: "Personal Project - Final Presentation -"
description: "Personal Project - Music and Yeast -"
tags: [Personal Project, music and yeast, DNA]
published: false
---

## Music and Yeast / 音楽と酵母

### Background / プロジェクトの背景

Brewing process of Japanese Sake fascinates me. Even-though Basic raw materials are rice and water only, fermentation by Koji-mold and yeasts bring out numerous varieties of flavor. I encountered “sake song” during the sake brewery tours.

In an era when the clock didn’t exist in Japan, traditional sake brewers used to sing sake songs to check a long process of brewing. Since brewing technology has been advanced, sake songs are gradually forgotten now. 

I started to think possibilities to store the sake songs to the sake yeast. The goal of this project is to make fermented food and drink by yeast, which has music DNA.

日本酒の世界に惹かれている。基本の原材料は米と水だけなのに、そこに麹菌や酵母が関わることで、全く異なる味や香りを持つ日本酒ができあがるからだ。日本酒の蔵を巡る旅の中で、酒造り唄というものを知った。

酒造り唄は、まだ時計のない時代に酒造りの長い醸造工程の時間を計ることや、どの作業をしているのかを確認するためのものだった。醸造技術の進歩に伴い、次第に歌われなくなっていく。

この「酒造り唄」を、酵母のDNAに記録することは可能なのだろうか？という疑問からプロジェクトは始まった、最終的には「音楽DNAを持つ酵母」でお酒やパンをつくりたいと考えた。


### Challenges:
1.	Encoding music to DNA sequence
2.	Encoding DNA sequence to Music
    * 	Searching yeast, which has similar DNA to music DNA.
    * 	Encoding similar yeast DNA to Music

### このプロジェクトを通してチャレンジしたこと:
1.	音楽をDNA塩基配列に変換する
2.	DNA塩基配列から音楽に変換する
* 	変換した音楽DNAに似たDNAをもつ酵母をデータベースから探す
* 	類似酵母のDNAを音楽に戻す


### 1. Encoding music to DNA sequence / 音楽をDNA塩基配列に変換する

I tried some different ways to encode music to DNA sequence. Finally, I decided to encode music (sake song) to DNA sequence based on amino acid molecular weight. 
The twenty amino acids are mapped to a musical scale (pitch) and duration. Two amino acids are assigned to each note. 
A specific amino acid corresponds with a DNA codon, which is a sequence of three DNA nucleotides (T, C, A and/or G). So that music is encoded to DNA sequence.

＊Multiple DNA codons corresponds with a amino acid. If same amino acid is assigned to pitch/duration once, different DNA codon will be assigned. So that DNA codon is always changing (to avoid erroneous DNA sequence).


音楽をDNA塩基配列に変換する方法を探った。いろいろ変換方法を試し、最終的にタンパク質を構成するアミノ酸の分子量を元に、音楽をDNA塩基配列に変換した。

酒造り唄の楽譜上の音高と音価の二つの情報にアミノ酸を割り当てて、DNA塩基配列に変換。最終的に楽譜上の一つの音符に対して音高と音価、それぞれ２つのアミノ酸がマッピングした。

一つのアミノ酸は３つの塩基（A,T,C,Gのうちのどれか三つ　コドン/トリプレットと呼ばれるもの）で構成されている。

＊１つのアミノ酸には複数のコドン（）が割り当てられているため、同じアミノ酸が繰り返し使用された場合に、常に異なるコドンを選択するというルールを作りました。

<figure>
<img src="/images/BHA_Mayumi_Presentation_en.004.jpeg" alt="">
<img src="/images/BHA_Mayumi_Presentation_en.005.jpeg" alt="">
<img src="/images/BHA_Mayumi_Presentation_en.006.jpeg" alt="">
</figure>


#### Is that possible to transfer music(sake song) DNA sequence to yeast? / 音楽をDNA塩基配列に変換したものを酵母に導入することは可能か？

It is possible to transfer music DNA sequence to yeast without affecting biological function of yeast as recombinant DNA or plasmid. 

作成した配列を酵母に、生体機能に影響なく、組換えで導入することは可能。
もしくは、組換えを起こさないまま、遊離（プラスミド）の状態でもたせることも可能。





### 2.	Encoding DNA sequence to Music













### Two Up

Apply the `half` class like so to display two images side by side that share the same caption.

```html
<figure class="half">
	<img src="/images/image-filename-1.jpg" alt="">
	<img src="/images/image-filename-2.jpg" alt="">
	<figcaption>Caption describing these two images.</figcaption>
</figure>
```

And you'll get something that looks like this:

<figure class="half">
	<a href="http://placehold.it/1200x600.jpg"><img src="http://placehold.it/600x300.jpg" alt=""></a>
	<a href="http://placehold.it/1200x600.jpg"><img src="http://placehold.it/600x300.jpg" alt=""></a>
	<img src="http://placehold.it/600x300.jpg" alt="">
	<img src="http://placehold.it/600x300.jpg" alt="">
	<figcaption>Two images.</figcaption>
</figure>

### Three Up

Apply the `third` class like so to display three images side by side that share the same caption.

```html
<figure class="third">
	<a href="http://placehold.it/1200x600.jpg"><img src="http://placehold.it/600x300.jpg" alt=""></a>
	<a href="http://placehold.it/1200x600.jpg"><img src="http://placehold.it/600x300.jpg" alt=""></a>
	<a href="http://placehold.it/1200x600.jpg"><img src="http://placehold.it/600x300.jpg" alt=""></a>
	<figcaption>Caption describing these three images.</figcaption>
</figure>
```

And you'll get something that looks like this:

<figure class="third">
	<a href="http://placehold.it/1200x600.jpg"><img src="http://placehold.it/600x300.jpg" alt=""></a>
	<a href="http://placehold.it/1200x600.jpg"><img src="http://placehold.it/600x300.jpg" alt=""></a>
	<a href="http://placehold.it/1200x600.jpg"><img src="http://placehold.it/600x300.jpg" alt=""></a>
	<a href="http://placehold.it/1200x600.jpg"><img src="http://placehold.it/600x300.jpg" alt=""></a>
	<a href="http://placehold.it/1200x600.jpg"><img src="http://placehold.it/600x300.jpg" alt=""></a>
	<a href="http://placehold.it/1200x600.jpg"><img src="http://placehold.it/600x300.jpg" alt=""></a>
	<figcaption>Three images.</figcaption>
</figure>

### Alternative way

Another way to achieve the same result is to include `gallery` Liquid template. In this case you
don't have to write any HTML tags – just copy a small block of code, adjust the parameters (see below)
and fill the block with any number of links to images. You can mix relative and external links.

Here is the block you might want to use:

```liquid
{% raw %}{% capture images %}
	/images/abstract-10.jpg
	/images/abstract-11.jpg
	http://upload.wikimedia.org/wikipedia/en/2/24/Lenna.png
{% endcapture %}
{% include gallery images=images caption="Test images" cols=3 %}{% endraw %}
```

Parameters:

- `caption`: Sets the caption under the gallery (see `figcaption` HTML tag above);
- `cols`: Sets the number of columns of the gallery.
Available values: [1..3].

It will look something like this:

{% capture images %}
	/images/abstract-10.jpg
	/images/abstract-11.jpg
	http://upload.wikimedia.org/wikipedia/en/2/24/Lenna.png
{% endcapture %}
{% include gallery images=images caption="Test images" cols=3 %}
