<h1>Datensatz Netzwerkforschung Kohlekommission Testat SS20 aj037</h1>


Codebuch Stand 2020-15-07 <p>
erstellt von Antonio Jung


<h2>Inhalt</h2>
<ul>
  <li>Edges.csv (Edgelist)</li>
  <li>Nodes.csv (Nodelist)</li>
  <li>Codebuch.md (Codierung der Datensätze)</li>
 </ul>

<h2>Ursprung und Datenerhebung</h2>

Der Bundestag hat am 03.07.2020 den Ausstieg aus dem Kohlestrom bis 2038 beschlossen. Dem zuvor arbeitete die sogenannte "Kohlekommission" mehrere Jahre an der Vorbereitung des Ausstiegs. Mit diesem Projekt möchte ich das Netzwerk der 31 Mitglieder der Kohlekommission analysieren. <p>
Der Datensatz wurde auf Grundlage folgendes Links erhoben: https://www.klimareporter.de/deutschland/das-sind-die-mitglieder-der-kohlekommission. <p>
Untersucht wird, in welchen Organisationen die Mitglieder der Kohlekommission Mitglied sind. 


<h2>Edge-Attribute</h2>

- from (id Mitglied der Kommision) <p>  
- to (alle Mitgliedschaften der Person, soweit recherchierbar, dazu gehört z.B. politische Partei, Unternehmen, Verbände, Vereine und weitere Organisationen: achten Sie darauf, dass alle ids auch genau so in der Nodelist auftauchen, dort aber nur ein Mal)


<h3>id</h3>

(eindeutige Codierung des Knoten) <p>
codiert nach Nachname, jede ID entspricht einem Mitglied der Kohlekommission



<h2>Node-Attribute</h2>

<h3>id</h3>
Identische ID wie aus der edgelist zur Identifikation der Knoten.

<h3>type</h3>
Netzwerk ist ein two-mode-Netzwerk mit zwei Typen von Akteuren/Knoten: <p>

0=Personen <p>
1=Organisationen

<h3>sex</h3>
1=männlich <p>
2=weiblich

<h3>age</h3>
1=unter 40 <p>
2=40-50 <p>
3=51-60 <p> 
4=61-70 <p>
5=71 und älter <p>


<h3>party</h3> 
Mitgliedschaft in politischer Partei

1=keine politische Mitgliedschaft <p>
2= CDU <p>
3=CSU <p>
4=SPD <p>
5=Grüne <p>
6=FDP <p>

<h3>representation</h3> 
Funktion des Mitglieds innerhalb der Kommission: <p>
1=Politik <p>
2=Wirtschaft <p>
3=Gewerkschaft <p>
4=Umwelt <p>
5= Regionen <p>
6=Wissenschaft <p>


<h3>position</h3>

1=Vorsitz <p>
2=Mitglied <p>
3=kein Stimmrecht <p>


<h3>state</h3> 
1=Niedersachsen <p>
2=Berlin <p>
3=Brandenburg <p>
4=NRW <p>
5=Sachsen <p>
6=Hessen <p>
7=Bayern <p>
8=Baden-Württemberg <p>


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
