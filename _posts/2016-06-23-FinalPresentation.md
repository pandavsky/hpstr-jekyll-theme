---
layout: post
title: "Personal Project - Final Presentation -"
description: "Personal Project - Music and Yeast -"
tags: [Personal Project, music and yeast, DNA]
published: true
---

## Music and Yeast / 音楽と酵母
　This personal project was exhibited at the BHA graduation show at FabCafe MTRL in Shibuya, during the week of June 4 - 11, 2016.

### Background / プロジェクトの背景

Brewing process of Japanese Sake fascinates me. Even-though Basic raw materials are rice and water only, fermentation by Koji-mold and yeasts bring out numerous varieties of flavor. I encountered “sake song” during the sake brewery tours.

In an era when the clock didn’t exist in Japan, traditional sake brewers used to sing sake songs to check a long process of brewing. Since brewing technology has been advanced, sake songs are gradually forgotten now. 

I started to think possibilities to store the sake songs to the sake yeast. The goal of this project is to make fermented food and drink by yeast, which has music DNA.

日本酒の世界に惹かれている。基本の原材料は米と水だけなのに、そこに麹菌や酵母が関わることで、全く異なる味や香りを持つ日本酒ができあがるからだ。日本酒の蔵を巡る旅の中で、酒造り唄というものを知った。

酒造り唄は、まだ時計のない時代に酒造りの長い醸造工程の時間を計ることや、どの作業をしているのかを確認するためのものだった。醸造技術の進歩に伴い、次第に歌われなくなっていく。

この「酒造り唄」を、酵母のDNAに記録することは可能なのだろうか？という疑問からプロジェクトは始まった、最終的には「音楽DNAを持つ酵母」でお酒やパンをつくりたいと考えた。


### Challenges:
1.  Encoding music to DNA sequence
2.	Encoding DNA sequence to Music
    * 	Searching yeast, which has similar DNA to music DNA.
    * 	Encoding similar yeast DNA to Music

### このプロジェクトを通してチャレンジしたこと:
1.	音楽をDNA塩基配列に変換する
2.	DNA塩基配列から音楽に変換する
* 	変換した音楽DNAに似たDNAをもつ酵母をデータベースから探す
* 	類似酵母のDNAを音楽に戻す


---------------------------------------




### 1. Encoding music to DNA sequence / 音楽をDNA塩基配列に変換する

I tried some different ways to encode music to DNA sequence. Finally, I decided to encode music (sake song) to DNA sequence based on amino acid molecular weight. 
The twenty amino acids are mapped to a musical scale (pitch) and duration. Two amino acids are assigned to each note. 
A specific amino acid corresponds with a DNA codon, which is a sequence of three DNA nucleotides (T, C, A and/or G). So that music is encoded to DNA sequence.

* Multiple DNA codons corresponds with a amino acid. If same amino acid is assigned to pitch/duration once, different DNA codon will be assigned. So that DNA codon is always changing (to avoid erroneous DNA sequence).


音楽をDNA塩基配列に変換する方法を探った。いろいろ変換方法を試し、最終的にタンパク質を構成するアミノ酸の分子量を元に、音楽をDNA塩基配列に変換した。

酒造り唄の楽譜上の音高と音価の二つの情報にアミノ酸を割り当てて、DNA塩基配列に変換。最終的に楽譜上の一つの音符に対して音高と音価、それぞれ２つのアミノ酸がマッピングした。

一つのアミノ酸は３つの塩基（A,T,C,Gのうちのどれか三つ　コドン/トリプレットと呼ばれるもの）で構成されている。

* １つのアミノ酸には複数のコドン（）が割り当てられているため、同じアミノ酸が繰り返し使用された場合に、常に異なるコドンを選択するというルールを作りました。

<figure>
<img src="/images/BHA_Mayumi_Presentation_en.004.jpeg" alt="" style="border:1px solid #333333">
<img src="/images/BHA_Mayumi_Presentation_en.005.jpeg" alt="" style="border:1px solid #333333">
<img src="/images/BHA_Mayumi_Presentation_en.006.jpeg" alt="" style="border:1px solid #333333">
</figure>


#### Is that possible to transfer music(sake song) DNA sequence to yeast? / 音楽をDNA塩基配列に変換したものを酵母に導入することは可能か？

It is possible to transfer music DNA sequence to yeast without affecting biological function of yeast as recombinant DNA or plasmid. 

作成した配列を酵母に、生体機能に影響なく、組換えで導入することは可能。
もしくは、組換えを起こさないまま、遊離（プラスミド）の状態でもたせることも可能。


---------------------------------------



### 2.	Encoding DNA sequence to Music


Searching yeast, which has similar DNA to music (sake song) DNA through the DNA database (BLAST). 
The yeast, which has similar DNA sequences, is found. 

音楽DNAと類似のDNAをもつ酵母をデータベースから検索。類似の配列をもつ酵母が見つかった。

<figure>
<img src="/images/BHA_Mayumi_Presentation_en.008.jpeg" alt="" style="border:1px solid #333333">
<img src="/images/BHA_Mayumi_Presentation_en.009.jpeg" alt="" style="border:1px solid #333333">
</figure>


Then, A music is encoded from similar yeast DNA.
類似酵母のDNAを音楽に変換した

<figure>
<img src="/images/BHA_Mayumi_Presentation_en.010.jpeg" alt="" style="border:1px solid #333333">
<img src="/images/BHA_Mayumi_Presentation_en.011.jpeg" alt="" style="border:1px solid #333333">
</figure>

**Encoded DNA music file will be available here soon.../　変換したDNAの音楽は近日中にアップします。


---------------------------------------



### 3.	How does yeast recognize the sound? / 酵母は音を認識するか否か？

While exploring the ways to encode music to DNA, a new question is provoked. ”How does yeast recognize the sound?” To find out this, an experiment is conducted based on the encoded sake song DNA.

#### Procedure: 
1.  Encoding sake song to DNA sequence based on amino acid molecular weight. 
2.  Making three sound proof boxes, and placing a petri dish with cultured yeast into each box. Then observing 
    how yeasts grow within different sound environments; 
        *  (Box1) No sound. 
        *  (Box2) Playing a sake song. 
        *  (Box3) Searching yeast, which has similar DNA to sake song DNA. Then playing a song, which is composed from similar yeast DNA.


「音楽DNAを持つ酵母」をテーマに音楽をDNA塩基配列に変換し、酵母に保存する方法を探った。その過程でもう一つの疑問が生まれた。「酵母は音をどのように認識するのか？」音楽から変換したDNAを使用し、実験を通して酵母と音の関係を探る。

#### 実験：
1.  タンパク質を構成するアミノ酸の分子量を元に、酒造り唄をDNA塩基配列に変換。
2.  防音した箱を３つ作成。酵母を培養したシャーレをそれぞれの箱に入れ、異なる音環境で一定期間培養し、成長の違いを観察する。
      * （箱１）音無し
      * （箱２）酒造り唄を再生
      * （箱３）音楽DNAと類似のDNAをもつ酵母をデータベースから検索。類似酵母のDNAを音楽に変換し、再生。

<figure>
<img src="/images/BHA_Mayumi_Presentation_en.012.jpg" alt="" style="border:1px solid #333333">
</figure>


