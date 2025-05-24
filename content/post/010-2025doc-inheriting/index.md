---
title: 2025年版 模擬店会計アプリケーション 引き継ぎ
description: 翠巒祭関係
slug: suiran-010
date: 2025-05-24 20:23:00+0900
tags:
    - 翠巒祭
---

どうも、[mint73](https://github.com/mint73) と [nAgI314](https://github.com/nAgI314) です。

この資料では、模擬店会計アプリケーションの引き継ぎ方法について書いています。

## 引継ぎについて

翠巒祭が終わったら、模擬店班チーフは次の年のために引継ぎをしましょう。

### Spread Sheet 関係

1. [Google Cloud のオーディエンス](https://console.cloud.google.com/auth/audience?inv=1&invt=Abx3Qw&project=gssheettest-448509)を開き、下の方にある「ユーザー情報」の表から、その年に登録したアカウントを削除します
削除はそれぞれの行のゴミ箱ボタンからできます
2. 次の年のチーフが班員のアカウントを登録できるように、このプロジェクトの「オーナー」にします。  
   1. [Google Cloud の IAM](https://console.cloud.google.com/iam-admin/iam?inv=1&invt=AbyOEA&project=gssheettest-448509) を開き、Grant Access を押します
      ![GrantAccess](s01-GrantAccess.png)
   2. 「新しいプリンシパル」に次期チーフの Google メールアドレスを入力し、「ロール」でオーナーを選択したら保存  
      ![setNewOwner](s02-SetNewOwner.png)
      ![owner](s03-Owner.png)
3. スプレッドシートの「購入情報」のデータは、別のシートに移すなど、情報が混ざってしまわないようにしましょう  
   ※1行目の「日時、チュロス、...」は消さないでください。

<!--
### 品物の値段を変更・品物を追加する

先に言うと、やや面倒です。
-->
