# ElectricityCalculations
Used to keep track of my electricity costs and savings by PV system

This excel sheet is used to calculate the return of the PV investment.

Very specific to Sweden and SolarEdge Inverter

# Daily Usage
I SolarEdge Designer kan man simulera sin anläggning. Det finns dock en viktig brist, det finns ingen förbrukningsprofil som är lämplig för en eluppvärmd villa i Sverige.
Så egenkonsumtionen är idag baserad på att du förbrukar exakt samma mängd el varje månad, året runt.

Jag skapade en enkel CSV fil som du kan använda om du vill ha en bättre simulering av elförbrukningen.

CSV filen bygger på följande antagande:
Snittförbrukningen per månad de senaste åren
Förbrukningen är samma alla dagar i månaden
Du har några procent mer förbrukning på morgonen och kvällen.

Du kan justera värdena, year data och Usage profile och spara första fliken som CSV utf-16, och importera denna fil i SolarEdge Designer
