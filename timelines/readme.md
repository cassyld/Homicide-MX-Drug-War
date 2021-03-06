﻿Homicide in Mexico by month
================================================
Two scripts to explore how have the different military operations
affected the annualized monthly homicide rate. One for the states
where there have been military operations and the other for Ciudad
Juarez since it is the city with the highest murder rate in the whole world.

Output
------
* Time series of the homicide rate in states with high homicide rates
  or states where the military has been sent, with loess lines added
  and grouped into before and after military operations.
* Chart of the murder rate in Ciudad Juarez before and after the military took over

Data
-----
Because the INEGI has a limit of ~100,000 cells in the files you can download, the data was divided into 3 files:

_county-month.csv.bz2_: Michoacan, Chihuahua, Durango, Sonora, Baja California (not Norte), Sinaloa, Durango

_county-month-gue-oax.csv.bz2_: Oaxaca and Guerrero

_county-month.csv-tam-nl.bz2_: Tamaulipas and Nuevo Leon

Interesting Municipalities
---------------------------
These municipalities are worth checking out because of the great increase in the homicide rate they suffered in 2008 (from the choropleths)

_Guerrero_

Bordering the state of Michoacán: Zirándaro, Coyuca de Catalán, Unión de Isidoro Montes de Oca

_Chihuahua_

The municipalities bordering the US excluding Juárez: Janos, Ascensión, Juárez, Guadalupe, Ojinaga, Ahumada, Nuevo Casas Grandes ,Coyame del Sotol


Codebook
--------
Variable used to download the data from the INEGI:

Tipo de defunción : Homicidio

Consulta de: Defunciones accidentales y violentas   Por: Ent y mun de ocurrencia, Año de ocurrencia y Mes de ocurrencia   Según: Año de registro

The columns of the database correspond to:

Code - Numeric code for each state and county

County - Name of each county

Year.of.Murder - The year in which the murder _occurred_

Month.of.Murder	- The month in which the murder _occurred_

1990 ... 2008 - The rest of the columns correspond to the year in which the murder was _registered_

The weird order of the database is because the website of the INEGI is a steaming pile of broccoli an only lets you download the data ordered by the year in which the murder was registered.

Sources:
--------
__Homicide Data 1990-2008:__

[INEGI](http://www.inegi.org.mx/est/contenidos/espanol/proyectos/continuas/vitales/bd/mortalidad/MortalidadGeneral.asp?s=est&c=11144)

__Military Deployment Dates:__

Unless otherwise noted all deployment dates come from the [SSP](http://www.ssp.gob.mx/portalWebApp/ShowBinary?nodeId=/BEA%20Repository/270970//archivo) [PDF] p. 21-24

Michoacan: 12/11/2006

OPERATIVO CONJUNTO  TIJUANA: 01/03/2007

Operativo Conjunto Guerrero: 01/15/2007

Operativo Conjunto Triangulo Dorado or Sierra Madre: 01/22/2007, [Part II](http://www.elsiglodetorreon.com.mx/noticia/328548.a-punto-de-reiniciar-la-guerra-contra-el-narc.html): 05/01/2007, [Part III]((http://www.elsiglodetorreon.com.mx/noticia/328548.a-punto-de-reiniciar-la-guerra-contra-el-narc.html)): 02/01/2008

Operación Conjunta Tamaulipas-Nuevo León: 02/19/2007

Operativo Veracruz: 05/14/2007

[Operativo Conjunto Chihuaha](http://www.el-mexicano.com.mx%2Fnoticias%2Fnacional%2F2009%2F03%2F02%2Fsitian-militares-ciudad-juarez.aspx&ei=OoZgS-nmA4XYtgOHwpGzCw&usg=AFQjCNH5AvHSTNwSpMPqT98OuiSYA8kbjg&sig2=rucCCB325xG_lYgmU_Rodw): 03/27/2008. Keep in mind that there were already 539 soldiers on the ground by the time it was announced
[juarezpress](http://www.eluniversal.com.mx/nacion/166104.html)

[Operación Conjunta Culiacán-Navolato](http://www.tabascohoy.com.mx/nota.php?id_nota=155210): 05/13/2008

[Operativo Sonora I](http://www.elimparcial.com/busqueda/TraerNota.aspx?Numnota=295876): 03/07/2008

[Reinforcements for Ciudad Juarez](http://eleconomista.com.mx/notas-online/politica/2009/03/01/arriban-militares-ciudad-juarez): 03/01/2009

[Vicente Fox sends troops to Nuevo Laredo](http://www.univision.com/content/content.jhtml?cid=625397) 06/13/2005

__Other Dates:__

[Alfredo Beltrán Leyva, "El Mochomo"](http://www.sedena.gob.mx/index.php?id_art=1169) captured: 01/21/2008

[Eduardo Arellano Félix, "El Doctor"](http://www.elfinanciero.com.mx/ElFinanciero/Portal/cfpages/contentmgr.cfm?docId=152259&docTipo=1&orderby=docid&sortby=ASC) arrested: 10/26/2008

__Population Data:__

CONAPO [De la población de México 2005-2050](http://www.conapo.gob.mx/00cifras/proy/municipales.xls)

__Ciudad Juarez Monthly Murder Rates in 2009:__

For the first half of the 2009
[puntoporpunto](http://www.puntoporpunto.com/informacion-general/en_juarez_suman_mil_13_asesina.php),
and for the second half of 2009
[larednoticias](http://www.larednoticias.com/detalle.cfm?s=26)

For 2010[Agencia EFE](http://www.google.com/hostednews/epa/article/ALeqM5gVsNv7FxY-In2bVMa5v0rujdQWtQ)
