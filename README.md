# tenkeyビルドガイド

## 同梱品
![01](https://github.com/yamyam3/tenkey/assets/135976746/759d86ab-93d2-4cf7-a882-8d23c197d70b)

|番号| 名前  |  数 |
|:-----------|:-----------|:------------|
|①| 基板 | 5 枚 |
|②| スイッチソケット | 18個+予備2個 |
|③| ダイオード | 18個+予備2個 |
|④| MXスイッチ  | 18個 |
|⑤| キーキャップ | 18個 |
|⑥| 3.5mm スペーサー | 4個+予備2個 |
|⑦| 6mm スペーサー | 4個+予備2個 |
|⑧| 7mm ネジ | 4個+予備2個 |
|⑨| 8mm ネジ | 4個+予備2個 |
|⑩| 2Uスタビライザー | 2個 |
|⑪| 4ピン コンスルー | 2個 |
|⑫| 5ピン コンスルー | 2個 |
|⑬| マイコン | 1個 |
|⑭| 7ピン コンスルー | 2個 |
|⑮| ゴム足 | 6個 |

## 基板構成
![02](https://github.com/yamyam3/tenkey/assets/135976746/664d18e2-e9d4-4131-9f5f-70ccc7911340)

|番号| 名前 | 説明 |
|:-----------|:-----------|:-----------|
|1| トッププレート | キースイッチの固定に使用します |
|2| メイン基板 | キースイッチの取り付けなどに使用します |
|3| サブ基板 | マイコン接続用の基板です |
|4| ボトムプレート1 | サブ基板の保護用に使用します |
|5| ボトムプレート2 | 底面の見た目を良くするために使用します|

## 組み立て方法
2のメイン基板、②のスイッチソケットと③のダイオードを使用します。

![03](https://github.com/yamyam3/tenkey/assets/135976746/feb6392f-4a01-4675-a679-99735715f3ed)

メイン基板の裏側を向けてください。

![04](https://github.com/yamyam3/tenkey/assets/135976746/33049885-2cc0-4add-87ba-704e2c3573a0)

はんだごてとはんだを使用し、赤丸の部分に予備ハンダをしていきます

![05](https://github.com/yamyam3/tenkey/assets/135976746/eaf991ea-ab6c-4e5d-baae-eea46bb88946)
![06](https://github.com/yamyam3/tenkey/assets/135976746/f49b3ba1-cdf2-45ec-815d-b6fb4ed82035)
![07](https://github.com/yamyam3/tenkey/assets/135976746/d008dbb8-daab-4292-95e8-67e06aee9a66)

次に③のダイオードを開封します。非常に小さい部品のため気をつけて開封してください。
画像のような開封はおすすめしません

![08](https://github.com/yamyam3/tenkey/assets/135976746/aaec50be-41c6-4a9a-8a82-75e9c57b00cb)
![09](https://github.com/yamyam3/tenkey/assets/135976746/de3868bc-cb19-4dd5-8d31-f93a5f5c9d18)

ダイオードにある線と基板の印字にある向き（ここでは下向きにそろえてください）に揃えます。

![10](https://github.com/yamyam3/tenkey/assets/135976746/39fb39a4-eab9-466c-86d8-aadfb386f8c3)

基板に行った予備ハンダを溶かしながら、ダイオードをピンセットなどで持ちながら、予備ハンダに向けてスライドさせます。

![11](https://github.com/yamyam3/tenkey/assets/135976746/2ae96038-08ad-4219-85d5-63335a0f0326)
![12](https://github.com/yamyam3/tenkey/assets/135976746/d3c4be81-68f6-4975-969d-75d95894edb1)
![13](https://github.com/yamyam3/tenkey/assets/135976746/6fec7e5b-4d6a-4b25-834a-373d57622f76)


その後、ダイオードをピンセットなどで保持したまま、はんだごてを離します。

![14](https://github.com/yamyam3/tenkey/assets/135976746/228d10e6-86e5-4377-b58c-7a4146406ddb)
![15](https://github.com/yamyam3/tenkey/assets/135976746/34c2cd34-752f-4bc6-ae54-82ce25886d23)

これをすべての箇所（計18箇所）行ってください。

18箇所行ったら、反対側の面を更にハンダ付けしていきます。

![16](https://github.com/yamyam3/tenkey/assets/135976746/241957ff-8795-4a7e-b727-2fa119199771)
![17](https://github.com/yamyam3/tenkey/assets/135976746/314fee7a-1ad6-4be9-9c35-abdcd58be5d2)

これも同様にすべての箇所（計18箇所）行ってください。

![18](https://github.com/yamyam3/tenkey/assets/135976746/3bc0293e-78b9-4ee9-b6ff-bee990eb85d8)

次に②のスイッチソケット取り付けを行います。

メイン基板の赤丸の部分に予備ハンダをしていきます。

![19](https://github.com/yamyam3/tenkey/assets/135976746/743c139e-7a9d-4a01-945a-3eda5e3fc47f)
![20](https://github.com/yamyam3/tenkey/assets/135976746/74d33d99-896f-4b8c-9fe6-2dd18495dfde)
![21](https://github.com/yamyam3/tenkey/assets/135976746/574e29fc-7884-4831-8848-11a2455bd434)
![22](https://github.com/yamyam3/tenkey/assets/135976746/3dd3a2ce-b613-4919-96b9-066cceb48587)

予備ハンダを行ったら、次にスイッチソケットを開封してください。

![23](https://github.com/yamyam3/tenkey/assets/135976746/d7bce807-c3b5-4976-bb3c-56b5a5d0a22d)

開封後、スイッチソケットをはめていきます。このとき向きに気をつけて取り付けをしてください。

![24](https://github.com/yamyam3/tenkey/assets/135976746/734accf1-ab60-4434-8985-b85dbcf17c16)

スイッチソケットをすべてはめたら、はんだごてを使用していきます。

スイッチソケットの足の部分からはんだごてを入れ、基板に押し付けるようにハンダ付けしていきます。

![25](https://github.com/yamyam3/tenkey/assets/135976746/996063a2-2f66-4047-9b75-642b19ef3d61)

これをすべての箇所（計18箇所）行ってください。

次に、反対側の足のハンダ付けしていきます。

反対側の足にはんだごてを入れ、そこにハンダを流し込みます。

![26](https://github.com/yamyam3/tenkey/assets/135976746/d81352ea-b0cd-45c8-8bb1-3bf576f40ef7)


これも再度すべての箇所（計18箇所）行ってください。

これでハンダ付けは完了です。

## メインの組み立て

スタビライザーを取り付けていきます。

画像の向きのように取り付けます。

![27](https://github.com/yamyam3/tenkey/assets/135976746/c1360069-87bf-4d87-aa2c-1d64a96e1be8)
![28](https://github.com/yamyam3/tenkey/assets/135976746/5c8b72b1-66ef-4ccc-930a-5559257a8892)
![29](https://github.com/yamyam3/tenkey/assets/135976746/267ee308-866b-4a49-9d26-4a8f8278f3af)
![30](https://github.com/yamyam3/tenkey/assets/135976746/4a05872b-83a4-4372-ac70-e11721ce5846)

カチッと音がするまで押し込んでください。その後、抜けないことを確認してください。 

次に1のトッププレート、⑥の3.5mm スペーサーと⑨の8mm ネジを使用します。

![31](https://github.com/yamyam3/tenkey/assets/135976746/740f1bdf-9470-4526-86cb-04858b895977)

トッププレート四隅にある穴にネジを入れ、スペーサーをねじ止めします。
このときスペーサーからネジが出ていることを確認してください。

![32](https://github.com/yamyam3/tenkey/assets/135976746/b573b2da-c269-46df-82c8-6cbfd05adbff)
![33](https://github.com/yamyam3/tenkey/assets/135976746/2c940284-e632-44d6-8f3a-a2a872c549ff)
![34](https://github.com/yamyam3/tenkey/assets/135976746/aca69850-43be-4507-bcbe-6c61542198ee)

トッププレートとメイン基板の向きをあわせ重ねます。

![35](https://github.com/yamyam3/tenkey/assets/135976746/76846ba7-b5b3-4ffd-b8b5-ce653f81e7b6)
![36](https://github.com/yamyam3/tenkey/assets/135976746/98d6b845-5de8-420a-b979-610cd689ac6d)

そこにキースイッチを入れていきます。完全に奥まで入れてください

![37](https://github.com/yamyam3/tenkey/assets/135976746/3762440f-3b79-4489-8493-0b9e934c5b40)
![38](https://github.com/yamyam3/tenkey/assets/135976746/71dda4d9-bef1-46bb-8fee-3f20296b8ce3)
![39](https://github.com/yamyam3/tenkey/assets/135976746/8d50aac7-ade0-4584-8a95-5c2fc49b4cf8)
![40](https://github.com/yamyam3/tenkey/assets/135976746/56563169-e1bf-4a9b-9d9d-844006bb4957)

また、このときキースイッチのピン折れに注意してください。

正しく挿入されている場合、メイン基板の裏面にあるスイッチソケットの穴からピンが出ているのでわかります。

次に、⑧の6mm スペーサーをメイン基板裏側の四隅から出ているネジに取り付けます。

![41](https://github.com/yamyam3/tenkey/assets/135976746/8f18816b-4d53-4721-b026-c1a8cefc7194)
![42](https://github.com/yamyam3/tenkey/assets/135976746/2e75039f-5529-45b6-af49-a90788a6fc7d)
![43](https://github.com/yamyam3/tenkey/assets/135976746/03843699-f810-4b48-8de2-46b043b76720)
![44](https://github.com/yamyam3/tenkey/assets/135976746/b1b68715-f6f8-463d-8fdc-96171010a568)

以上でメイン基板の組み立ては終わりです。

## サブ基板の組み立て
3のサブ基板、⑬のマイコン、⑭の7ピン コンスルー、⑪の4ピン コンスルーと⑫の5ピン コンスルーを使用します。

![45](https://github.com/yamyam3/tenkey/assets/135976746/af641800-f426-48c0-b4a6-cd9f04215eb6)

マイコンに7ピン コンスルーを取り付けていきます
コンスル－には向きがあります。

画像のようにコンスルー中央より少しズレた位置に小さい穴があります。

![46](https://github.com/yamyam3/tenkey/assets/135976746/0e83fcbf-88c9-4fda-95ca-4b69830e5c7a)

穴の向きを上側なるようにマイコンに取り付けてください。

![47](https://github.com/yamyam3/tenkey/assets/135976746/f65ef9f7-8718-4995-b3ac-201c4e9d335c)
![48](https://github.com/yamyam3/tenkey/assets/135976746/a3352919-7b11-4ef9-b669-9dc0f72581c7)


取り付けたマイコンの左右を見て、片方には穴があり、もう一方には穴がない状態にしてください。

![49](https://github.com/yamyam3/tenkey/assets/135976746/af8d34cb-c9d1-4e10-9e67-8477f0ba497c)
![50](https://github.com/yamyam3/tenkey/assets/135976746/8e63e336-38dd-4d7f-8635-c6fd5bd6e5d6)

コンスルーとマイコンのハンダ付けは不要です

マイコンとサブ基板に取り付けます。

画像の赤丸部分に取り付けます。

![51](https://github.com/yamyam3/tenkey/assets/135976746/dc6a0a73-9d44-41a0-9eab-0e44e75ee617)
![52](https://github.com/yamyam3/tenkey/assets/135976746/d15cc684-d092-407a-9656-a51f4c017988)
![53](https://github.com/yamyam3/tenkey/assets/135976746/908aab0c-e77a-4734-ad95-43efabda2ad3)

このときもハンダ付けは不要です

次に、サブ基板と4ピン コンスルーおよび5ピン コンスルーを赤丸部分に取り付けます。

![54](https://github.com/yamyam3/tenkey/assets/135976746/bc2bd2a0-e3f0-450a-ae5a-cfdf1dc26f7b)

このときコンスルーの向きも先程と同様にそろえてください。

コンスルーの穴の向きさえ揃って入れば、上下は気にしなくても構いません。

![55](https://github.com/yamyam3/tenkey/assets/135976746/4bc87486-9eaf-42a2-9ae8-8fbf2438521a)

メイン基板とサブ基板の取り付けを行いますが、メイン基板の赤丸の部分にセロハンテープなどを2重に貼ってください。

マイコンのコンスルーとスイッチソケットの金属部分が接触して、予期せぬ動作をする可能性があるためです。

![57](https://github.com/yamyam3/tenkey/assets/135976746/3ff1a046-bae6-45b3-881a-99a6c5898a00)
![58](https://github.com/yamyam3/tenkey/assets/135976746/02eae85a-33a5-4068-b0e9-91600ed95b25)

セロハンテープを貼ったあと、メイン基板にある4ピンおよび5ピンの穴の部分にコンスルーが刺さるように取り付けます。

![58](https://github.com/yamyam3/tenkey/assets/135976746/409c0942-231d-46df-a25d-d0e006c0a57a)
![59](https://github.com/yamyam3/tenkey/assets/135976746/94f43866-1d99-40e4-a7ee-b92d5c01d6a1)

次に、4のボトムプレート1と5のボトムプレート2を ボトムプレー1、ボトムプレート2の順番にサブ基板に合わせます。

![61](https://github.com/yamyam3/tenkey/assets/135976746/b5f498f8-2eda-4ca3-9571-05cac48f0b41)
![62](https://github.com/yamyam3/tenkey/assets/135976746/e089c65e-8b39-48dc-8b09-04357a5013ee)
![63](https://github.com/yamyam3/tenkey/assets/135976746/11e020bb-f5a8-46f1-9695-01f2c62d1321)

四隅の穴に、⑨の7mm ネジを入れ、ネジ止めをします。

![66](https://github.com/yamyam3/tenkey/assets/135976746/fbc674bb-50a9-42a9-a75b-e5975af51a9d)
![68](https://github.com/yamyam3/tenkey/assets/135976746/aa6dcdf9-8dcf-4ed3-9505-57fd45e38af9)

また、任意の場所に⑮のゴム足を取り付けます。

![70](https://github.com/yamyam3/tenkey/assets/135976746/dc2da30a-f50f-4c99-88a3-05c831955de8)

最後に、キースイッチにキーキャップを取り付け完成です。

![71](https://github.com/yamyam3/tenkey/assets/135976746/b09483fc-e186-4b06-ae50-f949e6379f17)

## 動作確認
マイコンにはファームウェアの書き込みを行っています。

USB Cケーブルを使用し、PCと接続すると使用できます。

[ここ](https://github.com/yamyam3/tenkey/blob/main/tenkey.json) から JSONファイルをダウンロードします。

次に、https://remap-keys.app/ へ アクセスを行います

アクセス後、[START REMAP FOR YOUR KEYBOARD]ボタンをクリックします

![72](https://github.com/yamyam3/tenkey/assets/135976746/9cac3e7e-5f89-4e00-84b8-7f01bcc137bb)

その後、＋KEYBOARDボタンを押し、表示されたダイアログにてtenkeyをクリックします。

![73](https://github.com/yamyam3/tenkey/assets/135976746/7495530f-c0da-4e64-b771-53e9d5f6d33d)
![74](https://github.com/yamyam3/tenkey/assets/135976746/0c0e56c1-bd6c-477f-92be-ab471d1aa0fb)

Please import your tenkey definition file(.json). と表示されるので、IMPORT(.JSON)をクリックし、ダウンロードしたJSONファイルを読み込みます。

![75](https://github.com/yamyam3/tenkey/assets/135976746/5f9abf1a-fd46-47c4-9bb8-99d0e70843f2)
![76](https://github.com/yamyam3/tenkey/assets/135976746/181236ff-8e86-4d2d-8bad-ce1c850f0a41)

読み込み後、以下のような画面が表示されるので、[・・・]ボタンをクリックし、[Test Matrix Mode]をクリックします。

![77](https://github.com/yamyam3/tenkey/assets/135976746/565803fa-aa62-4d24-b18f-12700584e885)

キーボードのキースイッチをそれぞれ押し、対応する位置が青く変化することを確認してください。

![78](https://github.com/yamyam3/tenkey/assets/135976746/63d32065-6930-4d6f-b3f0-70145ec8b2c0)

すべてのキーが青く変化したら動作確認完了および組み立て完了です。お疲れ様でした。
