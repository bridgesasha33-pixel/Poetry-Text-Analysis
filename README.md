# Poetry-Text-Analysis
Python text analysis of selected poems by Phillis Wheatley and Paul Laurence Dunbar, exploring poem length and word frequency.
Poetry Text Analysis

An exploratory Python analysis of ten published poems: five by Phillis Wheatley and five by Paul Laurence Dunbar. The project examines poem length, frequently used words, and whether repeated words appear across poems or are concentrated in one.

Data and tools

I collected the poem text in Excel and exported it as Poem Analysis.csv. I used Python, pandas, regular expressions, Matplotlib, and Google Colab for the analysis.

The poems come from Project Gutenberg:

Phillis Wheatley, Poems on Various Subjects, Religious and Moral
Paul Laurence Dunbar, The Complete Poems
What I examined
Word counts for each poem, including averages and medians for the five selected poems by each author
Frequently occurring words after filtering selected common words
The number of times the exact words “bird” and “love” occur in each poem
Findings

The five selected Wheatley poems averaged 224 words, compared with 111.6 words for the five selected Dunbar poems. The medians were 148 and 98 words, respectively; two longer Wheatley poems raised her sample’s average.

In these selected poems, “bird” appeared seven times across two Dunbar poems, including six times in “Sympathy.” “Love” appeared six times across three Dunbar poems. Neither exact word appeared in the five selected Wheatley poems.

Limitations

These ten poems were chosen for this project and do not represent either poet’s full body of work. The authors’ selected poems also contain different total amounts of text, so raw word frequencies should not be treated as comparable usage rates. A word count cannot establish a poem’s meaning or artistic quality.

Run the analysis

Upload Poem Analysis.csv to a Google Colab session, then open the project notebook and run its cells from top to bottom. The notebook reads the CSV by filename, so both files must be available in the same Colab session.
