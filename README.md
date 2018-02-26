# 幻想四倍剣^2 翻訳辞書
# GensoYonbaiKen^2 translation data

# Links
## Site
http://moetoku.sakura.ne.jp/gsq2/manual.html

## Steam
http://store.steampowered.com/app/806720/

# Instructions

  If you are not a developer, jump to #4.

## 1. Copy Localization.json

  Copy `Localization.json` in new language directory.

  Files in this repo will be like this.
```
deu/Localization.json
eng/Localization.json
Localization.json
README.md
```

## 2. Modify your Localization.json

Edit the `xxx/Localization.json` and add translations.  

e.g.
```
"設定.Caption":
{
   "jpn":"設定",
   "eng":"Settings", // <- this
},
```


## 3. Create pull request!

## 4. Replace json

GensoYonbaiKen2 contains Localization.json.  
`gsq2_Data/StreamingAssets/Localization.json`

Replace it with your modified one.

## 5. Modify language.txt

The game contains language.txt. Open it.  
And replace `jpn` with your language. e.g. `eng`

Start the game, it will render your translations.
