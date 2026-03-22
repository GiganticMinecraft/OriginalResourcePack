# OriginalResourcePack

ギガンティック☆整地鯖で提供されている独自リソースパック（以下「本リソースパック」）です。使用するには各Modを導入する必要があります。  
最新バージョンのリソースパックは、[GitHubのRelease](https://github.com/GiganticMinecraft/OriginalResourcePack/releases/latest)からダウンロードできます。

## 利用するには

- 前提Modの導入
- リソースパックの適用（自動または手動）

が必要です。

### 前提Mod

**自動・手動での適用問わず、以下のModを導入する必要があります。**  
すべて**1.18.2に対応したもの**を使用してください。  
各リンクの下に書いてあるバージョンで動作確認済みとなります。（リンクもそのバージョンになっています。）  
なお、Fabricを使用しますので、**OptiFineやForgeなどとの併用はできません**。

- [Fabric API](https://modrinth.com/mod/fabric-api/version/0.77.0+1.18.2)
  - 0.77.0+1.18.2
- [Fabric Language Kotlin](https://modrinth.com/mod/fabric-language-kotlin/version/1.13.9+kotlin.2.3.10)
  - 1.13.9+kotlin.2.3.10
- [Animatica](https://modrinth.com/mod/animatica/version/0.5+1.18.2)
  - 0.5+1.18.2
- [CIT Resewn](https://modrinth.com/mod/cit-resewn/version/1.1.1+1.18.2)
  - 1.1.1+1.18.2
- [cloth-config2](https://modrinth.com/mod/cloth-config/version/6.5.102)
  - 6.5.102
- [Continuity](https://modrinth.com/mod/continuity/version/2.0.2+1.18.2)
  - 2.0.2+1.18.2
- [Custom Entity Models](https://modrinth.com/mod/cem/version/0.7.1)
  - 0.7.1
- [Enhanced Block Entities](https://modrinth.com/mod/ebe/version/0.7.1+1.18.2)
  - 0.7.1+1.18.2
- [[ETF] Entity Texture Features](https://modrinth.com/mod/entitytexturefeatures/version/MbHYReOp)
  - 6.0.1
- [Sodium](https://modrinth.com/mod/sodium/version/mc1.18.2-0.4.1)
  - 0.4.1

Modが導入できたら、以下のうちいずれかに進んでください。  
あとから適用方法を切り替えることもできます。

- [自動で適用する場合](#自動で適用する場合)
  - 基本的にはバージョンを気にせず、**自動で最新のものを適用**できます。
  - **リソースパックの更新があった場合は、次の日の午前7時以降**に接続し直すことで、最新のバージョンのリソースパックを適用できます。
- [手動で適用する場合](#手動で適用する場合)
  - **自分でリソースパックを適用、更新する必要**があります。
  - **リソースパックの更新があった場合は、次の日を待たず**に最新のバージョンのリソースパックを適用できます。
  - [自動で適用する場合](#自動で適用する場合)の手順で適用できないときは、こちらをお試しください。

### 自動で適用する場合

1. Minecraftを起動してください。
2. 「マルチプレイ」のボタンをクリックしてください。
3. サーバーの一覧画面が表示されるので、整地鯖を選択してください。
4. 左下の「編集」ボタンをクリックしてください。
5. 「サーバーアドレス」の下にある「サーバーリソースパック」のボタンを以下のうちいずれかの表示になるまで何度もクリックしてください。
   - 「サーバーリソースパック：有効」: 整地鯖に接続する場合は、常に最新のリソースパックを自動でダウンロードして適用できます。
   - 「サーバーリソースパック：毎回確認」: 整地鯖に接続するたびに、リソースパックを有効にするか選ぶことができます。
6. 「完了」をクリックしてください。
7. 整地鯖に接続してください。

### 手動で適用する場合

1. [GitHubのRelease](https://github.com/GiganticMinecraft/OriginalResourcePack/releases/latest)を開いてください。
2. 「seichi_tex_v〇〇.〇〇.zip」をクリックしてください。
3. zipファイルを自分の好きなところに保存してください。
4. Minecraftを起動してください。
5. 「設定」ボタンをクリックしてください。
6. 「リソースパック」ボタンをクリックしてください。
7. 「リソースパックフォルダーを開く」ボタンをクリックしてください。
8. エクスプローラーでリソースパックを配置するフォルダが開くので、先程ダウンロードしたzipファイルをそこに移動してください。
9. Minecraftに戻ってください。
10. 「利用可能」の列に「Seichi.Click_Texture v〇〇.〇〇」が表示されていることを確認してください。
11. 「Seichi.Click_Texture v〇〇.〇〇」を選択してください。
12. 「Seichi.Click_Texture v〇〇.〇〇」のアイコンの上に右向きの三角形のボタンが表示されるので、クリックしてください。
13. 「Seichi.Click_Texture v〇〇.〇〇」が「選択中」に移動したことを確認してください。
14. 「完了」をクリックしてください。
15. もう一度「完了」をクリックしてください。
16. 整地鯖に接続してください。

## リソースパックが適用されないときは

- [ ] 1.18.2に対応していないバージョンの[前提Mod](#前提mod)を導入していませんか？
- [ ] 導入し忘れている前提Modはありませんか？
- [ ] 読み込まれていない前提Modはありませんか？
- [ ] （自動で適用している場合）[自動で適用する場合](#自動で適用する場合)の手順は完了していますか？
- [ ] （自動で適用している場合）[手動で適用する場合](#手動で適用する場合)の手順にしたがって、手動で適用しても状況は変わらないでしょうか？
- [ ] （手動で適用している場合）[手動で適用する場合](#手動で適用する場合)の手順は完了していますか？
- [ ] （手動で適用している場合）リソースパックのファイルは正しい場所にダウンロードできていますか？
- [ ] （手動で適用している場合）リソースパックのフォルダに古いバージョンと新しいバージョンのリソースパックのファイルがどちらもありませんか？
- [ ] リソースパックは最新のバージョンのものを使用していますか？
- [ ] Minecraft上でリソースパックは正しいものを選択していますか？
- [ ] Minecraft上で本リソースパックが一番上に位置していますか？

上記をすべて確認してもリソースパックが適用されない場合は、[整地鯖 お問い合わせフォーム](https://www.seichi.network/access)よりご連絡ください。

## 更新履歴、過去のバージョン

- 更新履歴は、[UpdatedLog.md](https://github.com/GiganticMinecraft/OriginalResourcePack/blob/main/UpdatedLog.md)から確認できます。
- 過去のバージョンのリソースパックは[GitHub Release](https://github.com/GiganticMinecraft/OriginalResourcePack/releases)からダウンロードできます。

## ライセンス

本リソースパックの著作権は本サーバーOwnerのunchamaが保有しています。本リソースパックを無断で改変再配布したり二次配布したりすることを一切禁じます。OSSではありませんのでご注意ください。詳細は[著作権ガイドライン](https://redmine.seichi.click/projects/public/wiki/Copyright_Guide#3%E7%AB%A0%E3%82%B5%E3%83%BC%E3%83%90%E3%83%86%E3%82%AF%E3%82%B9%E3%83%81%E3%83%A3)をご覧ください。

### 利用例

- 個人利用目的でダウンロードし、改変して使用する→OK
- 改変している、していないを問わず、本リソースパックをインターネット上へ再公開、他人に直接配布する→NG

## 開発者向け

本リソースパックは[GitHubリポジトリ](https://github.com/GiganticMinecraft/OriginalResourcePack)で管理・更新されています。

### 更新（コントリビュート）する方法

mainブランチから各自ブランチを作成し、その中で作業を行ってください。作業が完了したら、mainブランチに向けたPRを作成してください。

### リリースする方法

適宜管理者によって行われます。詳細については、[GitHub Wiki](https://github.com/GiganticMinecraft/OriginalResourcePack/wiki#%E3%83%AA%E3%83%AA%E3%83%BC%E3%82%B9%E6%96%B9%E6%B3%95)をご覧ください。

## 謝辞

テクスチャの提供等、本リソースパックの作成にご協力いただいた方々です。ありがとうございます。

- arakooAiry3Zkさん（Minestack内のGTテクスチャの修正をしてくださいました。）
- kouki21さん（木の斧のテクスチャを作成してくださいました。）
- 19moonさん（4周年記念GTテクスチャを作成してくださいました。）
- SpecialBoyWakaさん（GW、ハロウィン、クリスマスイベントと第3回・第4回整地大会の限定テクスチャを作成してくださいました。）
- nubasuさん（まいんちゃんと王冠の立体テクスチャ、5周年記念GTテクスチャを作成してくださいました。）
- eclipse_5306さん（サーバーアイコンのテクスチャを作成してくださいました。）
- shirotubuさん（クリスマス、お正月イベント限定テクスチャを作成してくださいました。）
- towa_256さん（GAEA Whitedayのテクスチャの修正をしてくださいました。）
- B_Makkuroさん、ploptawさん（お花見イベント限定テクスチャを作成してくださいました。）
- ploptawさん、aluM_8bitさん、Inumugi_331さん、Argon_7270さん（6周年記念GTテクスチャを作成してくださいました。）
- ploptawさん、aluM_8bitさん、Inumugi_331さん（7周年記念GTテクスチャを作成してくださいました。）
- NuaahBox514さん（8周年記念GTテクスチャを作成してくださいました。）
- ploptawさん（棒メニューのテクスチャを作成してくださいました。）
