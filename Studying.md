# 初心者がMagicTween勉強中

MagicTweenのパフォーマンスがとても良いらしい。

MagicTweenのライセンスはMIT Licenseです。

<br>

## まず、MagicTweenをインストールしてみた

最初、大量のエラーが出てビビり、ECSのEntitiesをインストールしていなかっただけでしたね。<br>
com.unity.entitiesをインストールした時点で、エラーが解消されました。<br>

### 要件は
* Unity 2022.1 以上
* Entities 1.0.0 以上
* Burst 1.8.8 以上

<br>

## README_JAを読んでみた

README_JAに書かれている通り、Tween.To()よりも拡張メソッドはパフォーマンスが最適化されているとか最高なので、拡張メソッドを使います。

**確超メソッドのwikiを作成中らしい。応援してます！！！！！！！**

Tween.To()は任意の値を
