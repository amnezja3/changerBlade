# changerBlade
Biblioteka changerBlade to zbiór funkcji, które pomagają w przetwarzaniu języka naturalnego w języku polskim. Biblioteka zawiera funkcje do sprawdzania, czy dany znak jest samogłoską, do określania rodzaju i liczby słowa, a także do pobierania sufiksu słowa.

Funkcje biblioteki changerBlade:

    sam_g(): Sprawdza, czy dany znak jest samogłoską.
    sufix(): Pobiera sufiks słowa.
    check_v_list(): Porównuje dwie listy.
    kind_sex_word(): Określa rodzaj słowa.
    lpm(): Określa liczbę słowa.

Jak korzystać z biblioteki changerBlade?
Aby korzystać z biblioteki changerBlade, należy ją najpierw zaimportować do swojego kodu. Można to zrobić za pomocą następującego kodu:
Python

from changerBlade import *

Po zaimportowaniu biblioteki, można zacząć korzystać z jej funkcji. Na przykład, aby sprawdzić, czy dany znak jest samogłoską, można użyć następującego kodu:
Python

import changerBlade

is_vowel = changerBlade.sam_g("a")
print(is_vowel)

Wynik:
True

Przykłady użycia biblioteki changerBlade:
Oto kilka przykładów użycia biblioteki changerBlade:
    Sprawdzenie, czy słowo jest rzeczownikiem rodzaju męskiego:

Python

import changerBlade
word = "dom"
kind_sex_word = changerBlade.kind_sex_word(word)
print(kind_sex_word)

Wynik:
M

Pobranie liczby słowa:

Python

import changerBlade

word = "domy"
lpm = changerBlade.lpm(word)
print(lpm)

Wynik:
LM

Wnioski
Biblioteka changerBlade jest przydatnym narzędziem dla osób zajmujących się przetwarzaniem języka naturalnego w języku polskim. Biblioteka zawiera funkcje, które mogą być wykorzystane w wielu zadaniach, takich jak sprawdzanie poprawności gramatycznej zdań, generowanie nowych zdań lub tłumaczenie języków.

Dodatkowe informacje
Biblioteka changerBlade jest dostępna na GitHubie. Kod źródłowy biblioteki jest rozpowszechniany na licencji MIT.

Kontakt
Jeśli masz jakieś uwagi lub sugestie dotyczące biblioteki changerBlade, skontaktuj się ze mną na mój adres email.

-----------------------------------------------------------------------------------

The changerBlade library is a collection of functions that assist in natural language processing in the Polish language. The library includes functions for checking if a given character is a vowel, determining the gender and number of a word, and extracting the suffix of a word.

Functions in the changerBlade library:

    sam_g(): Checks if a given character is a vowel.
    sufix(): Retrieves the suffix of a word.
    check_v_list(): Compares two lists.
    kind_sex_word(): Determines the gender of a word.
    lpm(): Determines the number of a word.

How to use the changerBlade library?
To use the changerBlade library, you first need to import it into your code. You can do so using the following code:

python

from changerBlade import *
Once the library is imported, you can start using its functions. For example, to check if a given character is a vowel, you can use the following code:

python

import changerBlade
is_vowel = changerBlade.sam_g("a")
print(is_vowel)

Result:
graphql
True

Examples of using the changerBlade library:
Here are a few examples of how to use the changerBlade library:

    Checking if a word is a masculine noun:

python

import changerBlade
word = "dom"
kind_sex_word = changerBlade.kind_sex_word(word)
print(kind_sex_word)

Result:
M
    Retrieving the number of a word:

python
import changerBlade
word = "domy"
lpm = changerBlade.lpm(word)
print(lpm)

Result:
LM

Conclusion
The changerBlade library is a valuable tool for individuals involved in natural language processing in the Polish language. The library contains functions that can be used in various tasks, such as checking the grammatical correctness of sentences, generating new sentences, or translating languages.

Additional Information
The changerBlade library is available on GitHub, and its source code is distributed under the MIT license.

Contact
If you have any feedback or suggestions regarding the changerBlade library, please contact me at my email address.
