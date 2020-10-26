## Opgelost
##### melding: Backwardscompatible maken	
oplossing: Relatie Bodemkaart bestaat uit één of meer BodemvlakCollecties is geschrapt en hersteld naar Bodemkaart bestaat uit één of meer Kaartvlakken.
oplossing: Relatie Bodemvlakcollectie bestaat uit één of meer Kaartvlakken is omgedraaid naar Kaartvlak maakt onderdeel uit van één BodemvlakCollectie
oplossing: Kardinaliteit van de attributen 'kenmerken bovenlaag' en 'kenmerken onderlaag' is hersteld van 0..2 naar 0..*
oplossing: In gegevensgroeptype BodemEenheid is attribuut bodemhoofdklasse met codelijst Bodemhoofdklasse  hersteld.

##### melding: Mnemonic EPL van registratieobject is onjuist.	
oplossing: EPL is vervangen door SGM

##### melding: Herkomst definitie afgeleid profiel ontbreekt.	
oplossing: Toegevoegd: herkomst definitie = BRO

##### melding: "4.3.10.9 kalkgehalte: - waardebereik BRO tot BRO  moet of ingevuld worden of leeg && 4.3.10.10 Fe-dith: -waardebereik BRO to BRO  moet of ingevuld of leeg"	
##### melding: 4.3.10.10 Fe-dith: -waardebereik BRO to BRO  moet of ingevuld of leeg" 
oplossing: Aangepast. Waardebereik is leeg voor beide attributen
	
## Niet opgelost:
##### melding: Backwardscompatible maken	
reden niet opgelost: Attribuut Standaardprofielverwijziging van het attribuut RegistratieObjectcode is niet hersteld.

##### melding: "afzettingskarakteristiek: - waardelijst.  mist link naar waardelijst in het document en “type”: waardelijst uitbreidbaar niet ingevuld.
##### melding: - zelfde geldt voor 4.3.6.1 bodemhelling, 4.3.7.1 bodemkundigbelang, 4.3.8.2 bodemeenheid, 4.3.2.1 staringreeksbouwsteen, 4.3.2.1 afzettingskarakteristiek  alle waardelijsten in catalogus."	
reden niet opgelost: Waardenlijsten zijn opgenomen in de catalogus en dit zijn de voor de BRO juridisch vastgestelde waardenlijsten. Verwijzing naar catalogus zelf lijkt niet logisch. Waardenlijsten worden met type Codelist opgenomen omdat ze extern beheerd worden en t.b.v. technische flexibiliteit niet in de berichtschema's (anders enumeratie).

##### melding: "4.3.10 pH-KCI: Eenheid; -pH  dimensieloos.  "	
reden niet opgelost: pH komt voor in https://ucum.org/ucum.html

##### melding: 5.9 Regio: omschrijving is leeg.  -> check in Respec omdat wel in UML bij codelijst en attribuut een definitie/omschrijving is opgenomen. 	
reden niet opgelost: Regio's zijn indicatief en nader toegelicht in de toelichting van de totstandkoming. Ze kunnen niet nader worden gedefinieerd in de waardenlijsten.
