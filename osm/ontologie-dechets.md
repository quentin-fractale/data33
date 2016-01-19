# Comment décrire les équipements liés aux déchets dans OSM (dans un contexte français)

## les équipements collectifs à destination de tous

### container collectif
#### poubelle publique -> [Wiki OSM](http://wiki.openstreetmap.org/wiki/FR:Tag:amenity%3Dwaste_basket)
![Poubelle publique](http://wiki.openstreetmap.org/w/images/thumb/2/22/M%C3%BClleimer_%C3%96PNV.JPG/200px-M%C3%BClleimer_%C3%96PNV.JPG)
> amenity=waste_basket

#### bac déchets ménagers collectifs -> [Wiki OSM](http://wiki.openstreetmap.org/wiki/FR:Tag:amenity%3Dwaste_disposal)
![Container collectif d'apport de poubelles ménagères](http://wiki.openstreetmap.org/w/images/thumb/6/6b/Waste_container.jpg/200px-Waste_container.jpg)
> amenity=waste_disposal
> waste=trash
    
#### container à verre -> [Wiki OSM](http://wiki.openstreetmap.org/wiki/FR:Tag:amenity%3Drecycling)
![Container à verre](https://upload.wikimedia.org/wikipedia/commons/thumb/2/22/Glass_salvage_container_in_Paris%2C_April_2011.jpg/640px-Glass_salvage_container_in_Paris%2C_April_2011.jpg)
> amenity=recycling
> recycling_type=container
> recycling_glass=yes
> recycling:glass_bottles=yes

#### container à vêtements -> [Wiki OSM](http://wiki.openstreetmap.org/wiki/FR:Tag:amenity%3Drecycling)
![container à vêtements](https://upload.wikimedia.org/wikipedia/commons/thumb/4/46/Cabine_Oxfam.JPG/360px-Cabine_Oxfam.JPG)
> amenity=recycling
> recycling_type=container
> recycling_clothes=yes
> operator=

#### compostage collectif -> [Wiki OSM](http://wiki.openstreetmap.org/wiki/FR:Tag:amenity%3Drecycling)
![container à déchets organiques](https://upload.wikimedia.org/wikipedia/commons/thumb/f/f6/Pavillon_compostage_Montreuil_2011.jpg/320px-Pavillon_compostage_Montreuil_2011.jpg?uselang=fr)
> amenity=recycling
> recycling_type=container
> recycling:organic=yes
> operator=

#### piles et batteries -> [Wiki OSM](http://wiki.openstreetmap.org/wiki/FR:Tag:amenity%3Drecycling)
![container à piles et batteries]()
> amenity=recycling
> recycling_type=container
> recycling:batteries=yes
> operator=

#### plastique -> [Wiki OSM](http://wiki.openstreetmap.org/wiki/FR:Tag:amenity%3Drecycling)
![container à plastique]()
> amenity=recycling
> recycling_type=container
> recycling:plastic=yes
> recycling:plastic_bottles=yes
> recycling:plastic_bags=yes
> recycling:plastic_packaging=yes
> operator=

#### métal -> [Wiki OSM](http://wiki.openstreetmap.org/wiki/FR:Tag:amenity%3Drecycling)
![container à métaux]()
> amenity=recycling
> recycling_type=container
> recycling:cans=yes
> operator=

#### bouchon plastique -> [Wiki OSM](http://wiki.openstreetmap.org/wiki/FR:Tag:amenity%3Drecycling)
![container pour les bouchons plastiques]()
> amenity=recycling
> recycling_type=container
> recycling_clothes=yes
> operator=

#### déchèteries -> [Wiki OSM](http://wiki.openstreetmap.org/wiki/FR:Tag:amenity%3Drecycling)
![Déchèteries](http://wiki.openstreetmap.org/w/images/c/c2/WertstoffhofWeitnau.jpg)
> amenity=recycling
> recycling_type=centre
> Types de matériaux recyclés -> [Wiki OSM](http://wiki.openstreetmap.org/wiki/FR:Tag:amenity%3Drecycling#Mat.C3.A9riaux)
> operator=
> opening_hours=*

#### station pour camping car ->[Wiki OSM](http://wiki.openstreetmap.org/wiki/FR:Tag:amenity%3Dwaste_disposal)
![Station pour camping car](http://wiki.openstreetmap.org/w/images/b/b0/Fr-CE24-Station_vidange_caravanes.gif)
> amenity=waste_disposal
> waste_disposal:grey_water=Yes/No (eaux grises : vaisselle, douche)
> waste_disposal:chemical_toilet = Yes / No (WC chimique)
> waste_disposal:trash=Yes/No (poubelle)
> fee=Yes/no/x€ (payant ou non, prix) 


## le traitement "public" des déchets
Dans ce paragraphe, les déchets sont déjà regroupés et vont subir des opérations pour soit les détruire soit les acheminer vers les filières de valorisation et/ou de recyclage :

### centre de tri ->[Wiki OSM](http://wiki.openstreetmap.org/wiki/Tag:amenity%3Dwaste_transfer_station)
> amenity=waste_transfer_station

### décharge, centre d'enfouissement, ... ->[Wiki OSM](http://wiki.openstreetmap.org/wiki/Tag:landuse%3Dlandfill)
![Décharge](https://upload.wikimedia.org/wikipedia/commons/a/ac/Landfill_Hawaii.jpg)
> landuse=landfill


### incinérateur de déchets ->[Wiki OSM](http://wiki.openstreetmap.org/wiki/FR:Key:generator:source)
> power=generator
> generator:source=waste


### centre de compostage
![Plate-forme de compostage](https://upload.wikimedia.org/wikipedia/commons/thumb/6/67/Tas_de_compost%2C_sur_une_plateforme_de_compostage..JPG/320px-Tas_de_compost%2C_sur_une_plateforme_de_compostage..JPG?uselang=fr)
> amenity=recycling
> recycling_type=centre
> recycling:organic=yes
> recycling:green_waste=yes
> recycling:garden_waste=yes
> operator=*
> opening_hours=*
> fee=Yes/no/x€ (payant ou non, prix) 