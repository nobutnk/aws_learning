# AWSの勉強

## 開始日
 * 2015/08/14

## 参考サイト
 http://qiita.com/hiroshik1985/items/6433d5de97ac55fedfde

## VPCを作成する。
* 参考 http://qiita.com/hiroshik1985/items/9de2dd02c9c2f6911f3b
* VPC: Amazon Virtual Private Cloud の略
* ネットワーク難しい、、、

## EC2インスタンスの作成
* 参考サイト http://qiita.com/hiroshik1985/items/f078a6a017d092a541cf
* 一番安くなるように構築
* 公開鍵は、保存後chmod で600

```
ssh ec2-user@{確認したPublic IP} -i {秘密鍵保存ディレクトリ}/test.pem
```

でsshできた！さて、いくらになるのか
