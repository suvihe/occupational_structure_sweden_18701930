This data includes all census occupations from Swedish population censuses 1870 - 1930. These are available through SCB's website, either as BiSOS A (Befolknings-statistik) for 1870-1900, or as SOS Folkräkningen for 1910-1930.
The original census occupations have been standardized and coded to HISCO manually. 
The HISCO codes were decided based on matches either directly from the Swedish occupational title or through translated occupational title. I am grateful for Christer Lundh for sharing his coding, which I used to cross-check my own coding.
I will add an appendix explaining the coding behind the dataset soon.

The dataset is part of a publication:  
Heikkuri, S. (2026). Technological change and structural shifts in Sweden’s Labor Market, 1870–1930: skill upgrading or deskilling? Scandinavian Economic History Review, 1–25. https://doi.org/10.1080/03585522.2026.2624370


Variable definitions:  
occ_id = Occupation identifier  
occ_title = Standardized occupation title (English)  
sector = Major sector (1 = Primary, 2 = Secondary , 3 = Tertiary, 4 = Other)  
hisco = HISCO code  
hisco_title = HISCO description  
hisclass = HISCLASS code  
hisclass_title = HISCLASS description  
skill = Skill-level (1 = High, 2 = Medium, 3 = Low, 4 = Unskilled)  
skill_category = Skill category ("high", "medium", "low", "unskilled")  
manual = dummy for manual occupations (according to HISCLASS)  
year = Census year (1870,...,1930)  
men = total men  
women = total women  
women2 = total women (incl. agricultural wives)  
total = total men and women  
total2 = total men and women (incl. agricultural wives)  

NOTE on 1870 census:
Some occupational groups were reproted together, such as godsägare (major landowners) and hemmansägare (farmers) as well as arrendatorer and brukare (both tenant farmers). I used the 1880 proportions to estimate their numbers.
Likewise, wives were included as family members. I used the proportiong of 1880 wives and other female relatives to estimate the number of wives for 1870. 


UPDATE 2026-02-02: Dataset now available as csv-file. Data Appendix added.
UPDATE 2026-02-18: Paper now available as an online publiscation at Scandinavian Economic History Review. 
