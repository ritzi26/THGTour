# THGTour
Tour durch das THG Aalen

Clappr Quellen:
https://github.com/clappr
https://github.com/clappr/clappr-core
https://github.com/thiagopnts/clappr-video360

Jakob hats auch geschaft!!

Array inhalt nach diesem Formalt verwenden:
Gänge (anpassbar nach folgendem Schema
  ['n', server[serverwahl]+'/res/THG/VID_1OG.mp4', x, y, Id1OG, z, true, false],)
  n: Name des Labels
  x: Startzeit zu der das Label auftaucht
  y: Endzeit zu der das Label verschwindet
  z: die Zeit zu der das neue Video beginnt

  Treppe:
    ['Treppe', server[serverwahl]+'/res/THG/VID_TrepOst.mp4', 0, 3, IdTrepOst, 30, true, false]
  EG:
  - rechts (Aula & Gang vorne):
    ['1-EG', server[serverwahl]+'/res/THG/VID_EG_1.mp4', 8, 12, IdEG1, 0, true, false],
  - links (Musik und Deutsch):
    ['2-EG', server[serverwahl]+'/res/THG/VID_EG_2.mp4', 8, 12, IdEG2, 0, true, false],

  1.OG:
    ['1.OG', server[serverwahl]+'/res/THG/VID_1OG.mp4', 8, 12, Id1OG, 0, true, false],  
  2.OG:
    ['2.OG', server[serverwahl]+'/res/THG/VID_2OG.mp4', 8, 12, Id2OG, 0, true, false],
  3.OG:
    ['3.OG', server[serverwahl]+'/res/THG/VID_3OG.mp4', 8, 12, Id3OG, 0, true, false],

Räume (anpassbar nach folgendem Schema
  ['n', server[serverwahl]+'/res/THG/Vid_Oberstufe.mp4', x, y, IdObers , 1, false, false], )
  n: Name des Label
  x: Auftauchzeit des Label
  y: Endzeit des Label

  Oberstufenzimmer:
    ['Oberstufe', server[serverwahl]+'/res/THG/Vid_Oberstufe.mp4', 20, 25, IdObers , 1, false, false]


die Download server sind in der Array server[serverwahl] veränderbar und durch serverwahl auswählbar.
