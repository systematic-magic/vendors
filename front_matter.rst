1. Typography
-------------

1.1. The following typographical characters presented anywhere in the article must be encoded in HTML notation:

+---------------------------+---------------+-----------------------+
|    Character(s)           |    Literal(s) |    HTML value(s)      |
+===========================+===============+=======================+
|    Cent (currency)        |    ¢          |    &#162;             |
+---------------------------+---------------+-----------------------+
|    Pound (currency)       |    £          |    &#163;             |
+---------------------------+---------------+-----------------------+
|    Section                |    §          |    &#167;             |
+---------------------------+---------------+-----------------------+
|    Copyright              |    ©          |    &#169;             |
+---------------------------+---------------+-----------------------+
|    Guillemets             |    « »        |    &#171; &#187;      |
+---------------------------+---------------+-----------------------+
|    Registered trademark   |    ®          |    &#174;             |
+---------------------------+---------------+-----------------------+
|    Degree(s)              |    °          |    &#176;             |
+---------------------------+---------------+-----------------------+
|    Plus/minus             |    ±          |    &#177;             |
+---------------------------+---------------+-----------------------+
|    Pilcrow (paragraph)    |    ¶          |    &#182;             |
+---------------------------+---------------+-----------------------+
|    Middle dot             |    ·          |    &#183;             |
+---------------------------+---------------+-----------------------+
|    Fractional half        |    ½          |    &#188;             |
+---------------------------+---------------+-----------------------+
|    En dash                |    –          |    &#8211;            |
+---------------------------+---------------+-----------------------+
|    Em (long) dash         |    —          |    &#8212;            |
+---------------------------+---------------+-----------------------+
|    Single quotes          |    ‘ ’        |    &#8216; &#8217;    |
+---------------------------+---------------+-----------------------+
|    Single low quote       |    ‚          |    &#8218;            |
+---------------------------+---------------+-----------------------+
|    Double low quote       |    „          |    &#8222;            |
+---------------------------+---------------+-----------------------+
|    Single & double daggers|    † ‡        |    &#8224; &#8225;    |
+---------------------------+---------------+-----------------------+
|    Prime & double prime   |    ′ ″        |    &#8242; &#8243;    |
+---------------------------+---------------+-----------------------+
|    Euro sign              |    €          |    &#8364;            |
+---------------------------+---------------+-----------------------+
|    Trademark              |    ™          |    &#8482;            |
+---------------------------+---------------+-----------------------+
|    Almost equal to        |    ≈          |    &#8776;            |
+---------------------------+---------------+-----------------------+
|    Not equal to           |    ≠          |    &#8800;            |
+---------------------------+---------------+-----------------------+
|    Bullet                 |    •          |    &#8226;            |
+---------------------------+---------------+-----------------------+


2. Article Title
----------------

2.1. The title must be in :ref:`sentence case<sentence_case>`.

2.2. There must be no period (.) at the end of the title. Exclamation (!) and question (?) marks are allowed.

2.4. The format of title must be as follows:

+---------------------------+-------------------------------------+
| Characteristics           | Value.                              |
+===========================+=====================================+
| Font family               | Arial, Helvetica, sans-serif        |
+---------------------------+-------------------------------------+
| Font size                 | 1.2em                               |
+---------------------------+-------------------------------------+
| Font weight               | 700                                 |
+---------------------------+-------------------------------------+
| Font color                | #ac2b31                             |
+---------------------------+-------------------------------------+

2.3. The following Latin terms must be written in italics: *in vivo, in vitro, in utero, in situ, via*. 
All other words/terms formatted by author in italics must be preserved in italics.

2.4. There must be PDF, HTML, Supplementary Files, Order a Reprint links below the title. Links must be hyperlinked.
Supplementary Files link is required only when article has supplementary files. Links must be separated from each other by space and pipe (|). See screenshot below for details.

2.5. The format of the links must be as follows:

+---------------------------+-------------------------------------+
| Characteristics           | Value                               |
+===========================+=====================================+
| Font family               | Arial, Helvetica, sans-serif        |
+---------------------------+-------------------------------------+
| Font size                 | 13px                                |
+---------------------------+-------------------------------------+
| Link color                | #4074c8                             |
+---------------------------+-------------------------------------+
| Link visited color        | #294a80                             |
+---------------------------+-------------------------------------+

.. image:: /_static/title_format.png
   :alt: Title format
   :scale: 60%																								


3. Author names
---------------

3.1. Author names in author list must be separated by commas (,). Last two author names in the list must be separated by "and" instead of a comma (,). No other separators allowed.

3.2. There must be **no** period (or any other punctuation mark) after the last author name.

.. image:: /_static/html_author_list_separ.png
   :alt: Author list separators
   :scale: 60%


3.3. Author names must comply to the following standards: 

	+  :sample:`FirstName LastName`
	+  :sample:`FirstName MN. LastName` (MN. are initials of middle names; up to 4 letters)
	+  :sample:`FirstName M.N. LastName` (M.N. are initials of middle names; up to 4 letters)
	+  :sample:`F. MiddleName LastName` (F. is an initial of first name)
	+  :sample:`F. MiddleName MiddleName LastName` (F. is initial of first name and there can any number of middle names)

Please note that last names can be compound, can have prepositions, suffixes, prefixes or be :ref:`mononyms<mononym>`. For example:

	- Compound last names: :sample:`Garcia-Closas, Gomez Jimenez`
	- Last name related prepositions: :sample:`Van den Brandt, van der Ent`
	- Suffixes: :sample:`Williams 3rd, Rowland Jr`
	- Prefixes: :sample:`McCann, O'Kelly`
	- Mononym: :sample:`Govindjee`


.. Important::
	
	LastName **cannot** be presented as initial (even if authors insist on this). LastName must always be presented in full.


If you see that author name does not comply to these standards, please contact corresponding author and ask to provide author name in correct format.

3.4. Format of author names must be as follows:

+---------------------------+-------------------------------------+
| Characteristics           | Value                               |
+===========================+=====================================+
| Font family               | Sans-serif                          |
+---------------------------+-------------------------------------+
| Font size                 | 12px                                |
+---------------------------+-------------------------------------+
| Font weight               | bold                                |
+---------------------------+-------------------------------------+


3.5. Each author name must have at least 1 affiliation number (i.e. number linked to the affiliation text). One author name can have a few affiliation numbers.

.. image:: /_static/html_aff_texts_and_authors.png
	:scale: 60%
	:alt: Affiliation texts and authors

If there is only one affiliation text for all authors, then each author name must have "1" next to it. 

.. image:: /_static/html_one_affiliation_all_auth.png
   :alt: One affiliation for all authors
   :scale: 60%


3.6. Author name must have "author note" symbol (i.e. symbol linked to author note) together with affiliation number, if article contains author note. The following symbols are allowed as author note symbol:

+===========================+===============+=======================+
|    Priority               |    Symbol     |    HTML value(s)      |
+===========================+===============+=======================+



|    1                      |               |    &#42;              |
+---------------------------+---------------+-----------------------+
|    2                      |               |    &#42;&#42;         |
+---------------------------+---------------+-----------------------+
|    3                      |               |    &#42;&#42;&#42;    |
+---------------------------+---------------+-----------------------+
|    4                      |    #          |    &#35;              |
+---------------------------+---------------+-----------------------+
|    5                      |    †          |    &#8224;            |
+---------------------------+---------------+-----------------------+


3.7. The default author note symbol is \*. If there are more than one author note, then symbols must be used in accordance with the priority spcified in the table above (i.e. first author note should be denoted by \*, second - by \*\*, third - by \*\*\* etc.)

3.8. Affiliation numbers and author note symbols for one author must be separated by commas (,). No other separator is allowed.

3.9. The format of affiliation number and/or author note symbol must be as follows:

+---------------------------+-------------------------------------+
| Characteristics           | Value                               |
+===========================+=====================================+
| Font family               | Sans-serif                          |
+---------------------------+-------------------------------------+
| Font size                 | 10px                                |
+---------------------------+-------------------------------------+
| Font weight               | bold                                |
+---------------------------+-------------------------------------+
| Vertical-align            | super                               |
+---------------------------+-------------------------------------+
| Font color                | #BD1B3C                             |
+---------------------------+-------------------------------------+


.. image:: /_static/html_affiliation_numbers.png
   :alt: Affiliation Numbers



