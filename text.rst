.. role:: und

.. role:: sample

.. role:: sampleb

.. role:: sampleu

.. role:: samplei

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





10.3. Check MATERIALS AND METHODS section (or its alternatives - see in Section headers) for erroneously placed hyperlinks (e.g. hyperlinked numbers in compound names).

10.4. Check that all website addresses are hyperlinked in article text.

.. _figures_check:

11. Figures
------------

11.1. Check that figure image has text and graphics which are clear and large enough to read (i.e. image text is not smaller than article text itself).

If image is hard to read, please contact Production team and ask to provide more clear images. If Production team does not have better images, then contact corresponding author.

11.2. Check whether figures have :ref:`panel letters<figure_pannel>`. Both lower case and upper case :ref:`panel letters<figure_pannel>` are allowed. However, they should be used consistently: either all figures have lower case :ref:`panel letters<figure_pannel>` or all have upper case letters. Mix of formats is not allowed.

11.3. Check the figure description text (figure legend):

	- Check that figure legend has a figure number:

	|	:sampleb:`Figure N:` (where N is a number of the figure)

	- Check that number is followed by colon (:).

	- Check that figure number is formatted in bold and coloured in black.

	- If figure number is followed by text, then check that the first sentence of that text is formatted in bold and coloured in black. The rest of the text should be in plain text.

	|	:sampleb:`Figure 1: First sentence of legend text in sentence case.` :sample:`Second sentence and rest of text.`
	
	.. image:: /_static/html_figure_number.png
   	  	:alt: Figure number
   	  	:scale: 99%

	`Exclusion:` if first sentence contains :ref:`panel letters<figure_pannel>`, then it should be formatted in plain text.

	|	:sampleb:`Figure 2:` :sample:`First sentence of legend text containing panel letter (`:sampleb:`A`:sample:`) and letter (`:sampleb:`B`:sample:`) in a sentence case. Second sentence and rest of text.`


	.. image:: /_static/html_figure_number_exception.png
   	  	:alt: Figure number
   	  	:scale: 99%

	- If figure image has :ref:`panel letters<figure_pannel>`, then check that reference to each panel is present in figure legend. Reference is denoted by :ref:`panel letter<figure_pannel>` and is formatted in bold.

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


11.4. Check that figure numbers are assigned to figures continuously and there are no gaps in a sequence. In other words there should be no situation when there are figures 1, 3 and 4 in the article, but figure 2 is missing.

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
	If figure has panels, then callout can have a letter (letter case should be the same as on figure image):

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
	Both formats (Fig. and Figure) are acceptable. However, they should be used consistently: either all callouts have "Fig." or all callouts have "Figure".

	| `Examples of callout combinations:`
	| :sampleu:`Figure 1`
	| :sampleu:`Figure 3C`
	| :sampleu:`Figure 2B` :sample:`and` :sampleu:`2C` (note that there is no "s" at the end of "Figure" word)
	| :sampleu:`Figure 5B`:sample:`,` :sampleu:`5C`
	| :sampleu:`Figure 1E`:sample:`–`:sampleu:`1G`

	.. image:: /_static/html_fig_callout_variations.png
   	  	:alt: Figure number
   	  	:scale: 99%

	Same variations are allowed for "Fig."


	- Check that words "Figure" or "Fig." as well as number (and letter) are hyperlinked.

	- Check that each figure has at least 1 callout in the text.

	If one or more callouts are missing in the text, please contact author.


.. Important::

	There is a different callouts format for Supplementary Figures.
	It is described in Supplementary Materials Check here.


.. _tables_check:

12. Tables
----------

12.1.  Check that table font size is large enough to read.

If table is hard to read, please contact Production team and ask to increase font size.

.. _table_title_check:

12.2. Check table title:

	- Check that there is a title above the table.

	- Check that title has table number:

	| :sampleb:`Table N:` (where N is a number of the table)

	In rare cases table number can contain a letter:

	| :sampleb:`Table 1A:` (where Table 1A and 1B, 1C etc are separate tables)

	- Check that number is followed by colon (:).

	- Check that table number is formatted in bold and coloured in black.

	- Check that table number is followed by table title. Table title should be a single sentence. It is not allowed to have more than 1 sentence as a table title.

	| :sampleb:`Table 2: Table title in a sentence case`

	.. image:: /_static/html_table_title.png
   	  	:alt: Table title
   	  	:scale: 99%

	- Check that title does not have period (.) at the end.

	- Check that title is written in :ref:`sentence case<sentence_case>`, formatted in bold and coloured in black.

12.3. Check that table-related additional information is presented below the table as a note in :ref:`plain text<plain_text>`.

.. image:: /_static/html_table_notes.png
	:alt: Table notes
	:scale: 99%

12.4. Check that table font, title font and notes (additional information) fonts are used consistently within the article (i.e. font should not vary from table to table).

12.5. Check that table numbers. Tables should be numbered continuously, so there are no gaps in the sequence. In other words, there should be no situation when there are tables 1, 3 and 4 in the article, but table 2 is missing.

At the same time, upon authors request, tables can appear in the text in any order. E.g. table 2 before table 1 is OK.

If you see that there are gaps in number sequence, then check with corresponding author whether some tables are missing or whether it is possible to re-number the tables to eliminate the gaps.

12.6. Check table callouts in the text:

	- Check the format of table callouts:

	| :sampleu:`Table 1` (or in rare cases :sampleu:`Table 1A`)
	|
	| `Examples:`
	| :sampleu:`Table 1`
	| :sampleu:`Table 2A`
	| :sampleu:`Tables 1` :sample:`and` :sampleu:`2` (note that there is an "s" at the end of "Table" word)
	| :sampleu:`Tables 3A` :sample:`and` :sampleu:`3B` (where 3A and 3B are separate tables)

	.. image:: /_static/html_table_callouts.png
		:alt: Table callouts
		:scale: 99%
	|
	- Check that word "Table" (or "Tables") as well as number (and letter) are hyperlinked.

	- Check that each table has at least 1 callout in the text.

	If one or more callouts are missing in the text, please contact author.

.. Important::

	There is a different callouts format for Supplementary Tables.
	It is described in Supplementary Materials Check here.


13. Reference Callouts
----------------------

13.1. Check reference callouts in the text:

	- Check the format of reference callouts:

	| :sample:`[N]` (where N is the order number of the corresponding reference)
	|
	| `Examples:`
	| :sample:`[1]`
	| :sample:`[1, 2]`
	| :sample:`[1–3]`
	| :sample:`[1, 3–4]`

	.. image:: /_static/html_callouts.png
		:alt: Table callouts
		:scale: 99%
	|
	- Check that only comma (,) and :ref:`en dash<en_dash>` (–) are used as a separators. No other separators are allowed. 

	- Check that there is a space after comma (,) and no space before and after en dash (–).

	- Check that reference callouts are in :ref:`plain text<plain_text>` and a number (or numbers in case of ranges) is hyperlinked.

13.2. Check that callout number for each of the references is present in the text or is covered in the range of numbers. I.e. in the range of [1-3] reference 2 is not present in the text, but covered in the range. This is acceptable case.

13.3. Check that there are no "orphaned" callouts (i.e. callout numbers for the references which do not exist). E.g. if you see callout [50] and there are only 40 references in the article, then callout [50] is "orphaned" and should be removed.
