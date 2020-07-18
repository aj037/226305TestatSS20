<h1>Datensatz Netzwerkforschung Kohlekommission Testat SS20 aj037</h1>


Codebuch Stand 2020-15-07 <p>
erstellt von Antonio Jung


<h2>Inhalt</h2>
* Edges.csv (Edgelist)
* Nodes.csv (Nodelist)
* Codebuch.md (Codierung der Datensätze)

<h2>Ursprung und Datenerhebung</h2>

Der Bundestag hat am 03.07.2020 den Ausstieg aus dem Kohlestrom bis 2038 beschlossen (faz). Dem zuvor arbeitete die sogenannte "Kohlekommission" mehrere Jahre an der Vorbereitung des Ausstiegs. Mit diesem Projekt möchte ich das Netzwerk der 31 Mitglieder der Kohlekommission analysieren.
Ich habe den Datensatz über folgenden Link erhoben: https://www.klimareporter.de/deutschland/das-sind-die-mitglieder-der-kohlekommission (Primärquelle). Ergänzt werden die Personendaten durch das Munzinger Archiv.Untersucht wird, in welchen Organisationen die Mitglieder der Kohlekommission Mitglied sind. 


<h2>Edge-Attribute</h2>


- from (id Mitglied der Kommision),  
- to (alle Mitgliedschaften der Person, soweit recherchierbar, dazu gehört z.B. politische Partei, Unternehmen, Verbände, Vereine und weitere Organisationen: achten Sie darauf, dass alle ids auch genau so in der Nodelist auftauchen, dort aber nur ein Mal)


<h3>id</h3>


(eindeutige Codierung des Knoten)
codiert nach Nachname, jede ID entspricht einem Mitglied der Kohlekommission



<h2>Node-Attribute</h2>


<h3>id</h3>
Identische ID wie aus der edgelist zur Identifikation der Knoten.

<h3>type</h3>
Netzwerk ist ein two-mode-Netzwerk mit zwei Typen von Akteuren/Knoten:


0=Personen 
1=Organisationen




<h3>sex</h3>
1=männlich
2=weiblich




<h3>age</h3>
1=unter 40
2=40-50
3=51-60
4=61-70
5=71 und älter


<h3>party</h3> 
(Mitgliedschaft in politischer Partei),


1=keine politische Mitgliedschaft
2= CDU
3=CSU
4=SPD
5=Grüne
6=FDP


<h3>representation</h3> 
Funktion des Mitglieds innerhalb der Kommission: 
1=Politik
2=Wirtschaft
3=Gewerkschaft
4=Umwelt
5= Regionen
6=Wissenschaft


<h3>position</h3>


1=Vorsitz
2=Mitglied
3=kein Stimmrecht


<h3>state</h3> 
1=Niedersachsen
2=Berlin
3=Brandenburg
4=NRW
5=Sachsen
6=Hessen
7=Bayern
8=Baden-Württemberg


<h3>name</h3>
falls ID Abkürzung, hier ausgeschrieben

HTW	Hochschule für Technik und Wirtschaft Berlin

BWB	Berliner Wasserbetriebe

BWO	Bundesverband der Windparkbetreiber Offshore

DIW	Deutsches Institut für Wirtschaftsforschung

MIBRAG	Mitteldeutschen Braunkohlengesellschaft 

DRK	Deutsches Rotes Kreuz

BDA	Bundesvereinigung der Deutschen Arbeitgeberverbände

BDEW	Bundesverbands der Energie- und Wasserwirtschaft

BDI	Bundesverband der Deutschen Industrie 

GVB	Genossenschaftsverband Bayern

VKU	Verband Kommunaler Unternehmen

SD	Stadtentwässerung Dresden

Alba	Entsorgungskonzern Alba

DIHT	Deutscher Industrie- und Handelskammertag

BfB	Initiative "Buirer für Buir"

KAD	Klimaallianz Deutschland

GZW	Grüne Zukunft Welzow

Spre	Stadt Spremberg Rathaus (Bürgermeisterin) 

KSKK	Kreissparkasse Köln

LEENRW	Landesverband Erneuerbare Energien Nordrhein-Westfalen 

IGBCE	Industriegewerkschaft Bergbau, Chemie, Energie

DGB	Deutscher Gewerkschaftsbund

GP	Greenpeace

BUND	Bund für Umwelt- und Naturschutz Deutschland

RNE	Rat für nachhaltige Entwicklung der Bundesregierung

DNR	Dachverband Deutscher Naturschutzring

NBG	Nationales Begleitgremium zur Endlagersuche

BfAN	Bundesagentur für Arbeit Nürnberg

DVPW	Deutsche Vereinigung für Politische Wissenschaft

GEE	Gesellschaft für Energiewissenschaft und Energiepolitik

IPCC	Weltklimarat

PIK	Potsdam Inatitut für Klimafolgenforschung

CAU	Christian-Albrechts-Universität Kiel

IAB	Institut für Arbeitsmarkt- und Berufsforschung

IMWS	Fraunhofer-Institut für Mikrostruktur von Werkstoffen und Systemen

MLU	Martin-Luther-Universität Halle-Wittenberg

BT	Bundestag

AWE	Ausschuss für Wirtschaft und Energie

EUD	Europa-Union Deutschland (EUD)

KK Kohlekommission
