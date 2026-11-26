## ANALYS OCH BESKRIVNING ##

## BESKRIVNING AV PROGRAM##
Programmet returnerar olika biljettpriser beroende på vilken ålder som anges.

## ANALYS ##
Utifrån de angivna kraven i uppgiften kunde jag rätt snabbt lokalisera att ett fel i koden var:
 if age <= 13:
            return 50
Eftersom att det i kravet står att åldrar mellan 0 och 12 ska vara 50, inte 13. 
När detta var korrigerat ville jag dubbelkolla att testerna passerade detta och lade till (12, 50) och (13, 100). Detta passerade. Jag ville sedan vara extra säker och adderade därför (64, 100) (65, 80) för att se att de även passerade här. Vilket det gjorde :)


