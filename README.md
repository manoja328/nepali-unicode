# roman2nepali / latin2nepali -- Romanized to nepali unicode characters.

# Demo: https://www.manojacharya.com/nepali/

# Why ?
Only a few years ago we had to install fonts to write in any new language. They worked by  
mapping ASCII keys to the respective languages. However, this method was too cumbersome. If you didnot
have correct fonts installed you would  get garbage. Then comes Unicode which has codes for almsot all
languages around the world. Nowadays, almost all softwares and text processors support unicode. Wouldn't it be
awesomeif you can write in universal unicode system and also not have to remember key mappings?

# Transliteration vs Transaltion:
Transliteration means conversion based on how words sound phonetically eg. "dhanyabaad" written with latin characters
means "धन्यबाद" in Nepali, a script based on Devnagari symbols. In a nutshell, this is a tool makes 
writing easy by not having to remember keymaps for each characters. This is different from tranlastion, which
means input and the output have same meaning. It requires higher level of understanding of language.


# Google Input Tools

There are other tools such as Google Input Tools https://www.google.com/inputtools/try/ for transliteration. It  has more
features like it remembers your corrections and maintains a custom dictionary for new or uncommon words and names. 
It also generate alternate corrections as options.
However, google discontinued supoort to this API. I found  a repo that re-wrote some portions 
of google's API https://github.com/KSubedi/transliteration-input-tools/tree/master/src

# Please note that this is a work in progress.

# TODO: 

1. Fuzzy options during typing.
3. Make a better UI. :smile:
3. Add better grammar support.
4. Add more edge cases.
5. Learn collaboratively using a simple ML.  Show the most frequent choosen transliterations.

# Resources: 

1. https://en.wikipedia.org/wiki/Devanagari_transliteration

2. https://github.com/libindic/Transliteration/blob/master/libindic/transliteration/core.py
