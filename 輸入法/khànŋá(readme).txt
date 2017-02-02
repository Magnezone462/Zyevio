１　安裝法　How to install　インストール方法　

下載「中州韻輸入法引擎」于 http://rime.im。安裝之，而複製三 .yaml 檔案（chetpheng.schema、chetpheng.dict、default.custom）於資料夾。

Download “Rime IME” from http://rime.im. Install it, then copy three .yaml files (chetpheng.schema, chetpheng.dict, default.custom) to the settings folder.

「中州韻輸入法引擎」を http://rime.im からダウンロードしてインストールしたのち，設定フォルダへ３つの .yaml ファイル（chetpheng.schema、chetpheng.dict、default.custom）をコピーしてください。

*資料夾在　settings folder is at　設定フォルダの場所は
(Mac) ~/Library/Rime
(Windows) %APPDATA%\Rime
(Linux) ~/.config/ibus/rime


２　開始使用法　How to start　使用開始方法

按 Ctrl+` 換輸入法，按 Ctrl+Shift+` 重新部署。

Enter Ctrl+` to choose the imput method. Enter Ctrl+Shift+` to deploy the data if it is the first time or after an update.

「Ctrl+`」で入力方式を選択し，「Ctrl+Shift+`」でデータを更新します（初回および更新時のみ）。ただし，日本語キーボードに於いては「`」キーそのものの入力にシフトキーが必須なため，入力方式を選択することができません。解決法は現在不明ですが，default.custom.yaml を書き換えることによって姑息的に方式を変えることができます。
なお，WindowsとLinuxではF4キーで「Ctrl+`」の代わりをすることが可能です。


３　輸入法　How to input　入力法　

打拼音，按上下鍵擇漢字，以空格鍵確之。
以按「v」「w」鍵能入 ⟨ŋ⟩ ⟨ə⟩ 。按「r」「f」「h」鍵於音節末入平聲、上聲、去聲。

After typing the letters, use up or down key or number keys to choose the word, press space key to confirm.
You can enter ⟨ŋ⟩ or ⟨ə⟩  with typing “v” or “w” keys respectively. Use “r”, “x” or “h” keys for inputting “level”, “rising”, or “departing” tones.

入力後の候補選択は数字キーまたは上下キーでおこない，スペースキーで確定します。リターン（エンター）キーは入力したキー（≠拼音）をそのまま出力します。シフト＋スペースキーで入力中の拼音をそのまま出力します。
（少なくともWindowsの場合は拼音出力はシフト＋エンター）

（例）
tavx＋スペースキー→黨
tavx＋リターンキー→tavx
tavx→シフトキー＋スペースキー→táŋ

キーの制約のため，⟨ŋ⟩ ⟨ə⟩ の入力は「v」「w」で代用できます。声調は，音節を入力したのち，「r」キーで平聲，「f」キーで上聲，「h」キーで去聲となります。
他にも，「g」キーが限定的に ⟨x⟩ となるなど，種種の表記ゆれを實裝してあります。


４　逆引き

`キー（日本語キーボードでは Shift+@）で，漢語拼音からの逆引きをおこなうことができます。




４　履歴

2017.02.02　改訂修正。
2016.12.17　微修正。
2016.05.01　反映改綴。
2016.02.20　加機能，増補詞典。
2016.02.16　改訂。
2016.02.15　微修正，増補詞典。
2016.02.14　増補詞典。
2016.02.13　微修正。
2016.02.12　作成，公開。