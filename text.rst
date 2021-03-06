.. role:: und

.. role:: sample

.. role:: sampleb

.. role:: sampleu

.. role:: samplei

.. role:: raw-html(raw)

10. Text
--------

10.1. Text format must be consistent across all sections (except for References) of the article:

+---------------------------+-------------------------------------+
| Characteristics           | Value                               |
+===========================+=====================================+
| Font family               | Arial, Helvetica, sans-serif        |
+---------------------------+-------------------------------------+
| Font size                 | 12px                                |
+---------------------------+-------------------------------------+
| Font weight               | normal                              |
+---------------------------+-------------------------------------+
| Font style                | normal                              |
+---------------------------+-------------------------------------+
| Line-height               | 18px                                |
+---------------------------+-------------------------------------+
| Text-align                | justify                             |
+---------------------------+-------------------------------------+
| Font color                | #221f22                             |
+---------------------------+-------------------------------------+

10.2. Check that there is a period (.) at the end of the abstract text.

10.3. The following Latin terms must be written in italics: *in vivo, in vitro, in utero, in situ, via, de-nove, de nove*. 
All other words/terms formatted in italics by author must be preserved in italics.


10.4. All letters for variables ("p", "u", "t", "n", "x", "P", "U", "T", "N", "X" and others) must be must be written in italics. There must be a space between variable letter and mathematical operators. For example:

| :samplei:`p`:sample:`-value`
| :samplei:`p` :sample:`value`
| :samplei:`p` :sample:`> 10`
| :samplei:`p` :sample:`= 10`
| OR
| :samplei:`P`:sample:`-value`
| :samplei:`P` :sample:`value`
| :samplei:`P` :sample:`> 10`
| :samplei:`P` :sample:`= 10`
| OR
| :samplei:`u`:sample:`-test`
| :samplei:`t`:sample:`-test`
| :samplei:`u` :sample:`test`
| :samplei:`t` :sample:`test`
| OR
| :samplei:`U`:sample:`-test`
| :samplei:`T`:sample:`-test`
| :samplei:`U` :sample:`test`
| :samplei:`T` :sample:`test`
| OR
| :samplei:`n` :sample:`= 1`
| :samplei:`N` :sample:`= 1`
| :samplei:`x` :sample:`= 1`
| :samplei:`X` :sample:`= 1`

10.5. Letters for variables can be preceeded by asterisk (*). In such cases asterisk must be in superscript and there must be NO space between asterisk and variable letter. For example:

| :samplei:`*p` :sample:`< 30`
| :samplei:`*p` :sample:`> 10`

10.6. There must be a prime (ʹ - see typography section for HTML code of prime) instead of apostrophe in entries related to genes. For example:

| :sample:`5ʹ-TCTTCCACCAGTCCCAAA-3ʹ`
| :sample:`5′-GCGTTGTCTGTCCAGTTG-3′`
| :sample:`5′-GAACTACAACTGGAACTCCTT-3′`

10.7. There must be a space between numeric value and uits. For example:

| :sample:`25 ml`
| :sample:`1 h`
| :sample:`50 Gy`
| :sample:`16 cm`
| :sample:`9.5 μM`

**Exclusion:**  There must be NO space between numeric value, percentage, currency character or degree:

| :sample:`10%`
| :sample:`$250`
| :sample:`€250`
| :sample:`37°C`

10.8. There must be a minus sign (−) or en-dash (–) instead of hyphen (‐) in number elements and ranges. For example:

| :sample:`-0.9`
| :sample:`5-7`

10.9. Double dash "- -" must be replaced by en-dash (–). For example:

| "been reported that- -patients" must be corrected to :sample:`"been reported that-patients"`


10.10. Spelled out fractions (e.g, one-third) must always be separated by hyphen (‐).

10.11. Only curly quotes |curly quoutes| must be used throughout the article. Straight quotes |straight quoutes| are not allowed.

10.12. Registered trademark (®) must be written in superscript throughout the article.

10.13. Ordinal number (1st, 2nd, 3rd etc) suffixes must NOT be written in superscript. Such suffixes must be presented in plain text. For example:

| :sample:`1st`
| :sample:`2nd`


10.14. Article text must NOT be underlined or formatted in bold for emphasis purposes. However, bold is allowed for scientific terms.

10.15. All website addresses must be hyperlinked in article text.

.. _figures_check:

11. Figures
------------

11.1. Figure image must have text and graphics which are clear and large enough to read (i.e. image text is not smaller than article text itself).

11.2. Figures can have :ref:`panel letters<figure_pannel>`. Both lower case and upper case :ref:`panel letters<figure_pannel>` are allowed. However, they must be used consistently: either all figures have lower case :ref:`panel letters<figure_pannel>` or all have upper case letters. Mix of formats is NOT allowed.

11.3. Figure legend must have a figure number followed by colon (:):

	|	:sampleb:`Figure N:` (where N is a number of the figure)

11.4. The format of title must be as follows:

+---------------------------+-------------------------------------+
| Characteristics           | Value                               |
+===========================+=====================================+
| Font family               | Arial, Helvetica, sans-serif        |
+---------------------------+-------------------------------------+
| Font size                 | 11px                                |
+---------------------------+-------------------------------------+
| Font weight               | bold                                |
+---------------------------+-------------------------------------+
| Font style                | normal                              |
+---------------------------+-------------------------------------+
| Line-height               | 14px                                |
+---------------------------+-------------------------------------+
| Font color                | #221f22                             |
+---------------------------+-------------------------------------+


11.5. If figure number is followed by text, then first sentence of that text must be formatted same way as figure numbe (see above). The rest of the text should be in plain text (see point 10.1)

	|	:sampleb:`Figure 1: First sentence of legend text in sentence case.` :sample:`Second sentence and rest of text.`
	
	.. image:: /_static/html_figure_number.png
   	  	:alt: Figure number
   	  	:scale: 99%

	`Exclusion:` if first sentence contains :ref:`panel letters<figure_pannel>`, then it should be formatted in plain text.

	|	:sampleb:`Figure 2:` :sample:`First sentence of legend text containing panel letter (`:sampleb:`A`:sample:`) and letter (`:sampleb:`B`:sample:`) in a sentence case. Second sentence and rest of text.`


	.. image:: /_static/html_figure_number_exception.png
   	  	:alt: Figure number
   	  	:scale: 99%

11.6. If figure image has :ref:`panel letters<figure_pannel>`, then reference to each panel must be present in figure legend. Such reference is composed of a :ref:`panel letter<figure_pannel>`, which must be formatted in **bold** (same format as in point 11.4.).

	| There are 2 allowed formats for the panel reference (case of letter should match letter case in figure image):

	|	:sampleb:`A.` or :sampleb:`a.` - i.e. letter followed by period (.)
	|	:sample:`(`:sampleb:`A`:sample:`)` or :sample:`(`:sampleb:`a`:sample:`)` - i.e. letter wrapped in round brackets ()

	| Panel letters can be combined in different ways in the figure legend text:

	| :sampleb:`A.` :sample:`and` :sampleb:`B.`

	.. image:: /_static/html_fig_reference_anb.png
   	  	:alt: Figure number
   	  	:scale: 99%

	| :sampleb:`A.`:sample:`,` :sampleb:`B.`

	.. image:: /_static/html_fig_reference_acomb.png
   	  	:alt: Figure number
   	  	:scale: 99%

	| :sampleb:`A.-C.`

	.. image:: /_static/html_fig_reference_a-c.png
   	  	:alt: Figure number
   	  	:scale: 99%

	| :sample:`(`:sampleb:`A` :sample:`and` :sampleb:`B`:sample:`)`

	.. image:: /_static/html_fig_reference_br_anb.png
   	  	:alt: Figure number
   	  	:scale: 99%

	| :sample:`(`:sampleb:`A`:sample:`,` :sampleb:`B`:sample:`)`

	.. image:: /_static/html_fig_reference_br_acomb.png
   	  	:alt: Figure number
   	  	:scale: 99%

	| :sample:`(`:sampleb:`A-C`:sample:`)`

	.. image:: /_static/html_fig_reference_br_a-c.png
   	  	:alt: Figure number
   	  	:scale: 99%

	| Same variations are allowed for lower case panel letters.


	If a reference to :ref:`panel letter<figure_pannel>` is missing, then please ask author to provide one.


11.4. Figure numbering must NOT have any gaps in sequence. In other words there must be no situation when there are figures 1, 3 and 4 in the article, but figure 2 is missing.

At the same time, upon authors request, figures can appear in the text in any order. E.g. figure 2 before figure 1 is OK.

If you see that there are gaps in number sequence, then check with corresponding author whether some figures are missing or whether it is possible to re-number the figures to eliminate the gaps.

11.5. Check figure callouts in the text:

	- Check the format of figure callouts:

	| :sampleu:`Fig. 1`
	| :sampleu:`Figure 1`


	.. image:: /_static/html_fig_callouts.png
   	  	:alt: Figure number
   	  	:scale: 99%
    |
	If figure has panels, then callout can have a letter (letter case must be the same as on figure image):

	| :sampleu:`Fig. 1A` 	
	| :sampleu:`Fig. 1a`
	
	.. image:: /_static/html_fig_callout_short_letters.png
   	  	:alt: Figure number
   	  	:scale: 99%
   	|
	| :sampleu:`Figure 1A`
	| :sampleu:`Figure 1a`

	.. image:: /_static/html_fig_callout_full_letters.png
   	  	:alt: Figure number
   	  	:scale: 99%
   	|
	Both formats (Fig. and Figure) are acceptable. However, they must be used consistently: either all callouts have "Fig." or all callouts have "Figure".

	| `Examples of callout combinations:`
	| :sampleu:`Figure 1`
	| :sampleu:`Figure 3C`
	| :sampleu:`Figure 2B` :sample:`and` :sampleu:`2C` (note that there is NO "s" at the end of "Figure" word)
	| :sampleu:`Figures 2` :sample:`and` :sampleu:`3` (note that there IS "s" at the end of "Figure" word)
	| :sampleu:`Figure 5B`:sample:`,` :sampleu:`5C`
	| :sampleu:`Figure 1E`:sample:`–`:sampleu:`1G`

	.. image:: /_static/html_fig_callout_variations.png
   	  	:alt: Figure number
   	  	:scale: 99%

	Same variations are allowed for "Fig."


	- "Figure" or "Fig." as well as number (and letter) must be hyperlinked.

	- Each figure must have at least 1 callout in the text.

	If one or more callouts are missing in the text, please contact author.


.. Important::

	There is a different callouts format for Supplementary Figures.
	It is described in Supplementary Materials Check here.


.. _tables_check:

12. Tables
----------

12.1. The format of table text must be as follows:

**- Table header**

+---------------------------+-------------------------------------+
| Characteristics           | Value                               |
+===========================+=====================================+
| Font family               | Arial, Helvetica, sans-serif        |
+---------------------------+-------------------------------------+
| Font size                 | 12px                                |
+---------------------------+-------------------------------------+
| Font weight               | bold                                |
+---------------------------+-------------------------------------+
| Font style                | normal                              |
+---------------------------+-------------------------------------+
| Text-align                | center                              |
+---------------------------+-------------------------------------+
| Font color                | #333                                |
+---------------------------+-------------------------------------+

**- Table text**

+---------------------------+-------------------------------------+
| Characteristics           | Value                               |
+===========================+=====================================+
| Font family               | Arial, Helvetica, sans-serif        |
+---------------------------+-------------------------------------+
| Font size                 | 12px                                |
+---------------------------+-------------------------------------+
| Font weight               | normal                              |
+---------------------------+-------------------------------------+
| Font style                | normal                              |
+---------------------------+-------------------------------------+
| Text-align                | center                              |
+---------------------------+-------------------------------------+
| Font color                | #333                                |
+---------------------------+-------------------------------------+


.. _table_title_check:

12.1. Each table must have a title. Title must be positioned above the table.

12.2. Title must have table number and title text.

12.3. Table number must contain word "Table", number and colon (:):

	| :sampleb:`Table N:` (where N is a number of the table)

	In rare cases table number can contain a letter:

	| :sampleb:`Table 1A:` (where Table 1A and 1B, 1C etc are separate tables)


12.4. Table number must be followed by title text. Title text must be a single sentence. It is not allowed to have more than 1 sentence as a table title.

	| :sampleb:`Table 2: Table title in a sentence case`

	.. image:: /_static/html_table_title.png
   	  	:alt: Table title
   	  	:scale: 99%

12.5. THere must be NO period (.) or any other punctuation makrs at the end of table title.

12.6. Title must be written in :ref:`sentence case<sentence_case>`.

12.7. The format of table title must be as follows:

+---------------------------+-------------------------------------+
| Characteristics           | Value                               |
+===========================+=====================================+
| Font family               | Arial, Helvetica, sans-serif        |
+---------------------------+-------------------------------------+
| Font size                 | 11px                                |
+---------------------------+-------------------------------------+
| Font weight               | bold                                |
+---------------------------+-------------------------------------+
| Font style                | normal                              |
+---------------------------+-------------------------------------+
| Line height               | 14px                                |
+---------------------------+-------------------------------------+
| Font color                | #221f22                             |
+---------------------------+-------------------------------------+

12.8. The format of table text must be as follows:

**- Table header**

+---------------------------+-------------------------------------+
| Characteristics           | Value                               |
+===========================+=====================================+
| Font family               | Arial, Helvetica, sans-serif        |
+---------------------------+-------------------------------------+
| Font size                 | 12px                                |
+---------------------------+-------------------------------------+
| Font weight               | bold                                |
+---------------------------+-------------------------------------+
| Font style                | normal                              |
+---------------------------+-------------------------------------+
| Text-align                | center                              |
+---------------------------+-------------------------------------+
| Font color                | #333                                |
+---------------------------+-------------------------------------+

**- Table text**

+---------------------------+-------------------------------------+
| Characteristics           | Value                               |
+===========================+=====================================+
| Font family               | Arial, Helvetica, sans-serif        |
+---------------------------+-------------------------------------+
| Font size                 | 12px                                |
+---------------------------+-------------------------------------+
| Font weight               | normal                              |
+---------------------------+-------------------------------------+
| Font style                | normal                              |
+---------------------------+-------------------------------------+
| Text-align                | center                              |
+---------------------------+-------------------------------------+
| Font color                | #333                                |
+---------------------------+-------------------------------------+


12.9. Table notes (additional information related to table) must be presented below the table in :ref:`plain text<plain_text>`.

.. image:: /_static/html_table_notes.png
	:alt: Table notes
	:scale: 99%


12.10. The format of table text must be as follows:

+---------------------------+-------------------------------------+
| Characteristics           | Value                               |
+===========================+=====================================+
| Font family               | Arial, Helvetica, sans-serif        |
+---------------------------+-------------------------------------+
| Font size                 | 11px                                |
+---------------------------+-------------------------------------+
| Font weight               | normal                              |
+---------------------------+-------------------------------------+
| Font style                | normal                              |
+---------------------------+-------------------------------------+
| Line height               | 14px                                |
+---------------------------+-------------------------------------+
| Font color                | #221f22                             |
+---------------------------+-------------------------------------+


12.11. Table numbering must NOT have any gaps in sequence. In other words, there must be no situation when there are tables 1, 3 and 4 in the article, but table 2 is missing.

At the same time, upon authors request, tables can appear in the text in any order. E.g. table 2 before table 1 is OK.

If you see that there are gaps in number sequence, then check with corresponding author whether some tables are missing or whether it is possible to re-number the tables to eliminate the gaps.


12.11. Table callout must contain word "Table", number of the table and (in rare cases) pannel letter.


	| :sampleu:`Table 1` (or in rare cases :sampleu:`Table 1A`)
	|
	| `Examples:`
	| :sampleu:`Table 1`
	| :sampleu:`Table 2A`
	| :sampleu:`Tables 1` :sample:`and` :sampleu:`2` (note that there IS an "s" at the end of "Table" word)
	| :sampleu:`Tables 3A` :sample:`and` :sampleu:`3B` (where 3A and 3B are separate tables)

	.. image:: /_static/html_table_callouts.png
		:alt: Table callouts
		:scale: 99%
	|

12.12. Table callouts must be hyperlinked to corresponding tables in the text.

12.13. Each table must have at least 1 callout in the text.

	If one or more callouts are missing in the text, please contact author.

.. Important::

	There is a different callouts format for Supplementary Tables.
	It is described in Supplementary Materials Check here.


13. Reference Callouts
----------------------

13.1. Reference callout must contain a number, or a set of numbers or a range of numbers, wrapped in sqare brakets.

	| :sample:`[`:sampleu:`N`:sample:`]` (where N is the order number of the corresponding reference)
	|
	| `Examples:`
	| :sample:`[`:sampleu:`1`:sample:`]`
	| :sample:`[`:sampleu:`1`:sample:`,` :sampleu:`2`:sample:`]`
	| :sample:`[`:sampleu:`1`:sample:`–`:sampleu:`3`:sample:`]`
	| :sample:`[`:sampleu:`1`:sample:`,` :sampleu:`3`:sample:`–`:sampleu:`4`:sample:`]`

	.. image:: /_static/html_callouts.png
		:alt: Table callouts
		:scale: 99%
	|

13.2. Only comma (,) and/or :ref:`en dash<en_dash>` (–) must be used as a separators. No other separators are allowed. 

13.3. There must be a space after comma (,) and NO space before and after en dash (–).

13.4. All numbers, set of number or range of numbers must be hyperlinked to courresponding references.

13.2. Callout number for each of the references must be present in the text or covered in the range of numbers. E.g. reference 2 is not present in the text, but covered in the range of [1-3]. This is acceptable case.

13.3. There must be NO "orphaned" callouts (i.e. callout numbers for the references which do not exist). E.g. if you see callout [50] and there are only 40 references in the article, then callout [50] is "orphaned" and must be removed.


.. |straight quoutes| raw:: html

   (&#34; &#34;)

.. |curly quoutes| raw:: html

   (&ldquo; &rdquo;)