

# Word Formation in Ancient Greek
![](Images/Classic_Tree_02.jpeg)

---

## Introduction

1. This is the site of the Project “Word Formation in Ancient Greek”.
2. The purpose of this project is to create a new handbook of Word Formation in the footsteps of Debrunner and Risch.
3. This site is under construction.

   ---
   
![](Images/Site_under_construction_02.png) 
---
## Database

1. The nucleus of the project is a **database** containing the **Liddle-Scott-Jones Dictionary** provided by the Perseus Project. 
2. The LSJ has been take from **Celano**'s  [Unicode LSJ](https://github.com/gcelano/LSJ_GreekUnicode)
3. This dictionary contains 116.500 lemmata.
4. The information is encoded in xml.
   
![Πείθω](Images/DataBase_XML.png)

---
## Tagging

1. Each lemma is tagged for the following information:
    - Segmentation
    - Word class
    - Suffixes
    - Prefixes.
    - Infixes.
    - Gender
    - Accent
    - Family root
    - ...
2. The tagging is both manual and automatic.
3. Structure of the DB (partial information):
   
![DB](Images/DB_Structure.png)

---
## Data extraction

1. Many of the processes are automatized taking as starting point the manually tagging.
2. The derivation of each lemma is extracted automatically, once the first base of each lemma has been manually established:
![](Images/Extraction.png)
3. This video shows the automatic extraction: [vídeo] ([video.html](https://github.com/pajaro1966/GreekWordFormation/blob/main/Images/Extraction_02.mp4))

<iframe src="video.html" title="Vídeo"></iframe>

---

## Graphics

1. The database allows the automatical creation of graphics representing the derivation of each lemma.
   
2. The graphics are created in Markdown using [Mermaid](https://mermaid.js.org). 
![](Images/Mermaid.png)

3. The following image (svg) depicts a provisional representation of the word family πείθω (‘to persuade’):

![Πείθω](Images/Peitho_Colores_02.png)

---
## Some references

1. Debrunner A. (1917). Griechische wortbildungslehre. C. Winter.
2. Emde Boas E. van. (2019). The cambridge grammar of classical greek. University Press.
3. Risch E. (1937). Wortbildung der homerischen sprache von ernst risch. W. de Gruyter.
