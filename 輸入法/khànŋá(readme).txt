１　安裝法　How to install　インストール方法　

得「中州韻輸入法引擎」自 http://rime.im，安裝之，複製三 .yaml 檔案（chetpheng.schema、chetpheng.dict、default.custom）於資料夾。

從 http://rime.im 下載「中州韻輸入法引擎」，安裝它，複製三 .yaml 檔案（chetpheng.schema、chetpheng.dict、default.custom）到資料夾。

Download “Rime IME” from http://rime.im, install it, then copy three .yaml files (chetpheng.schema, chetpheng.dict, default.custom) to settings folder.

「中州韻輸入法引擎」を http://rime.im からダウンロードしてインストールしたのち，設定フォルダへ３つの .yaml ファイル（chetpheng.schema、chetpheng.dict、default.custom）をコピーしてください。

*資料夾在　settings folder is at　設定フォルダの場所は
(Mac) ~/Library/Rime
(Windows) %APPDATA%\Rime
(Linux) ~/.config/ibus/rime


２　開始使用法　How to start　使用開始方法

按 Ctrl+` 換輸入法，按 Ctrl+Shift+` 重新部署。

請閲讀 https://github.com/rime/home/wiki/UserGuide。

Enter Ctrl+` to choose the imput method. Enter Ctrl+Shift+` to deploy the data if it is the first time or after an update.

「Ctrl+`」で入力方式を選擇し，「Ctrl+Shift+`」でデータを更新します（初回および更新時のみ）。たゞし，日本語キーボードに於いては「`」キーそのものゝ入力にシフトキーが必須なため，入力方式を選擇することができません。解決法は現在不明ですが，default.custom.yaml を書き換へることによって姑息的に方式を變へることができます。


３　輸入法　入力法　How to input

打拼音，按上下鍵擇字，以空格鍵確之。
以按「v」「w」鍵能入 ⟨ŋ⟩ ⟨ə⟩ 。按「r」「x」「h」鍵於音節末入平聲、上聲、去聲。

請閲讀 https://github.com/rime/home/wiki/UserGuide。

入力後の候補選擇は數字キーまたは上下キーでおこなひ，スペースキーで確定します。リターン（エンター）キーは入力したキー（≠拼音）をそのまゝ出力します。シフト＋スペースキーで入力中の拼音をそのまゝ出力します。

（例）
tavx＋スペースキー→黨
tavx＋リターンキー→tavx
tavx→シフトキー＋スペースキー→táŋ

キーの制約のため，⟨ŋ⟩ ⟨ə⟩ の入力は「v」「w」で代用できます。聲調は，音節を入力したのち，「r」キーで平聲，「x」キーで上聲，「h」キーで去聲となります。
他にも，「g」キーが限定的に ⟨gh⟩ となるなど，種種の表記ゆれを實裝してあります。

After typing the letters, use up or down key or number keys to choose the word, press space key to confirm.
You can enter ⟨ŋ⟩ or ⟨ə⟩  with typing “v” or “w” keys respectively. Use “r”, “x” or “h” keys for inputting “level”, “rising”, or “departing” tones.



４　履歴

2016.12.17　微修正。
2016.05.01　反映改綴。
2016.02.20　加機能，増補詞典。
2016.02.16　改訂。
2016.02.15　微修正，増補詞典。
2016.02.14　増補詞典。
2016.02.13　微修正。
2016.02.12　作成，公開。