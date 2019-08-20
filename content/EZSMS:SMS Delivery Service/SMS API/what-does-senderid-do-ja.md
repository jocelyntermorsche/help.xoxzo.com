Title: 送信元ID (Sender ID) というのは何でしょうか？
Date: 2016-01-26 14:32
Slug: what-does-sender-id-do
Lang: ja
Category: ezsmssms-delivery-service/SMS API

送信元ID (Sender ID)は、受信者の端末で、メッセージの送り主として表示されるものとなります。

SMSを配信する際に受信者側で表示される送信元IDは、なりすまし防止の観点から原則としてキャリアにより規制対象になることが多くあります。

通常の送信時、送信元IDを指定はできますが、キャリアによって、別のものに置き換えられる可能性があるということをご承知ください。

そのため、受信者にメッセージの配信元を明確に知ってもらうために、本文の中に配信元の情報を記載することを強くお勧めします。

使用可能な送信元IDの情報は各キャリアによって基準の違いもあり、（内部情報ですので開示されていませんが）以下の注意点が挙げられますのでご確認ください。

なお、以下のリストが常に有効であるとは保証できませんので、ご了承ください。

* 4文字以下の短い配信元IDを設定すると規制される場合があります

* そのまま表示されるという保証はありません

* 多くのキャリアではその国内にあるような番号（i.e 日本の場合08011223455または03897853334)に設定することができません

メッセージの送信前に、使用する予定の配信元IDを実際に指定してテストを行い、配信結果を確認した上でのご使用をお勧めします。

[Kプレミアムサービス](https://help.xoxzo.com/ja/ezsmssms-delivery-service/articles/what-is-k-premium/)をご利用になると、日本のau(KDDI)の携帯電話向けに、サービス申し込み時に設定した送信元IDを受信側へ表示させることができます。
お申込みを含めた詳細は、[Kプレミアムサービス](https://help.xoxzo.com/ja/ezsmssms-delivery-service/articles/what-is-k-premium/)のページより、ご確認ください。