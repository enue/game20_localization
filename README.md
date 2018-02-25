# 幻想四倍剣^2 翻訳辞書
# GensoYonbaiKen^2 translation data

# Links
## Site
http://moetoku.sakura.ne.jp/gsq2/manual.html

## Steam
http://store.steampowered.com/app/806720/

# Instructions

## 1. Create a JSON file for your language

Copy `jpn.json` to a new file for your language, e.g. `eng.json`, and translate the strings on the right-hand side.

e.g.
```json
    "設定.Caption": "Settings", // <- this
```

## 2. Add the new JSON file to the game

Place the file into the `gsq2_Data/StreamingAssets/` directory of GensoYonbaiKen2.

## 3. modify language.txt

The game contains language.txt. Open it.
And replace `jpn` with your language. e.g. `eng`

Start the game, it will render your translations.


And create pull request!
