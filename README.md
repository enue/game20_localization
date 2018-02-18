# 幻想四倍剣^2 翻訳辞書
# GensoYonbaiKen^2 translation data

# Links
## Site
http://moetoku.sakura.ne.jp/gsq2/manual.html

## Steam
http://store.steampowered.com/app/806720/

# Instructions

## 1. modify Localization.json

add translations.

e.g.
```
"設定.Caption":
{
   "jpn":"設定",
   "eng":"Settings", // <- this
},
```

## 2. replace json

GensoYonbaiKen2 contains Localization.json.  
`gsq2_Data/StreamingAssets/Localization.json`

replace it with your modified one.

## 3. modify language.txt

The game contains language.txt. Open it.  
And replace `jpn` with your language. e.g.`eng`

Start the game, it will render your translations.

And create pull request!
