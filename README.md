# Transkribus models
Images of example pages from Transkribus model training sets to make it easier to find a match.

## DAT 18. Jh M3b\_Pylaia
**Language:** German

**Description:** 19th century newspaper. Fraktur. 130 pages OCR correction and proofing. Print style for umlaut varies throughout (superscript "e" vs öäü). Since no applicable Pylaia model was available for training, the training set includes the HTR model data for DAT 18. Jh M1 and M2.

| Text | Tech | Words     | Lines | CER train     | CER validation     |
| :---    | :---    | :---        |    :----:   |          ---: |          ---: |
| Print | Pylaia | 102875      | 17029      | 0.50%   | 0.30%   |

**Ground Truth Examples**
| 110      | 166 | 181     | 201     |
| :---        |    :----:   |          ---: |          ---: |
| [![DAT 18 p. 110](images/dat18_110.png)](images/dat18_110.png)      | [![DAT 18 p. 166](images/dat18_166.png)](images/dat18_166.png)      | [![DAT 18 p. 181](images/dat18_181.png)](images/dat18_181.png)   | [![DAT 18 p. 201](images/dat18_201.png)](images/dat18_201.png)   |

## Pylaia\_NeoLatin\_Ravenstein
**Language:** NeoLatin

**Description:** This model is based on the transcription of the "Litterae Annuae Parochiae Ravensteijn SJ ab Anno 1643 ad Annum 1772".
The annual letters were kept at the Archivum Neerlandicum Societatis Iesu (Berchmannianum, Nijmegen) . These are now at the Catholic Document Center (Katholiek Documentatie Centrum (KADOC)) in Leuven, Belgium  (inventarisnummer 15.606).

Tom Gribnau photographed the manuscript; the transcriptions were made by Pim Boer, Leo Nellissen. 
This belongs to the publication: Tom Gribnau, Pim Boer, Leo Nellissen, Paul Begheyn SJ & Charles Caspers, Martiaal en theatraal. De jezuïeten in Ravenstein (1643-1772). Inleiding en vertaling van de jaarbrieven Nijmgen: Uitgeverij Valkhof Pers 2019; ISBN 978 90 5625 514 5)
More information can be found at: https://jaarbrieven.blogspot.com/ and https://www.stilus.nl/litterae/

T2I from the transcripts to Transkribus model has been done by Dr. C.A. Romein.

| Text | Tech | Words     | Lines | CER train     | CER validation     |
| :---    | :---    | :---         |    :----:   |          ---: |          ---: |
| Handwriting | Pylaia | 64435      | 6864      | 1.30%   | 4.00%   |

**Ground Truth Examples**
| 22      | 145 | 66     | 114     |
| :---        |    :----:   |          ---: |          ---: |
| [![Pylaia NeoLatin Ravenstein p. 22](images/pylaia_neolatin_ravenstein_22.png)](images/pylaia_neolatin_ravenstein_22.png)      | [![Pylaia NeoLatin Ravenstein p. 45](images/pylaia_neolatin_ravenstein_45.png)](images/pylaia_neolatin_ravenstein_45.png)      | [![Pylaia NeoLatin Ravenstein p. 66](images/pylaia_neolatin_ravenstein_66.png)](images/pylaia_neolatin_ravenstein_66.png)   | [![Pylaia NeoLatin Ravenstein p. 114](images/pylaia_neolatin_ravenstein_114.png)](images/pylaia_neolatin_ravenstein_114.png)   |


## German\_Kurrent_17th-18th
**Languages:** German, Latin, French

**Description:**  The model was trained with manuscripts of the 17th, 18th and few dates of the 19th century.  Occasionally, printed material from the same period were also included. In total, the Ground Truth is based on about 1500 individual handwritings, which come from the council minutes of the University of Greifswald, the assessor votes of the Wismar High Court, the minutes of the Pomeranian government of Stralsund, the responsa of the Greifswald Law Faculty and other archival holdings, such as private letter collections.

| Text | Tech | Words     | Lines | CER train     | CER validation     |
| :--- | :---     | :---        |    :----:   |          ---: |          ---: |
| Handwriting | Pylaia | 1839841      | 289857      | 6.00%   | 5.50%   |

No training image samples available.

## Manuscripts of Ethiopia and Eritrea
**Language:** Classical Ethiopic (Geʽez script)

**Description:**  Model for the transcription of Manuscripts of Ethiopia and Eritrea in Classical Ethiopic (Gǝʿǝz). Trained as part of the Beta maṣāḥǝft project 
and in order to feed a workflow to import transcriptions into the project's database.
Transcriptions for the training have been kindly provided by

 - Alessandro Bausi for ESum039, ff. 16vb-29va;
 - Antonella Brita for DAS002, 101va-110ra; 
 - Dorothea Reule for ESqdq004, ff. 97ra-101vb, 104ra-109rb.
 - Nafisa Valieva for BLorient718, ff. 1ra-7vb, images British Library.
- Several parts of manuscripts transcribed by Jeremy Brown and pertaining to the Miracle of the Cannibal of Qemer.

Importing of images and transcriptions in Transkribus has been done by Pietro Liuzzo

The project Beta maṣāḥǝft: Manuscripts of Ethiopia  and Eritrea (Schriftkultur des christlichen Äthiopiens  und Eritreas: eine multimediale Forschungsumgebung) is a long-term project funded within the framework of  the Academies' Programme (coordinated by the Union of the German Academies of Sciences and Humanities)  under survey of the Akademie der Wissenschaften in  Hamburg. The funding will be provided for 25 years,  from 2016–2040. The project is hosted by the Hiob  Ludolf Centre for Ethiopian Studies at the Universität  Hamburg. It aims at creating a virtual research environment that shall manage complex data related  to the predominantly Christian manuscript tradition  of the Ethiopian and Eritrean Highlands.

| Text | Tech | Words     | Lines | CER train     | CER validation     |
| :--- | :---     | :---        |    :----:   |          ---: |          ---: |
| Handwriting | HTR+ | 53830      | 16028      | 5.57%   | 5.16%   |

No training image samples available.

## Acta_17 PyLaia
**Languages:** German, Latin

**Description:** The PyLaia model was trained on the basis of more than 500,000 words from  about 1000 different writers during the period 1580-1705. It can handle the languages German, Low German and Latin and is able to decipher simple German and Latin abbreviations. Besides the usual chancery writings,  the training material also contained a  selection of concept writings and printed  material of the period.  The entire training material is based on  legal texts or court writings from the  Responsa of the Greifswald  Law Faculty. Validation sets are based on a chronological selection of the years: 1580 - 1705 . GT & validation set was produced by Dirk Alvermann, Elisabeth Heigl, Anna Brandt.

| Text | Tech | Words     | Lines | CER train     | CER validation     |
| :---    | :---    | :---        |    :----:   |          ---: |          ---: |
| Handwriting | Pylaia | 594628      | 102545      | 7.10%   | 5.16%   |

No training image samples available.

## Noscemus GM 3.0
**Languages:** Latin, Greek (German, Italian, English)

**Description:**
The "NOSCEMUS General Model" is able to read printed Latin text, especially from the 15th, 16th, 17th and 18th century. The model was released by Stefan Zathammer and it is based on training data coming from the Digital Sourcebook of the NOSCEMUS project (https://www.uibk.ac.at/projects/noscemus/)

For the 3rd revised and updated version a substantial amount of new pages was added, including prints from the 15th century and especially Greek texts.

Although the model is tailored towards transcribing (Neo-)Latin texts set in Antiqua-based typefaces, it is also, to a certain degree, able to handle Greek words and words set in (German) Fraktur.

The NOSCEMUS project has received funding from the European Research Council (ERC) under the European Union’s Horizon 2020 research and innovation programme (grant agreement No. 741374).

| Text | Tech | Words     | Lines | CER train     | CER validation     |
| :---    | :---    | :---        |    :----:   |          ---: |          ---: |
| Print | HTR+ | 448464      | 66575      | 0.40%   | 0.98%   |

No training image samples available.

## Acta_17 HTR+
**Language:** German, Latin

**Description:**
The HTR-model was trained on the basis of more than 500,000 words from about 1000 different writers during the period 1580-1705. It can handle the languages German, Low German and Latin and is able to decipher simple german and latin abbreviations. Besides the usual chancery writings, the training material also contained a selection of concept writings and printed  material of the period. The entire training material is based on legal texts or court writings from the  Responsa of the Greifswald  Law Faculty.

Validation sets are based on a chronological selection of the years: 1580 - 1705 . GT & validation set was produced by Dirk Alvermann, Elisabeth Heigl, Anna Brandt.

| Text | Tech | Words     | Lines | CER train     | CER validation     |
| :---    | :---    | :---        |    :----:   |          ---: |          ---: |
| Handwritten | HTR+ | 594628      | 102545      | 9.43%   | 6.30%   |

No training image samples available.

## Dutch\_Romantype_Pylaia
**Language:** Dutch Roman Print

**Description:**
This model is based on printed texts in the Roman font that was used in the Low Countries, during the 16th, 17th and 18th century. The type of sources used for this model, are books of ordinances, which contained the norms ('laws') at the time. 

This model has been the result of one of the KB National Library of the Netherlands Researcher-in-Residence position 2019. The project was called 'Entangled Histories'. 

For more information regarding the background of the model and how to cite it, please visit: https://lab.kb.nl/dataset/entangled-histories-ordinances-low-countries

| Text | Tech | Words     | Lines | CER train     | CER validation     |
| :---    | :---    | :---        |    :----:   |          ---: |          ---: |
| Print | Pylaia | 88105      | 13013      | 0.30%   | 1.40%   |

No training image samples available.


## Dutch\_Gothic\_Print_Pylaia
**Language:** Dutch Gothic

**Description:** This model is based on printed texts in the Gothic font that was used in the Low Countries, during the 16th, 17th and 18th century. The type of sources used for this model, are books of ordinances, which contained the norms ('laws') at the time. 

| Text | Tech | Words     | Lines | CER train     | CER validation     |
| :---    | :---    | :---        |    :----:   |          ---: |          ---: |
| Print | Pylaia | 51143      | 7143      | 0.20%   | 2.00%   |

No training image samples available.

## French\_18thC_Pylaia
**Language:** French

**Description:** This model is based on printed texts in French (Romantype Font) that was used in Flanders (Low Countries), during the 18th century. The type of sources used for this model, are books of ordinances, which contained the norms ('laws') at the time. 

This model has been the result of one of the KB National Library of the Netherlands Researcher-in-Residence position 2019. The project was called 'Entangled Histories'. The books used for this specific model, have been provided by the Bodleian Library Oxford (RECUEIL DES ÉDITS, DÉCLARATIONS, LETTRES-PATENTES, &c. ENREGISTRÉS
AU PARLEMENT DE FLANDRES).

For more information regarding the background of the model and how to cite it, please visit: www.https://lab.kb.nl/dataset/entangled-histories-ordinances-low-countries 

| Text | Tech | Words     | Lines | CER train     | CER validation     |
| :---    | :---    | :---        |    :----:   |          ---: |          ---: |
| Print | Pylaia | 38487     | 3883      | 0.10%   | 0.91%   |

No training image samples available.

## German\_Kurrent\_XIX\_pylaia
**Language:** German

**Description:** Large train and test set for german kurrent (19. century). GT from different projects and partners. Biased towards Swiss Documents.

| Text | Tech | Words     | Lines | CER train     | CER validation     |
| :---    | :---    | :---        |    :----:   |          ---: |          ---: |
| Handwritten | Pylaia | 5100439     | 764457      | 4.60%   | 6.90%   |

No training image samples available.

## Estonian Court Records 19thC
**Language:** Estonian

**Description:** Model is based on Uue-Põltsamaa court records (vallakohus, gemeindegericht) 1852-1864 from Estonian National Archives.

| Text | Tech | Words     | Lines | CER train     | CER validation     |
| :---    | :---    | :---        |    :----:   |          ---: |          ---: |
| Handwritten | HTR+ | 56190     | 10204     | 0.68%   | 3.55%   |

**Ground Truth Examples**
| 36      | 42 | 68     | 173     |
| :---        |    :----:   |          ---: |          ---: |
| [![Estonian Court Records p. 36](images/estonian_court_records_36.png)](images/estonian_court_records_36.png)      | [![Estonian Court Records p. 42](images/estonian_court_records_42.png)](images/estonian_court_records_42.png)      | [![Estonian Court Records p. 68](images/estonian_court_records_68.png)](images/estonian_court_records_68.png)   | [![Estonian Court Records p. 173](images/estonian_court_records_173.png)](images/estonian_court_records_173.png)   |

## Transkribus Typewriter 0.1
**Language:** English, German, Dutch, Finnish

**Description:** General model for typewritten documents

| Text | Tech | Words     | Lines | CER train     | CER validation     |
| :---    | :---    | :---        |    :----:   |          ---: |          ---: |
| Print | HTR+ | 654961     | 73144     | 1.80%   | 1.28%   |

No training image samples available.

## Italian Administrative Hands, 1550-1700

**Language:** Italian

**Description:** The Italian Administrative Hands model features a variety of Italian-language documents from state archives in Milan, Venice, Florence, Pisa, and Genoa. The training set represents a spectrum of humanistic, italic and cursive hands characteristic of administrative records, employed by secretaries and newswriters. The model has been trained to perform well with a mix of quantitative and qualitative information as well as many common proper nouns for the period, such as locations in Europe and contemporary rulers. Administrative documents often employ common superscript abbreviations, which the accompanying documentation treats in greater detail. The model can also be used with Latin, Spanish and French documents to some extent. The model represents a collaboration between Jake Dyble (Exeter/Pisa), Antonio Iodice (Exeter/Genoa), Sara Mansutti (Cork), and Rachel Midura (Virginia Tech). Documentation at https://emdigit.org/tool/2020/07/21/italian-administrative-hands.html.

| Text | Tech | Words     | Lines | CER train     | CER validation     |
| :---    | :---    | :---        |    :----:   |          ---: |          ---: |
| Handwritten | HTR+ | 67361     | 7193     | 9.15%   | 10.80%   |

No training image samples available.

## Typewritten/print\_early_1900
**Language:** Dutch

**Description:** The National Archives Netherlands have made this model for typewritten and print writings which were used in the Netherlands during the late 19th and early 20th century.

For more information regarding the background of the model read this article (Dutch): https://www.nationaalarchief.nl/beleven/nieuws/klussen-aan-nieuw-tekstherkenningsmodel-transkribus-platform 

| Text | Tech | Words     | Lines | CER train     | CER validation     |
| :---    | :---    | :---        |    :----:   |          ---: |          ---: |
| Print | HTR+ | 72170     | 13700     | 1.65%   | 3.24%   |

**Ground Truth Examples**
| 59     | 94 | 108     | 191     |
| :---        |    :----:   |          ---: |          ---: |
| [![Typewritten/print p. 59](images/type_print_59.png)](images/type_print_59.png)      | [![Typewritten/print p. 94](images/type_print_94.png)](images/type_print_94.png)      | [![Typewritten/print p. 108](images/type_print_108.png)](images/type_print_108.png)   | [![Typewritten/print p. 191](images/type_print_191.png)](images/type_print_191.png)   |

## Danish 1870-1950 v3.5 
**Language:** Danish

**Description:** General Model for Danish handwriting from 1870-1950.

Newer incrementation of Danish 1870-1950 with added material and further experimentation with base models.

Using material from The Royal Danish Library, Aarhus City Archive, Faxe Archive, Næstved Archive and Gentofte Archive. 

| Text | Tech | Words     | Lines | CER train     | CER validation     |
| :---    | :---    | :---        |    :----:   |          ---: |          ---: |
| Handwritten | HTR+ | 1603622    | 372704     | 7.68%   | 5.91%   |

No training image samples available.


## Gothenburg\_police\_reports_1868-1902
**Language:** Swedish

**Description:** This model is trained from reports from the Gothenburg Police Detective department 1868-1902, held at the Swedish National Archives in Gothenburg. The groundtruth for the model training consists of transcribed spreads from 1873, 1880, 1888, and 1896.

| Text | Tech | Words     | Lines | CER train     | CER validation     |
| :---    | :---    | :---        |    :----:   |          ---: |          ---: |
| Handwritten | HTR+ | 165060    | 27931     | 2.85%   | 2.70%   |

**Ground Truth Examples**
| 318     | 364 | 385     | 422     |
| :---        |    :----:   |          ---: |          ---: |
| [![Gothenburg police p. 318](images/gothenburg_police_318.png)](images/gothenburg_police_318.png)      | [![Gothenburg police p. 364](images/gothenburg_police_364.png)](images/gothenburg_police_364.png)      | [![Gothenburg police p. 385](images/gothenburg_police_385.png)](images/gothenburg_police_385.png)   | [![Gothenburg police p. 422](images/gothenburg_police_422.png)](images/gothenburg_police_422.png)   |


## Transkribus print 0.1
**Language:** Danish, Dutch, German, Finnish, French, Latin, Swedish

**Description:** A first attempt to create a large model for printed historical documents. The model should be able to read historical Danish, Dutch, German, Finnish, French, Latin, and Swedish with good quality. Note: If you have printed material in other languages use this model as basemodel for training to speed up the creation of your special models.

| Text | Tech | Words     | Lines | CER train     | CER validation     |
| :---    | :---    | :---        |    :----:   |          ---: |          ---: |
| Print | HTR+ | 3661935    | 592933    | 2.18%   | 1.50%   |

No training image samples available.


## Noscemus GM 2.2

**Language:** Latin, Greek, German et al.

**Description:** The "NOSCEMUS General Model" is able to read printed Latin text, especially from the 15th, 16th, 17th and 18th century. The model was released by Stefan Zathammer and it is based on training data coming from the Digital Sourcebook of the NOSCEMUS project (https://www.uibk.ac.at/projects/noscemus/)

For the 2nd revised and updated version a substantial amount of new pages was added, including prints from the 15th century, texts set in Fraktur and texts with a considerable amount of Greek passages.

Although the model is tailored towards transcribing (Neo-)Latin texts set in Antiqua-based typefaces, it is also, to a certain degree, able to handle Greek words and words set in (German) Fraktur.

The NOSCEMUS project has received funding from the European Research Council (ERC) under the European Union’s Horizon 2020 research and innovation programme (grant agreement No. 741374).

| Text | Tech | Words     | Lines | CER train     | CER validation     |
| :---    | :---    | :---        |    :----:   |          ---: |          ---: |
| Print | HTR+ | 345878    | 52459    | 0.39%   | 0.79%   |

No training image samples available.

## DiJeSt for Hebrew Script Languages

**Language:** Hebrew, Yiddish, Ladino, Judeo-Arabic

**Description:** Trained on a mix of historic Hebrew scripts and languages, in the framework of the project DiJeSt. For details: 
http://dijest.net/gtmodel

| Text | Tech | Words     | Lines | CER train     | CER validation     |
| :---    | :---    | :---        |    :----:   |          ---: |          ---: |
| Print | HTR+ | 774192    | 79483    | 1.80%   | 1.56%   |

**Ground Truth Examples**
| 1     | 41 | 65     | 1322     |
| [![DiJeSt for Hebrew Script Languages p. 1](images/dijest_1.png)](images/dijest_1.png)      | [![DiJeSt for Hebrew Script Languages p. 41](images/dijest_41.png)](images/dijest_41.png)      | [![DiJeSt for Hebrew Script Languages p. 65](images/dijest_65.png)](images/dijest_65.png)   | [![DiJeSt for Hebrew Script Languages p. 1322](images/dijest_1322.png)](images/dijest_1322.png)   |