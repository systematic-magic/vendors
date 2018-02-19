
.. role:: und

.. role:: sample


1. Typography
-------------

1.1. The following typographical characters presented anywhere in the article must be encoded in HTML notation:

+---------------------------+---------------+-----------------------+
|    Character(s)           |    Literal(s) |    HTML value(s)      |
+===========================+===============+=======================+
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
|    Fractional half        |    ½          |    &#188;             |
+---------------------------+---------------+-----------------------+
|    En dash                |    –          |    &#8211;            |
+---------------------------+---------------+-----------------------+
|    Em (long) dash         |    —          |    &#8212;            |
+---------------------------+---------------+-----------------------+
|    Single quotes          |    ‘ ’        |    &#8216; &#8217;    |
+---------------------------+---------------+-----------------------+
|    Single dagger          |    †          |    &#8224;            |
+---------------------------+---------------+-----------------------+
|    Double daggers         |    ‡          |    &#8225;            |
+---------------------------+---------------+-----------------------+
|    Prime                  |    ′          |    &#8242;            |
+---------------------------+---------------+-----------------------+
|    Double prime           |    ″          |    &#8243;            |
+---------------------------+---------------+-----------------------+
|    Trademark              |    ™          |    &#8482;            |
+---------------------------+---------------+-----------------------+
|    Almost equal to        |    ≈          |    &#8776;            |
+---------------------------+---------------+-----------------------+
|    Not equal to           |    ≠          |    &#8800;            |
+---------------------------+---------------+-----------------------+


2. Article Title
----------------

2.1. The title must be in :ref:`sentence case<sentence_case>`.

2.2. There must be no period (.) at the end of the title. Exclamation (!) and question (?) marks are allowed.

2.4. The format of title must be as follows:

+---------------------------+-------------------------------------+
| Characteristics           | Value                               |
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
All other words/terms formatted in italics by author must be preserved in italics.

2.4. There must be PDF, HTML, Supplementary Files, Order a Reprint links below the title. Links must be hyperlinked.
Supplementary Files link is required only when article has supplementary files. Links must be separated from each other by space and pipe (|). See screenshot below for details.


.. image:: /_static/title_format.png
   :alt: Title format
   :scale: 60%																								



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

3.4. Author titles and degrees (e.g. Dr., Ph.D., M.D., etc.) are not allowed.


3.5. Format of author names must be as follows:

+---------------------------+-------------------------------------+
| Characteristics           | Value                               |
+===========================+=====================================+
| Font family               | Sans-serif                          |
+---------------------------+-------------------------------------+
| Font size                 | 12px                                |
+---------------------------+-------------------------------------+
| Font weight               | bold                                |
+---------------------------+-------------------------------------+
| Font color                | #333                                |
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

+---------------------------+---------------+-----------------------+
|    Priority               |    Symbol     |    HTML value(s)      |
+===========================+===============+=======================+
|    1                      |    \*         |         \*            |
+---------------------------+---------------+-----------------------+
|    2                      |    \*\*       |         \*\*          |
+---------------------------+---------------+-----------------------+
|    3                      |    \*\*\*     |         \*\*\*        |
+---------------------------+---------------+-----------------------+
|    4                      |    #          |         #             |
+---------------------------+---------------+-----------------------+
|    5                      |    †          |    &#8224;            |
+---------------------------+---------------+-----------------------+


3.7. The default author note symbol is \*. If there are more than one author note, then symbols must be used in accordance with the priority spcified in the table above (i.e. first author note should be denoted by \*, second - by \*\*, third - by \*\*\* etc.)

3.8. Affiliation numbers and author note symbols must be separated by commas (,). No other separator is allowed.

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


4. Affiliation text
-------------------

4.1. Each affiliation must be denoted by separate text number. If you see an affiliation text containing more than one country, then it is a good indication that you see several affiliation texts grouped together. This must be corrected. As a rule of thumb: one affiliation text should have one number.

.. image:: /_static/html_2_texts_1_number.png
   :alt: One affiliation for all authors
   :scale: 55%

In case you find several affiliation texts for one text number, please contact corresponding author and ask to provide correct affiliation texts and author affiliation numbers.

4.2. Each author note text must be denoted by separate symbol (see table in point 3.6 for the details regarding symbols).

.. image:: /_static/html_author_notes.png
   	:alt: Author Notes
	:scale: 45%


4.3. The format of affiliation number and/or author note symbol must be as follows:

+---------------------------+-------------------------------------+
| Characteristics           | Value                               |
+===========================+=====================================+
| Font family               | Sans-serif                          |
+---------------------------+-------------------------------------+
| Font size                 | 10px                                |
+---------------------------+-------------------------------------+
| Font weight               | normal                              |
+---------------------------+-------------------------------------+
| Vertical-align            | super                               |
+---------------------------+-------------------------------------+
| Font color                | #BD1B3C                             |
+---------------------------+-------------------------------------+


4.4. There must be no separators between affiliation text number and affiliation text itself (space is allowed). 

.. image:: /_static/html_affiliation_numbers_new.png
   :alt: Affiliation Numbers


4.5. Each author must have at least one affiliation text (several affiliation text for 1 author are allowed). If there are author notes, then each author note should be linked to related author(s).


4.6. The format of affiliation text and/or author note text must be as follows:

+---------------------------+-------------------------------------+
| Characteristics           | Value                               |
+===========================+=====================================+
| Font family               | Arial, Helvetica, sans-serif        |
+---------------------------+-------------------------------------+
| Font size                 | 12px                                |
+---------------------------+-------------------------------------+
| Font weight               | normal                              |
+---------------------------+-------------------------------------+
| Font color                | #221f22                             |
+---------------------------+-------------------------------------+


4.7. Authors are free to provide affiliation texts having any elements (e.g. University, School, Department, Lab, Hospital, etc) in any sequence they like. However certain rules apply to affiliation texts:

	- Affiliation text must contain at least 2 sections:
	|	1. Deparment and/or division and/or lab and/or school etc.
	|	2. Institution

	| Note that there can be affiliations for non-academic institutions (such as companies). In such cases, affiliation text can contain just a company name.
	
	.. image:: /_static/html_aff_text_non_academ.png
		:alt: Affiliation Text Non-Academic


	- NO street addresses and house numbers must be included in affiliation texts.

	- Both country and city names must be present in affiliation texts.

	- Country and city names must NOT be written in all CAPS (capital letters).

	- Both full names and abbreviations (two capital letters) are allowed for US states. However, they must be used consistently: either all affiliation texts have all states abbreviated or all states are spelled out. 

	.. image:: /_static/html_usa_state_name.png
	   :alt: Affiliation Numbers
	  
	
	- Zip codes are optional element of affiliation texts. However, they must be used consistently: either all affiliation texts have zip codes or none.

	If one or more affiliation texts does not have zip code, then remove zip code from all texts. 

	- Only commas must be used to separate parts of affiliation text. No other separators are allowed. Zip code can be separated from state or city name by space (however it should be used consistently: either space used for zip codes in all affiliations or in none).

	.. image:: /_static/html_aff_text_structure.png
	   :alt: Affiliation text structure

	.. image:: /_static/html_aff_text_structure_non-us.png
	   :alt: Affiliation text structure


4.8. Only "Current address:" or "Present address:" are allowed (but not mandatory) at the beginning of affiliation text (alternatives like "Current/Present address:" are NOT allowed). Word "address" should be followed by colon (:). Affiliation text containing "Current address:" or "Present address:" must have affiliation text number (not symbol).

.. image:: /_static/html_current_address.png
	:alt: Affiliation text structure


4.9. There must be no punctuation marks at the end of affiliation text and/or author note text.


5. Correspondence
-----------------

5.1. Correspondence section must have a title “Correspondence to:”. It must start with capital letter and be followed by colon (:).

5.2. The format of "Correspondence to:" title must be as follows:

+---------------------------+-------------------------------------+
| Characteristics           | Value                               |
+===========================+=====================================+
| Font family               | Sans-serif                          |
+---------------------------+-------------------------------------+
| Font size                 | 12px                                |
+---------------------------+-------------------------------------+
| Font weight               | bold                                |
+---------------------------+-------------------------------------+
| Font color                | #777                                |
+---------------------------+-------------------------------------+


5.3. There can be one of more correspondence lines Correspondence section. The format of correspondence line must be as follows:

+---------------------------+-------------------------------------+
| Characteristics           | Value                               |
+===========================+=====================================+
| Font family               | Courier New                         |
+---------------------------+-------------------------------------+
| Font size                 | 0.85em                              |
+---------------------------+-------------------------------------+
| Font weight               | normal                              |
+---------------------------+-------------------------------------+
| Font color                | #333                                |
+---------------------------+-------------------------------------+


5.4. Name of author in correspondence line must fully match name in author list (it must be exact match, i.e. middle name initials must also match, if present).

5.5. Author name must NOT contain titles and/or degrees (e.g. Dr., Ph.D., M.D., etc.).

5.6. Correspondence line must consist of the following elements in the following order:

	|	:sample:`Author Name, email:` :und:`email@address.com`

5.7. There must be no commas (,) or "or" or other separators between several correspondence lines:

	|	:sample:`Author Name One, email:` :und:`emailone@address.com` 
	|	:sample:`Author Name Two, email:` :und:`emailtwo@address.com`

5.8. Email addresses must be separated by a comma, if one author has a few email addresses:

	|	:sample:`Author Name, email:` :und:`emailone@address.com`, :und:`emailtwo@address.com`

5.9. Email address must be hyperlinked.



6. Keywords
-----------

6.1. Keywords section must have a title “Keywords:”. It must start with capital letter and be followed by colon (:).

6.2. The format of "Keywords:" title must be as follows:

+---------------------------+-------------------------------------+
| Characteristics           | Value                               |
+===========================+=====================================+
| Font family               | Sans-serif                          |
+---------------------------+-------------------------------------+
| Font size                 | 12px                                |
+---------------------------+-------------------------------------+
| Font weight               | bold                                |
+---------------------------+-------------------------------------+
| Font color                | #777                                |
+---------------------------+-------------------------------------+

6.3. There can be only one keywords line in Keywords section. The format of keywords line must be as follows:

+---------------------------+-------------------------------------+
| Characteristics           | Value                               |
+===========================+=====================================+
| Font family               | Sans-serif    					  |
+---------------------------+-------------------------------------+
| Font size                 | 11px                                |
+---------------------------+-------------------------------------+
| Font weight               | bold                                |
+---------------------------+-------------------------------------+
| Font style                | italic                              |
+---------------------------+-------------------------------------+
| Font color                | #000                                |
+---------------------------+-------------------------------------+


6.4. Keywords must be written in lower case, unless proper nouns or scientific terms. 

6.5. Keywords must be separated by semicolons (;).
	
	.. image:: /_static/html_keywords.png
   		:alt: Keywords
		:scale: 60%


6.6. Article must have at least 1 and not more than 5 keywords.

6.7. There must be no punctuation marks at the end of keywords line.



7. Abbreviations
----------------

7.1. Abbreviations section must have a title "Abbreviations:". It must start with capital letter and be followed by colon (:).

7.2. The format of "Abbreviations:" title must be as follows:

+---------------------------+-------------------------------------+
| Characteristics           | Value                               |
+===========================+=====================================+
| Font family               | Sans-serif                          |
+---------------------------+-------------------------------------+
| Font size                 | 12px                                |
+---------------------------+-------------------------------------+
| Font weight               | bold                                |
+---------------------------+-------------------------------------+
| Font color                | #777                                |
+---------------------------+-------------------------------------+

7.3. There can be only one keywords line in Keywords section. The format of keywords line must be as follows:

+---------------------------+-------------------------------------+
| Characteristics           | Value                               |
+===========================+=====================================+
| Font family               | Sans-serif    					  |
+---------------------------+-------------------------------------+
| Font size                 | 11px                                |
+---------------------------+-------------------------------------+
| Font weight               | bold                                |
+---------------------------+-------------------------------------+
| Font style                | italic                              |
+---------------------------+-------------------------------------+
| Font color                | #000                                |
+---------------------------+-------------------------------------+


7.2. The format of the abbreviations line must be as follows:

		:sample:`ABRVTN: expanded text; ABRVTN: expanded text` |br|
	 or |br|
		:sample:`expanded text: ABRVTN; expanded text: ABRVTN`


7.3. Abbreviation part must be written in all CAPS and expanded part - in lower case letters (except for proper nouns).

7.4. Abbreviation part must be separated from expanded part by a colon (:). No other separators allowed.

7.5. Abbreviation pairs (i.e. abbreviation and corresponding expanded text) must be separated from each other by semicolons (;). No other separators allowed.


7.6. There must be no punctuation marks at the end of abbreviations line.


.. image:: /_static/html_abbreviations.png
	:alt: Keywords
	:scale: 60%


7.7. There must be NO more than 5 abbreviation pairs. If there are more than 5 pairs, then move all abbreviations to the article text as an "Abbreviations" section.


8. Dates
--------

8.1. Dates sections must have titles “Received:”, “Accepted:”, “Published:”. They must start with capital letter and be followed by colon (:).

8.2. The format of “Received:”, “Accepted:”, “Published:” titles must be as follows:

+---------------------------+-------------------------------------+
| Characteristics           | Value                               |
+===========================+=====================================+
| Font family               | Sans-serif                          |
+---------------------------+-------------------------------------+
| Font size                 | 12px                                |
+---------------------------+-------------------------------------+
| Font weight               | bold                                |
+---------------------------+-------------------------------------+
| Font color                | #777                                |
+---------------------------+-------------------------------------+

8.3. There can be only one date line for each section. The format of date line must be as follows:

+---------------------------+-------------------------------------+
| Characteristics           | Value                               |
+===========================+=====================================+
| Font family               | Sans-serif    					  |
+---------------------------+-------------------------------------+
| Font size                 | 11px                                |
+---------------------------+-------------------------------------+
| Font weight               | bold                                |
+---------------------------+-------------------------------------+
| Font style                | italic                              |
+---------------------------+-------------------------------------+
| Font color                | #000                                |
+---------------------------+-------------------------------------+

8.4. Date line must have the following format:

		:sample:`Month Day, Year`

8.5. Month must be spelled out, while Day and Year must be presented as digits. Note that single Day digit should be preceded by 0 (zero).

	| 	`Example:`
	|	June 02, 2017
	| 	August 29, 2016
 
 8.6. There must be a comma (,) between Day and Year.

 	.. image:: /_static/html_dates.png
   		:alt: Dates format
   		:scale: 45%

 8.7. Received date must be older than Accepted date, and Accepted date must be older than Published date (i.e. we cannot publish before we accept, and cannot accept before we receive).


.. |br| raw:: html

   <br />

