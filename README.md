# roman2nepali / latin2nepali -- Romanized to nepali unicode characters.
## Please note that this is work in progress.

# Why ?
Only few years ago we used custom mapped fonts for writing in different language. This method  
maps keys to  letters in respective lanugaages. However, this method was too cumbersome. You needed to have fonts 
installed in the destination computer also. Then came unicode, which can accomodate any type of encoding, if  they are 
registered in the unicode mappings. Nowadays, almost all systems and text processors support unicode. Wouldn't it be awesome
if you can write in universal unicode system and also not have to remember key mappings?

# Transliteration vs Transaltion:
Transliteration means conversion based on how words sound phonetically eg. "dhanyabaad" written with latin characters
means "धन्यबाद" in Nepali, which is based on devnagari symbols. In a nutshell, this is a tool that can help make 
writing easy by not having to remember keymaps for each characters. This is not the same as tranlastion, which
means source and the destination have same meaning. It requires higher lever of understanding of language.


# Google Input Tools

There are other tools such as Google Input Tools https://www.google.com/inputtools/try/ . It  remembers your corrections 
and maintains a custom dictionary for new or uncommon words and names. It also generate possible corrections as options.
However, Google discontinued supoort to their API a few year aog. Fear not, I found  a repo that re-wrote some portions 
of google's API https://github.com/KSubedi/transliteration-input-tools/tree/master/src

# Resources: 
1. https://en.wikipedia.org/wiki/Devanagari_transliteration

2. https://github.com/libindic/Transliteration/blob/master/libindic/transliteration/core.py
