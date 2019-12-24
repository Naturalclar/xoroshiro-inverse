# Xoroshiro inverse

ポケモン剣盾のレイドseed特定ツールです．

## 起動方法

`xoroshiroinverse.jar` をダウンロードした後，同じディレクトリ内で次を実行:

Windows

    java -jar .\xoroshiroinverse.jar
    
Linux

    java -jar ./xoroshiroinverse.jar


## seedを特定する

1. `ねがいのかたまり` を使い，次を満たすポケモンが出るまで日付を変え続ける．
    - V固定箇所が3つ以下
1. V固定箇所が2つ以上のポケモンしか出ないromの場合，3日前リセットを利用して連続5個体値を集める．
1. そこを起点に2日分もしくは3日分の個体の個体値・特性・性格を捕獲して確認し，ツールに入力する．

- seed検索には時間がかかります．
