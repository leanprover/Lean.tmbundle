# Lean.tmbundle
A [TextMate](http://macromates.com) bundle for the [Lean](https://leanprover.github.io) language. 
This is also used by [github/linguist](https://github.com/github/linguist) to syntax-highlight Lean code in [github.com](http://github.com). Everytime [github/linguist](https://github.com/github/linguist) is newly released, github pulls the latest version of this repository.


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

 - Note: TextMate saves grammar files (`.tmLanguage`) in Apple's PLIST format, which makes it very difficult to edit them outside of TextMate. It rejects to save any mal-formed/incomplete files. While saving grammar files, TextMate also clean up any comments inside of them.

## Resources
 - TextMate's documentation on language grammars: http://manual.macromates.com/en/language_grammars
 - Test grammars using Lightshow: https://github-lightshow.herokuapp.com
   - Example: [library/algebra/binary.lean](https://github-lightshow.herokuapp.com/?utf8=%E2%9C%93&scope=from-url&grammar_url=https%3A%2F%2Fraw.githubusercontent.com%2Fleanprover%2FLean.tmbundle%2Fmaster%2FSyntaxes%2FLean.tmLanguage&grammar_text=&code_source=from-url&code_url=https%3A%2F%2Fraw.githubusercontent.com%2Fleanprover%2Flean%2Fmaster%2Flibrary%2Falgebra%2Fbinary.lean&code=)
