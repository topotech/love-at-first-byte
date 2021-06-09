# Love-at-first-byte

## Recipes
- English
  - Baking
    - Cookies
      - [Mrs Fields Choc-Chip Cookies](baking/cookies/mrs_fields_choc_chip_cookies.md)

## Introduction
A journey of finding the best recipes through an iterative process.

> _It all begins and ends with a byte of delicious food._

Fork this repo to develop your own versions of the recipes.

Want to contribute? Submit a PR to provide suggestions to these recipes!

## Specification used
The format I pretend to use is based on both, [Kryptonat's](https://github.com/kryptonat) usage of CommonMark, and [Vikingcode's](https://github.com/vikingcode/vikingcode.github.io/blob/master/yumml.md) YumML language. Here's a transformation of Vikingcode's [example](http://web.archive.org/web/20131201041222im_/http://vikingco.de/yumml_example_recipe_basic.txt) into what I will use.

### Example

	# Mrs Fields Choc-Chip Cookies
	*Date: 2011-09-01*\
	*Time: 25 minutes*\
	*Servings:*
	
	## Ingredient
	- Plain flor `2.5 cups`
	- Bi-carb of soda `0.5 tsp`
	- Salt `0.25 tsp`
	- Dark brown sugar `0.75 cup`
	- White sugar `0.75 cup`
	- Margarine `0.5 cup`
	- Egg whites `3 units`
	- Vanilla `2 tsp`
	- Choc chips `3 cups`
	- Golden Syrup `2 tbs`
	
	## Instructions
	
	### Made-up subdivision 1
	- Mix flour, bi-carb soda, and salt in a large bowl.
	- Blend sugars with electric mixer, add margarine to form a grainy paste.
	
	### Made-up subdivision 3
	- In a small bowl, beat egg whites until fluffy.
	- Add egg, Golden Syrup and vanilla to sugar mixture, stir until smooth.
	
	### Final steps
	- Add to flour mix and mix in choc chips.
	- Blend on low speed until all combined.
	- Bake on ungreased trays for 18-20 minutes at 160C.
	- Transfer to cooling tray straight away.
	![Cookies photo.](https://upload.wikimedia.org/wikipedia/commons/6/69/Berchemse_Boterkoekjes.png)\
 	*In the image: Totally unrelated finished cookies.*
	
	## References
	- Here
	- be
	- dragons.
	
	## Notes
	- Foo
	- Bar

### Explanation
- The name goes in the first line, and is marked by a Header 1 with a single hash `#`.
- The second line contains the date of the recipe, following a YYYY-MM-DD format, written between asterisks `*` and finishing with a backslash `\`.
- The third line has the estimated time. Same markings as before. Leave empty if you don't know.
- The fourth line has the estimated servings. Same instructions as before.
- The ingredients section is marked with by a Header 2 with `##`.
- The ingredients are listed using a dash `-` and the units are written inside backquotes (``` - Ingredient name  `NUMBER Units` ```).
- Instructions are listed in a similar manner, and can be sub-divided with Header 3 (`###`).
- You can add images inside the instructions sections (`![Caption](direct_link.jpg)`) and footers in cursive (`*Footer*`).
- Optionallym you can credit the references you used for the recipe and add notes.

### Reasoning
The idea is having a human readable specfication which is compatible with CommonMark (used by GitHub), and which is easy to parse and has the same level of detail as basic and optional YumML. Also, following this rules will make it easier to control the different changes between versions.

# Credits
- [Original idea](https://github.com/kryptonat/love-at-first-byte) by [Kryptonat](https://github.com/kryptonat).
- Based on [Vikingcode's](https://github.com/vikingcode/vikingcode.github.io/blob/master/yumml.md) YumML language.
- Chungnho was the one who used the README as [a recipe index](https://github.com/chungnho/love-at-first-byte).

