# MOS5.5 Data Visualisation-Travail 1 :
  
 # ARC Diagram
  
  ## I - Description
  
   <img src="arc_diagram.png"/>
   
  Le diagramme " ARC Diagram " est une maniére pour représenter un diagramme réseaux à deux dimensions. 
  Dans un ARC Diagram, les noeuds sont placées tous au long d'une ligne (un simple axe qui représente la 1ére dimension)
  et les arcs sont utilisés pour montrer les connections entre les divers noeuds.
  
  Dans certaions cas on peut utilisé l'épaisseur  de chaque arc comme un indicateur sur la nature de la connection entre les noeuds       (exemple : fréquence) noeud source et noeud destination .
  
  ARC Diagram est trés utilisé pour clairement lire la coocurrence dans les données.
  
  Le point faible de ce type de diagramme (comme le plupart des graphique à deux dimensions) qu'il peut devenir illisible dans le cas on   aura plusieurs connections entre les noeuds : probléme de chevauchement et d'encombrement.
  
  ## II - Exemples :
  
  ### 1) Données :
  
  <i>Fichier JSON</i>
  On a un fichier JSON ou les données sont structuré de la façon suivante:
  Un objet JSON comportant deux tableaux :
 <table>
  <tr><th> -Tableaux noeuds :</th><td><img src="data1.png"/></td></tr>
 
  <tr><th> -Tableaux arcs : </td><td><img src="data2.png"/></td></tr>
 </table>
  Le tableau noeuds comporte des objets chaque objet a un attribut name et un attribut group l'attribut groupe varie entre 1 et 8  
 

   ### 2)  Code D3
    <img src="resultatFinal.png"/>
  <i>Si vous étes intéressé par ce diagram vous pouvez découvrir le code pour l'utilisé avec la bibliothéque de javascript JS</i>
  <a href='http://bl.ocks.org/sjengle/5431779'>Pour le reste de code cliquez ici  </a>[1]
 
  ## V - Sources

* <a href='http://bl.ocks.org/sjengle/5431779'>exemple complet</a>[1]
