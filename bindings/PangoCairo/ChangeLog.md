### 1.0.18

+ Update stack version to 12.10

### 1.0.17

+ Add an override to make sure that [`Cairo.FontOptions`](https://hackage.haskell.org/package/gi-cairo/docs/GI-Cairo-Structs-FontOptions.html) is always treated as boxed.

### 1.0.16

+ Remove enable-overloading flags, and use instead explicit CPP checks for 'haskell-gi-overloading-1.0', see [how to disable overloading](https://github.com/haskell-gi/haskell-gi/wiki/Overloading\#disabling-overloading).

### 1.0.12
Fix [#77](https://github.com/haskell-gi/haskell-gi/issues/77),
	changes the return value of
	[fontMapGetDefault](https://hackage.haskell.org/package/gi-pangocairo/docs/GI-PangoCairo-Interfaces-FontMap.html#v:fontMapGetDefault),
	[fontMapNew](https://hackage.haskell.org/package/gi-pangocairo/docs/GI-PangoCairo-Interfaces-FontMap.html#v:fontMapNew)
	and
	[fontMapNewForFontType](https://hackage.haskell.org/package/gi-pangocairo/docs/GI-PangoCairo-Interfaces-FontMap.html#v:fontMapNewForFontType)
	from
	[Pango.FontMap](https://hackage.haskell.org/package/gi-pango/docs/GI-Pango-Objects-FontMap.html#t:FontMap)
	to
	[PangoCairo.FontMap](https://hackage.haskell.org/package/gi-pangocairo/docs/GI-PangoCairo-Interfaces-FontMap.html#t:FontMap).