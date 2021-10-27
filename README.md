Describe vowelFinder();

Test: "It recognizes a single vowel and returns it"
code: vowelFinder("a");
Expected Output: "a"

Test: "It recognizes an uppercase vowel"
code: vowelFinder("A");
Expected Output: "A"

Test: "It recognizes a vowel in a multi-character word"
code: vowelFinder("cat");
Expected Output: "a"

Test: "It recognizes an uppercase vowel in a multi-character word"
code: vowelFinder("Aardvark");
Expected Output: "A"

Describe pigLatin();

Test: "It will recognize a single vowel"
code: firstLetterVowelOrCons("a");
Expected Output: True

Test: "It will recognize a single consonant"
code: firstLetterVowelOrCons("C");
Expected Output: False

Test: "It will ignore non alphabetical characters since they can't be vowels or consonants"
code: firstLetterVowelOrCons("%");
Expected Output: 
\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\

Test: "It will recognize if it is a string with characters"
code: pigLatin("")
Expected Output: False

Test: "It will add way to the end of a word"
code: pigLatin("dog");
Expected Output; "dogway"

Test: "It will add way to the end of word that starts a vowel"
code: pigLatin("and")
Expected output: "andway"

Test: "It will move all first consecutive consonants to the end of a word"
code: pigLatin("code")
Expected output: "odec" 

Test: "It will move all first consecutive consonants to the end of a word and add 'ay'"
code: pigLatin("code")
Expected output: "odec" 

Test: "it will move the qu to the end of a word starting with 'QU'"
code: pigLatin("quick")
Expected output: "ickqu"

Test: "it will move the qu to the end of a word starting with 'qu' and add 'ay' to the end"
code: pigLatin("quick")
Expected output: "ickquay"







