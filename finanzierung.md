- Finanzierung
  deck:: Finanzierung
	- Literatur
	  id:: 64ec40dc-8b78-4b42-a225-43bdde689015
		- [Löffler, Gunter: Finanzierung](https://rds-ulm.ibs-bw.de/link?kid=1801847436), [website](https://finanzierungsbuch.wordpress.com)
		- Brealey, R., S. Myers: Principles of Corporate Finance. McGraw-Hill. (frühere Auﬂagen sind i.d.R. ausreichend)
		- Copeland, T., F. Weston and K. Shastri (2005): Financial Theory and Corporate Policy, 4. Auﬂage, Addison-Wesley (frühere Auﬂagen sind i.d.R. ausreichend)
		- Spremann, K.: Finance. Oldenbourg. (frühere Auﬂagen sind i.d.R. ausreichend)
		- Eine stärkere mathematische Fundierung bietet: Kruschwitz, L.: Finanzierung und Investition. (frühere Auﬂagen sind i.d.R. ausreichend)
		- [financewiki](https://www.bf.uzh.ch/financewiki/)
		- [onvista](https://onvista.de)
	- Grundlagen
	  deck:: Finanzierung::Grundlagen
		- ### Finanzierungsformen
		  collapsed:: true
		  Können nach verschiedenen Kriterien klassifiziert werden. (Löffler, S. 3)
			- Rechtsstellung der Kapitalgeber
				- Fremdkapital #card
				  id:: 6505cd4a-898b-4149-9181-9a486e935ee8
					- Der Bereitstellende wird zum Gläubiger
					- Besitzt einen vertraglich festgelegten Anspruch auf Rückzahlung, der über den Ansprüchen der Eigenkapitalgebern steht.
					- Kein Mitspracherecht
					- Höherer Anteil als [EK](logseq://graph/logseq?block-id=6505cd4f-6335-43cd-ac8e-dcf7d0b52f89) an der Finanzierung
					- Beispiele
						- Anleihe #card
						  id:: 6507fb80-d6c2-4b1c-9c0b-81064fffba10
							- Ist eine Kreditbeziehung zwischen Unternehmen und Investoren: Das Unternehmen ist der Kreditnehmer.
							- Rückzahlungsbetrag ist der Nominalwert der Anleihe
							- Auszahlungsbetrag ist der Preis den Investoren bei der Emission bezahlen.
							- Der Zinssatz wird durch den Kupon (=periodische Verzinsung) festgelegt, ist oft an einen Referenzzinssatz gekoppelt
							- Covenants (sonstige Vereinbarungen)
							- Beispiel:
								- Nullkuponanleihe #card
								  id:: 650aa4d0-dd67-429c-9b95-f2725a717b72
									- einfachster Typ eines Wertpapiers
									- zahlen keinen Kupon aus, werden daher *diskontiert verkauft*, daher auch **reine Diskontanleihen**
									- Der Nominalwert (Rückzahlungsbetrag) ist $N<P$, dem Preis
									- $N-P$ ist die Diskontierung
									- $P/N$ ist der Diskontfaktor
									- Typischerweise beträgt die Laufzeit max. 1 Jahr
								- Kuponanleihe #card
								  id:: 650aa5b1-07f7-4443-8abd-04d00784635c
									- auch: Bullet Bonds, Coupon Bearing Bonds
									- Das Zahlungsintervall ist typischerweise bezeichnet als$\Delta = 1/2$ (in diesem Fall halbjährlich)
									- Die Kuponzahlungen werden prozentual zum Nominalwert $N$ angegeben, $C_i/N$ ist die Kuponrate
						- Anzahlungen von Kunden
						- Kredit #card
						  id:: 6507faa9-de3a-447e-a808-b379aad81d10
						  Populärster Weg der FK-Beschaffung
							- Inhalt vertraglich geregelt:
								- Auszahlungsbetrag (Was bekommt der Kreditnehmer heute)
								- Rückzahlungsbetrag
								- Laufzeit
								- Zinssatz
								- Tilgungsstruktur
								- Besicherung (Hat die Bank bei Zahlungsunfähigkeit das Recht das Vermögenswerte zu pfänden?)
								- Kündigungsrechte (Beendigung vor Laufzeit durch Tilgung?)
				- Eigenkapital #card #depth-2
				  id:: 6505cd4f-6335-43cd-ac8e-dcf7d0b52f89
					- Der Bereitstellende wird zum (Mit-)Eigentümer des Unternehmens
					- Recht auf Beteiligung am Unternehmenserfolg und Stimmrecht
					- Beispiele
						- Venture Capital #card
						  id:: 6505d488-48c7-464e-a458-a6f96fcaaa68
							- Eigenkapitalgeber die auf junge Unternehmen spezialisiert sind
							- Bieten Kapital oft in Stufen bei Erreichung bestimmter Ziele
							- Unterstützung oft nicht nur monetär sondern auch im Management
							- Oft Einräumung weitreichender Kontrollrechte
						- ### Aktien
						  Verkauf erhöht das [EK](logseq://graph/logseq?block-id=6505cd4f-6335-43cd-ac8e-dcf7d0b52f89)
							- Der Stimm- und Dividendenanspruch einer Aktie ergibt sich als Anteil des Nennwertes der Aktie am Gesamtnennwert aller Aktien, alternativ  ohne expliziten Nennwert (üblicherweise) als $$\frac{1}{\text{Anzahl aller Aktien}}$$
							- Aktien werden durch einen Börsengang (auch IPO: Initial Public Offering) an der Börse notiert. Potenzielle Anleger werden über einen Emissionsprospekt (Prospectus) über das Unternehmen und die Anzahl der Aktien informiert. Anschließend beginnt die Zeichnungsfrist, in der Investoren ihre Gebote abgeben. Anhand dieser Gebote wird ein Kurs für die Aktie bestimmt, zu dem dann die Aktien anschließend verkauft werden.
							- In Deutschland ist es üblich, dass Altaktionäre bei einer Kapitalerhöhung (Schaffung neuer Aktien) ein Bezugsrecht in anteiliger Höhe ihrer Aktien bekommen.
							- Vorzugsaktien #card #bidirectional
							  id:: 6505cbc5-499c-4f6d-8876-5a5a3c4f4494
								- Aktien mit höherer Gewinnausschüttung (Dividende), dafür üblicherweise ohne Stimmrecht
							- Stammaktien #card #bidirectional
							  id:: 6505cc69-d0c0-46d8-9b74-38b56e03d75e
								- "normale" Aktien mit Stimmrecht auf der Hauptversammlung und Anteil an der Gewinnausschüttung (Dividende)
							- Der Aktienkurs wird unterschieden zwischen
								- cum Dividende #card
								  id:: 65096400-7eee-4f22-afd0-adf2a13455c2
									- vor Gewinnausschüttung
								- ex Dividende #card
								  id:: 65096410-ab8c-44e0-a0e1-34f14d08a93f
									- nach Gewinnausschüttung
			- Herkunft des Kapitals
				- Außenfinanzierung #card
				  id:: 6505cd59-d002-4e6d-8aa0-988b29b31849
					- Quelle von außerhalb des Unternehmens
					- Beispiele
						- Verkauf von Aktien -> [EK](logseq://graph/logseq?block-id=6505cd4f-6335-43cd-ac8e-dcf7d0b52f89)
						- Aufnahme eines Kredites -> [FK](logseq://graph/logseq?block-id=6505cd4a-898b-4149-9181-9a486e935ee8)
				- Innenfinanzierung #card
				  id:: 6505cd60-03e6-4083-af8b-d32311c331c1
					- Wird durch das Unternehmen selbst generiert
					- Höherer Anteil als Außenfinanzierung an der Finanzierung
					- Beispiele
						- Einbehaltung von Gewinnen -> [EK](logseq://graph/logseq?block-id=6505cd4f-6335-43cd-ac8e-dcf7d0b52f89)
						- Umschichtung (Verkauf von Immobilien, keine Zunahme des Kapitals) -> [EK](logseq://graph/logseq?block-id=6505cd4f-6335-43cd-ac8e-dcf7d0b52f89)
						- Bildung von Rückstellungen (zur Deckung zukünftiger Verbindlichkeiten) -> [FK](logseq://graph/logseq?block-id=6505cd4a-898b-4149-9181-9a486e935ee8)
		- Börsenhandel #card
		  id:: 6505ccf0-9b3a-4c26-9626-fd483f196eaa
			- Kaufaufträge (Bid) werden mit Verkaufsaufträgen (Ask) verglichen und ausgeführt.
			- Bid-Ask Spread (Geld-Brief-Spanne) $$\frac{\text{Ask}-\text{Bid}}{(\text{Bid}+\text{Ask})/2}$$ stellt die Differenz zwischen An- und Verkaufspreis prozentual zum Mittelwert der beiden dar.
		- Fremdkapitalquote #card
		  id:: 650afd66-df1a-46ca-a0d6-6bf84b1d7f18
			- $$\frac{FK}{FK+EK}$$
	- Kapitalkosten und Diskontierungsmodell
	  deck:: Finanzierung::Kapitalkosten und Diskontierungsmodell
		- Kapitalwert #card
		  id:: 650805f9-d216-4335-aa02-07f0c2831173
			- Auch: Net Present Value, NPV, Diskontierungsmodell
			- Anleger sind gegenüber Investitionen mit gleicher Auszahlung und Risiko indifferent.
			  Also lässt sich der Wert einer zukünftigen Auszahlung über den zukünftigen Wert einer anderen Investition berechnen.
			- Der Barwert einer zukünftigen Zahlung $C$ in $t$ Jahren ist dann $$K_{0} = \frac{C_{t}}{(1+r)^{t}}$$, wobei $r$ der erzielbare alternative Zinssatz ist (genannt Diskontierungsrate, Kapitalkosten oder auch Alternativertragssatz). Die zukünftige Zahlung wird *diskontiert*. Für mehrere Zahlungen $C_{t}$ wird eine Summe gebildet: $$K_{0} = \sum_{t=0}^{T}{\frac{C_{t}}{(1+r)^{t}}}$$
			- Bei Unsicherheit wird der Erwartungswert $E[C_{t}]$ und ein entsprechend höherer Alternativertragssatz verwendet.
				- Beispiel: Eine Auszahlung von 1000€ in 5 Jahren ist bei einem Zins von 2% heute $$K_{0} = \frac{1000}{1,02^{5}} = 905,73$$ wert: Man müsste heute ebendiese Summe anlegen, um in 5 Jahren ebenfalls 1000€ zu haben.
			-
		- Kapitalkosten #card
		  id:: 64f08c3a-96d2-40d7-ac3c-25ca5b1e8ed6
			- die Rendite, welche der Investor auf dem in der Unternehmung investierten Kapital erwartet. Diese Rendite stellt für die Unternehmung (als Gegenseite zum Investor) Kosten dar.
			- Fremdkapitalkosten #card
			  id:: 650804d3-f90f-40ff-b136-714e298631fd
				- Sind meist vertraglich geregelt durch Kredit und Anleihen
			- Eigenkapitalkosten #card #depth-1
			  id:: 65080508-1721-47d7-9d3a-8f76d1a3ed4a
				- Tauchen nicht in der GuV (Gewinn- und Verlustrechnung) auf, müssen aber logisch existieren, da EK-Geber ohne Dividende keine Investition tätigen
				- EK-Kosten bei uniformem Dividendenstrom #card
				  id:: 65088318-9533-4b05-b4f2-bbe8cae9dda3
					- $P_0 = \sum_{t=1}^{\infty}\frac{E[D_{t}]}{(1+e)^{t}}$, als geom. Reihe aufgelöst $P_0 = \frac{E[D]}{e}$
				- Gordon-Growth-Modell #card
				  id:: 650829b9-d062-4083-a3be-c5bedf1b8b58
					- Stellt Kapitalwert anhand eines erwarteten Wachstums der Dividenden dar.
					- Bekannt ist der aktuelle Börsenkurs $P_{0}$ und die zuletzt gezahlte Dividende $D_{0}$. Bei einem erwarteten Wachstum von $g$ ergibt sich die nächste Dividende als $D_{t} = (1+g)^{t} * D_{0}$.
					- Die Summe des Kapitalwerts sieht hiernach so aus ($r$ ist nun mit $e$ bezeichnet): $$P_{0} = \sum_{t=1}^{\infty} \frac{D_{0}(1+g)^{t}}{(1+e)^{t}}$$. Als geom. Reihe aufgelöst ergibt sich daraus die Gordon-Growth-Formel: $$P_0 = \frac{D_{0}(1+g)}{e-g}$$. Nach $e$ umgeformt wird sie verwendet um die Eigenkapitalkosten zu berechnen.
						- Vom Gewinn zur Dividende #card
						  id:: 65088820-d996-417b-ba62-38fea30eb57d
							- Da oftmals der Gewinn und nicht die Dividende prognostiziert wird, wird die Dividende als Gewinn pro Aktie mal der Ausschüttungsquote berechnet.
		- Arbitrage #card
		  id:: 650aa2bc-2f85-46d9-b46f-829dba6a631c
			- Erhalten eines **risikolosen** Gewinns durch simultanen Handel auf zwei oder mehreren Märkten
			- Beispiel: Unterschiedliche Preise von Aktien (Software, etc.) in London und New York:
			  Arbitrageur kauft bei Anfrage (on demand) des teureren Marktes (New York, 122€) auf dem günstigeren Markt (London, 115€) um im anschließenden Verkauf sicheren Profit zu realisieren
			- Besteht meist nicht lange, da Erhöhung des Angebots auf dem teureren Markt zu einer Preissenkung (und umgekehrt) führt
			- TODO Arbitragebeweis, Arbitragemöglichkeiten
			- Beispiel: In welcher der folgenden Situationen kann man Arbitrage erwarten?
				- Juli-Futures sind 30% teurer als September-Futures
		- Aktienbewertung
			- Dividendenrendite #card
			  id:: 650af971-caaa-45f9-8a29-196997f84cf5
				- $$\frac{D_0}{P_0}$$, die gezahlte Dividende im Verhältnis zum Preis
			- ROE #card
			  id:: 65088b6a-d256-4709-ba9a-65a99060ae05
				- Return on Equity, gibt an wie viel Gewinn im Verhältnis zum im Unternehmen vorhandenen EK erwirtschaftet wird.
				- Deutsch: Eigenkapitalrendite
				- $\text{ROE} = \frac{G}{EK}$
				- Lässt sich auch aus dem [Gordon-Growth Modell](logseq://graph/logseq?block-id=650829b9-d062-4083-a3be-c5bedf1b8b58) als $e$ ablesen
				- TODO Lässt sich ebenfalls darstellen als $$ROE = ROA + (ROA - i)\frac{FK}{EK}$$, schwankt also direkt proportional zum ROA (Geschäftsrisiko), der zweite Term ist das
					- Finanzierungsrisiko #card
					  id:: 65097b56-549a-46c6-8b24-812a4867974c
						- Wenn $FK/GK$ steigt, steigt auch die Unsicherheit über ROE
						- außerdem steigt auch
			- ROA #card
			  id:: 650975d0-aed4-4c28-964b-6f9bb208657d
				- Return on Assets, Gesamtkapitalrendite
				- $$ROA = \frac{G}{EK+FK}$$
			- Erwartete Rendite eines Aktionärs #card
			  id:: 650966a0-bd33-435f-ad88-4e4bb7cc0a62
				- $$E[Rendite] = \frac{E[P_1] + E[D_1]- P_0}{P_0}$$, wobei $P_0$ der Kaufpreis ist, $P_1$ Verkaufspreis
			- Residualgewinn #card
			  id:: 65097678-2085-459b-8632-e0ae3395b60b
				- $$G= X - i*FK$$
				- Gewinn der an Teilhaber ausgezahlt werden kann (nach Abzug von FK-Kosten)
			- Unternehmenswert $V_0$ #card
			  id:: 65096dec-43fb-46c8-ac5d-a442d3fd8578
				- $$V_0 = \sum_{t=1}^{\infty} \frac{E[X_t]}{(1+k)^t} $$ mit
				  |:---|:---|
				  |X |Bruttoerträge (Dividenden + Zinsen) |
				  |k |Kapitalkosten |
					- Kapitalkosten #card
					  id:: 650b050f-741d-47fc-852e-a99d2a85583f
					- $$k= e* \frac{EK}{EK+FK} + i * \frac{FK}{EK+FK}$$
					  mit 
					  |||
					  |e | EK-Kosten |
					  |EK | Wert des Eigenkapitals (Marktwert, da Entscheidung der Aktionäre vom Marktwert abhängig) |
					  |i | FK-Kosten |
					  |FK | Wert des Fremdkapitals (Marktwert)|
					  |FK / EK| Kapitalstruktur|
					  |FK / (EK+FK) | Fremdkapitalquote, Verschuldungsgrad |
					  | EK / (EK+FK) | Eigenkapitalquote |
			- Modigliani-Miller-Thesen #card #incremental
			  id:: 6509d36f-a41a-48c2-9467-96742e307ea8
				- Die Gesamtwerte V = EK + FK von
				  logseq.order-list-type:: number
				  zwei Unternehmungen mit vergleichbarem Risiko und gleichen
				  erwarteten Bruttogewinnen unterscheiden sich trotz
				  unterschiedlicher Kapitalstrukturen nicht.
				- Eigenkapitalkosten sind eine
				  logseq.order-list-type:: number
				  lineare Funktion des Verh¨altnisses der Marktwerte von
				  Fremdkapital und Eigenkapital.
				- Die Kapitalkosten einer verschuldeten
				  logseq.order-list-type:: number
				  Unternehmung sind im Gleichgewicht konstant und
				  unabh¨angig von der Kapitalstruktur. Sie gleichen den (Eigen-)
				  Kapitalkosten einer unverschuldeten Unternehmung und der
				  erwarteten Rendite des Gesamtkapitals (zu Marktwerten) von
				  Unternehmungen in der Risikoklasse.
		- Derivate
		  deck:: Finanzierung::Derivate
			- Spotvertrag #card
			  id:: 6509da10-6d61-4be9-8e95-f6211d7fbf38
				- Abschluss- und Lieferzeitpunkt stimmen überein
			- (unbedingter)Terminvertrag #card
			  id:: 6509da46-a9fc-41ac-bc88-dc0c84044fc6
				- Vereinbarung über die zukünftige Lieferung zu festgelegten Bedingungen
				- Verpflichtung, d.h. es können Gewinne oder Verluste zum Lieferzeitpunkt auftreten
				- Basiswert (Underlying) wird zu einem späteren Zeitpunkt ausgetauscht
				- Die Partei in der Kaufposition kauft die Anlage
				- Beispiele
					- Forward #card
					  id:: 6509dbaf-76e0-419a-af3c-7fd4fdff7b11
						- außerbörslich (OTC)
						- TODO Zahlungsstrom (2.1)
						  :LOGBOOK:
						  CLOCK: [2023-09-20 Wed 09:40:29]--[2023-09-20 Wed 09:40:30] =>  00:00:01
						  CLOCK: [2023-09-20 Wed 09:40:31]
						  :END:
						- TODO Barwert
					- Future #card
					  id:: 6509dbb2-5512-46af-a977-d5ed29680e24
						- an einer Börse gehandlet
						- Clearing House ist die Gegenseite des Future Investors
						- Der Wert von Future Verträgen ist immer gleich 0
						- Weniger Anfällig  auf Kreditrisiko als Forwards
						- marked-to-market #card
						  id:: 6509f019-a98c-40da-9d54-91ff3a85a0f0
							- jeder Gewinn/Verlust wird am Ende jedes Handelstages ausgeglichen, durch ein sog. Margin-System
						- TODO Beispiel: Spekulation
						  2.1
					- Swap #card #depth-1
					  id:: 6509dbb4-a9a7-4db6-bbf3-77f71adad1ac
						- Finanzvertrag zwischen zwei Parteien zum Austausch von Verbindlichkeiten
						- Arten
							- Zins-Swap #card
							  id:: 650ae013-2b3c-4232-ac51-1036b77957bf
								- Austausch von Zinsverpflichtungen in einer einheitlichen Währung
								- Arten
									- Basis-Swap #card
									  id:: 650ae04f-fa3a-454c-98fb-a2281036bc4d
										- Vertragspartner tauschen zwei variable Zinszahlungen
										- beispielsweise 6-Monats-EURIBOR gegen 3-Monats-EURIBOR
									- Kupon-Swap #card
									  id:: 650ae052-40cf-4513-99f9-69c3713764d8
										- Vertragspartner tauschen eine variable gegen eine feste Zinsverpflichtung
										- Laufzeit i.d.R 3-5 Jahre
										- Basislevel, Swaplevel (fester Zinssatz) ist dabei frei wählbar
										- die meisten Banken bieten Kunden standardisierte Swaps an, bei denen die variable Zahlung vierteljährlich und die feste Zahlung jährlich ist
										- TODO Wert eines Kupon-Swaps #card
										  id:: 650aea1b-7a57-4ef1-b876-ebee987c253b
											- $$Swap(L) = N - N * \sum_{i=1}^T L * B(0,i) + B(0,T)$$
											  wobei 
											  |||
											  |B(0,t)| die Kurse von Nullkuponanleihen mit Nennwert 1 (normiert) und Endfälligkeit zum Zeitpunkt t|
											  | T | Laufzeit|
										- Swapyield #card (2.2)
										  id:: 650ae33c-0239-43f8-8033-a421b043065e
											- Wird das Basislevel so gewählt, dass zu Beginn keine spezielle Prämie notwendig ist, wird das Basislevel **Swapyield** genannt.
											- $$y_s = L^* = \frac{1-B(0,n)}{\sum_{i=1}^{T}B(0,i)}$$
										- Arten
											- Payer-Swap #card
											  id:: 650ae062-64c5-43bb-997e-fb7911b16c96
												- Käufer erhält variable Zinszahlung und zahlt einen festen Zinssatz
													- Beispiel:
														- Bei einem Payer-Swap mit den Daten:
														  |||
														  |Referenzzins ($r_L$)| 3-Monats EURIBOR|
														  |Laufzeit (T )| 3 Jahre|
														  |Nennwert (N)| 10 Mio.|
														  |Basislevel (L)| 2 % p. a.|
														  |Vertragsbeginn| 1.12.2019|
														  |Festzinszahlung| jährliche Zahlungen: 1.12.2020, 1.12.2021, 1.12.2022|
														  |variable Zahlung ($t_i$ )| vierteljährliche Zahlungen: 1.3.2020, ...., 1.12.2022|
														  verpflichtet sich der Halter zu jährlichen Festzinszahlungen von $L*N=200.000€$.
														  Der Halter erhält dafür vierteljährlich Zahlungen relativ zur Höhe des 3-Monats-EURIBOR des Vorzeitpunktes, also $$L*r_L*t_i = 0,02 * \text{EURIBOR} * 1/4 $$
														- Replizieren lässt sich die Auszahlung für den Halter (Emittenten) im Beispiel so:
															- Emittiere eine 3-jährige Kuponanleihe mit dem Nennwert 10 Mio., einer Kuponrate von 2%, und der Rückzahlung zum Nennwert zum selben Datum
															- Lege 10 Mio. rollierend zum 3-Monats-EURIBOR an, d. h. zu den selben Zeitpunkten werden
															  Zinszahlungen entnommen und der Nennwert von 10 Mio. erneut angelegt.
													-
											- Receiver-Swap #card
											  id:: 650ae066-ed07-40ad-b340-33f4066ff1da
												- Käufer erhält die feste Zinszahlung und leistet die variable Zinszahlung
							- Währungs-Swap
							- kombinierter Swap
			- bedingter Terminvertrag #card
			  id:: 6509db1c-c0f8-4ca3-a5b5-185aaaa2d9fe
				- Optionsvertrag
				- das **Recht** zu heute vereinbarten Bedingungen zu einem zukünftigen Zeitpunkt zu nutzen
	- Risiko und Rendite
	  deck:: Finanzierung::Risiko und Rendite
	- Hedging #card
	  id:: 650aa263-ba20-4df8-89c1-f3e9f46e2779
		- Absicherung
		- Investoren sind den Bewegungen des Basiswertes (Underlying<)
	- Portfoliotheorie und CAPM
	  deck:: Finanzierung::Portfoliotheorie und CAPM