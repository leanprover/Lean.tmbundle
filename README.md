# Lean.tmbundle
A [TextMate](http://macromates.com) bundle for the [Lean](https://leanprover.github.io) language. 
This is also used by [github/linguist](https://github.com/github/linguist) to syntax-highlight Lean code in [github.com](http://github.com).

## How to Install

After installing [TextMate2](http://macromates.com/download), please execute the following instructions:

```bash
mkdir -p ~/Library/Application\ Support/Avian/Bundles
cd ~/Library/Application\ Support/Avian/Bundles
git clone https://github.com/leanprover/Lean.tmbundle.git
```

## How to Edit

 - Open TextMate
 - Bundles >> Edit Bundles

    ![screen shot 2015-02-22 at 10 44 54 am](https://cloud.githubusercontent.com/assets/403281/6319147/17a5e8d4-ba80-11e4-885d-d71a16a1d5ac.png)
 
 - Lean >> Language Grammars
 
    ![screen shot 2015-02-22 at 10 45 20 am](https://cloud.githubusercontent.com/assets/403281/6319148/17ac14c0-ba80-11e4-8c58-59c04fde9b45.png)

 - Note: TextMate saves grammar files (`.tmLanguage`) in Apple's PLIST format, which makes it very difficult to edit them outside of TextMate.

## Resources
 - TextMate's documentation on language grammars: http://manual.macromates.com/en/language_grammars
 - Test grammars using Lightshow: https://github-lightshow.herokuapp.com
