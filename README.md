```
Corpus creation date: 2020-05-14
Corpus release date: 2020-05-14

Version 1.0

Authors:
Manolis Kapernaros, mkapernaros@di.uoa.gr


The WikiWarsEL corpus
#####################


1. Introduction
---------------
This is the README file for the distribution of the WikiWarsEL corpus, a 
Greek corpus containing Wikipedia [1] articles with annotations of temporal
expressions. The creation of the corpus was motivated by the English, German
and Vietnamese versions of the corpus, the WikiWars [2], WikiWarsDE [3] and
WikiWarsVN [4] corpora. For the creation of WikiWarsEL as well as for the
distribution, we followed the developers of the WikiWarsEL corpus. Thus, a lot of 
the information mentioned in this file follows the information provided by them 
in their README file. Thanks to all of the above!


2. Licensing Terms
------------------
The licensing terms are according to the licensing terms of the WikiWars 
corpus:
All the documents in the corpus are sources from Greek Wikipedia. As a 
consequence, the corpus is released under the Attribution-ShareAlike 3.0
Unported (CC BY-SA 3.0) License - To view a copy of this license,
visit http://creativecommons.org/licenses/by-sa/3.0/ or send a letter to
Creative Commons, PO Box 1866, Mountain View, CA 94042, USA.

See also the Terms of Use at http://wikimediafoundation.org/wiki/Terms_of_Use.

It is important to note that each time 'you distribute or publicly perform the 
work or a collection, the licensor offers to the recipient a license to the 
work on the same terms and conditions as the license granted to you under this 
license.'


3. Dictionary Structure
-----------------------
The WikiWarsEL package is structured as follows:

WikiWarsEL/readme.txt
	This is the readme file you are currently reading.
WikiWarsEL/untagged/
	This directory contains the 19 documents in TML format without
	annotations of temporal expressions.
WikiWarsEL/tagged/
	This directory contains the 19 documents with inline annotations of
	temporal expressions.

	
4. Corpus Creation
------------------
Here, we describe the Data Collection (Section 4.1), the Text Extraction and 
Preprocessing (Section 4.2) and the Annotation Process (Seciton 4.3).

4.1 Data Collection
-------------------
For data collection, we used the cross-language links from the Wikipedia sites
of the documents contained in the WikiWars corpus [2]. Thus the WikiWarsEL 
corpus contains sections of the following Wikipedia articles:

NAME OF THE WAR        YEAR SPAN     PAGE NAME AT https://el.wikipedia.org/wiki/
World War II           1939–1945     Β΄_Παγκόσμιος_Πόλεμος
World War I            1914–1918     Α΄_Παγκόσμιος_Πόλεμος
American Civil War     1861–1865     Αμερικανικός_Εμφύλιος_Πόλεμος
American Revolution    1775–1783     Αμερικανική_Επανάσταση
Vietnam War            1955–1975     Πόλεμος_του_Βιετνάμ
Korean War             1950–1953     Πόλεμος_της_Κορέας
Iraq War               2003–...      Πόλεμος_στο_Ιράκ
French Revolution      1789–1799     Γαλλική_Επανάσταση
Persian Wars           499–450 BC    Περσικοί_Πόλεμοι
Punic Wars             264–146 BC    Καρχηδονιακοί_Πόλεμοι
Chinese Civil War      1945–1949     Κινέζικος_Εμφύλιος_Πόλεμος
Iran-Iraq War          1980–1988     Πόλεμος_Ιράν-Ιράκ
Russian Civil War      1917–1923     Ρωσικός_Εμφύλιος_Πόλεμος
French Indochina War   1946–1954     - N/A
Mexican Revolution     1911–1920     - N/A
Spanish Civil War      1936–1939     Ισπανικός_εμφύλιος_πόλεμος
French-Algerian War    1954–1962     Πόλεμος_της_Αλγερίας
Soviet-Afghanistan War 1979–1989     Σοβιετικός_πόλεμος_στο_Αφγανιστάν
Russo-Japanese War     1904–1905     Ρωσοϊαπωνικός_Πόλεμος
Russo-Polish War       1919–1921     Πολωνο-Σοβιετικός_Πόλεμος
Biafran War            1967–1970     - N/A
Abyssinian War         1935–1936     Β΄_Ιταλο-Αιθιοπικός_Πόλεμος

For several of the English documents, there were no Greek versions 
available and as a result, the WikiWarsEL corpus contains only 19 and not the 
22 documents that WikiWars and WikiWarsDE contain.

4.2 Text Extraction and Preprocessing
-------------------------------------
Following Mazur and Dale (2010), we manually copied sections of the documents
that describe the course of the wars. All pictures, cross-page references, and 
citations were removed. In contrast to WikiWars and WikiWarsDE, all text files 
were then converted into the TimeML format with TIMEX3 annotations, the same 
format used in WikiWarsVN.
Due to this format, the corpus can be evaluated using the evaluation tools supplied
in HeidelTime's website [5] Corpora Preparation and Evaluation Scripts.


6. Versions & Changes
---------------------
Version 1.0: Initial release.


7. References
-------------
[1] http://www.wikipedia.org/
[2] Pawel Mazur and Robert Dale (2010). WikiWars: A New Corpus for Research on 
Temporal Expressions. In the Proceedings of the Conference on Empirical 
Methods in Natural Language Processing (EMNLP), 9-11 October 2010,
Massachusetts, USA.
[3] Jannik Strötgen and Michael Gertz: WikiWarsDE: A German Corpus of 
Narratives Annotated with Temporal Expressions. In the Proceedings of the 
Conference of the German Society for Computational Linguistics and Language 
Technology (GSCL). Pages 129-134, 2011.
based Vietnamese Text Processing Tool", http://jvntextpro.sourceforge.net/, 2010
[4] Jannik Strötgen, Ayser Armiti, Tran Van Canh, Julian Zell, and Michael 
Gertz. Time for More Languages: Temporal Tagging of Arabic, Italian, Spanish, 
and Vietnamese. In: ACM Transactions on Asian Language Information Processing 
(TALIP), 13(1), pages 1-21, 2014, ACM.
[5] https://dbs.ifi.uni-heidelberg.de/resources/heideltime-corpora-dl/
```
