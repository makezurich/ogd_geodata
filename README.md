# Open Geodata
**Repo for open geodata required for specific challenges of MakeZurich**


# Geodata for the **City-Forest-Challenge**:

- Forest Area of the Canton Zürich: *[ktzh_forestarea_groundcover_a.zip](https://github.com/make-zurich/ogd_geodata/blob/master/ktzh_forestarea_groundcover_a.zip)*

Actually, I couldn't find a complete **network** dataseta of all existing **pathes** within the forests. So, there are actually two different data sources:

- 1. [Ground cover data](https://opendata.swiss/de/dataset/amtliche-vermessung-bodenbedeckung-dm01avzh24): where it's possible to extract 
    
    - the **"Forest Paths"** (befestigt.Strasse_Weg.Waldstrasse) and 
    - the **"Bicycle and Pedestrian Paths"** (befestigt.Strasse_Weg.Velo_Fussweg). Those paths exist also outside of the forests of course. But I haven't cut them already with the forest borders...
    - Both groundcover areas can be found in *[stzh_foreststreets_pedestrian-nd-bikepathes_groundcover-a.zip](https://github.com/make-zurich/ogd_geodata/blob/master/stzh_foreststreets_pedestrian-nd-bikepathes_groundcover_a.zip)*. They can be distincted by the attribute "art_text".
    
    
 - 2. Forest development plan from 2011 (Waldentwicklungsplan 2011) which contains:
    - hiking network of the Canton Zürich *[ktzh_hiking_network_wep10.zip](https://github.com/make-zurich/ogd_geodata/blob/master/ktzh_hiking_network_wep10.zip)* and
    - horse riding paths of the Canton Zürich *[ktzh_ridingpathes_wep10.zip](https://github.com/make-zurich/ogd_geodata/blob/master/ktzh_ridingpathes_wep10.zip)*
    --> Both are not containing all the existing forest pathes. I don't know anything about the definition of these pathes...



