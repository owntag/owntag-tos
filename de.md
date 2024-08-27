# Allgemeine Geschäftsbedingungen owntag.eu

Stand: 27.08.2024, Version 1.1

## Vertragspartner, Geltungsbereich

Diese Allgemeinen Geschäftsbedingungen (AGB) regeln die Vertragsbeziehungen von

owntag  
Inhaber Justus Blümer  
Gneisenaustraße 10  
20253 Hamburg  
Deutschland

(nachstehend "owntag" genannt) mit seinen Kunden.

Soweit nachstehend nur von "Kunden" die Rede ist, betrifft dies ausschließlich Unternehmer im Sinne von § 14 BGB.
owntags Angebot richtet sich ausschließlich an solche Unternehmer und owntag wird keine Geschäftsbeziehung mit Privatpersonen eingehen.

owntags Angebot richtet sich ausschließlich an Kunden mit Geschäftssitz innerhalb der Europäischen Union.

Von diesen AGB insgesamt oder teilweise abweichende Geschäftsbedingungen des Kunden werden nicht Vertragsbestandteil, soweit keine Zustimmung von owntag in Textform vorliegt. Die AGB von owntag gelten auch dann ausschließlich, wenn in Kenntnis entgegenstehender Geschäftsbedingungen des Kunden durch owntag Leistungen vorbehaltlos erbracht werden.

# Vertragsgegenstand

## Allgemeines

Die Leistungen im Einzelnen werden nach Art und Umfang auf der Webseite von owntag beschrieben, soweit Verträge nicht durch Individualkommunikation zustande kommen.
Für den Kunden ist die jeweilige Leistungsbeschreibung im Zeitpunkt der Abgabe seiner Bestellung maßgeblich. Diese Leistungsbeschreibung geht den nachstehend beschriebenen Vertragsinhalten im Falle von Widersprüchlichkeiten vor.

## Begriffsbestimmungen

**Nutzer**: Der Endnutzer, dessen Daten ("Nutzerdaten") vom Kunden mit Hilfe der von owntag im Auftrag des Kunden betriebenen Software verarbeitet werden.

**Kunde**: Der Vertragspartner von owntag, der owntag mit der Erbringung der gebuchten Leistung beauftragt hat.

**Setup**: Eine durch owntag aus dem von Google Inc. veröffentlichten SGTM Docker Image bereitgestellte Installation des Google Tag Manager Server Side Containers, die der Kunde nutzt.

## Betrieb des Google Tag Manager Server Side Container

owntag betreibt für seine Kunden die Software "Google Tag Manager Server Side Container". Dabei handelt es sich um ein sogenanntes Tag Management System, das zur Verwaltung, Organisation und Steuerung der Erhebung digitaler Daten verwendet wird, mit besonderem Fokus auf digitale Analyse wie z. B. Webanalyse oder Marketing-Technologie.  
Im Folgenden wird "Google Tag Manager Server Side Container" als "[der] SGTM" bezeichnet.

Der SGTM ist eine von der Firma Google Inc. [kostenfrei und öffentlich bereitgestellte](https://gcr.io/cloud-tagging-10302018/gtm-cloud-image) Software, die nicht von owntag entwickelt und auch nicht modifiziert wird.
owntag unterhält keine spezielle Geschäftsbeziehung zu Google Inc. und tritt ausdrücklich nicht als Anbieter der Software auf, sondern lediglich als technischer Dienstleister für den Betrieb im Auftrag des Kunden.  
owntags Kunde hat keinen Anspruch auf eine eine bestimmte Funktionsweise oder auch nur auf korrekte Funktionsweise des Dienstes, sofern sich die tatsächlich beobachtete Funktion aus der Original-Software des SGTM ableitet.

owntag stellt im Auftrag des Kunden Serverressourcen bereit, nutzt diese für den Betrieb einer Instanz des SGTM und stellt diese dann seinen Kunden zur Verfügung.  
Der Kunde nutzt dann den SGTM, um über das HTTP Protokoll Daten entgegenzunehmen, in eigener Verantwortung mit Hilfe des SGTM zu verarbeiten und an den endgültigen Datenempfänger weiterzuleiten.

Der Kunde erhält das nicht ausschließliche, auf die Laufzeit des Vertrages zeitlich beschränkte Recht, die mit Nutzung der Webserver verbundenen Softwarefunktionalitäten gemäß diesen AGB zu nutzen.  
Darüber hinaus gehende Rechte erhält der Kunde nicht.  

Der Kunde nimmt zur Kenntnis, dass der SGTM ggf. unter Lizenzbedingungen von Google Inc. steht, die der Kunde selbst zu beachten hat (siehe z. B. https://www.google.com/analytics/terms/tag-manager/). owntags Hinweis auf solche Lizenzbedingungen entbindet den Kunden nicht von der Pflicht, sich selbst über diese Lizenzbedingungen zu informieren.  
owntag übernimmt keine Haftung für Schäden, die aus der Verletzung solcher Lizenzbedingungen Dritter entstehen.

Die Verantwortung für die stattfindenden Datenverarbeitung im SGTM liegt ausschließlich beim Kunden. Regelmäßig hat owntag sogar, obwohl es die Serverinfrastruktur zur Verfügung stellt, technisch keinen direkten Zugriff auf diese Verarbeitung.

## Logging

owntag betreibt einen Dienst zur Organisation und Weiterleitung von Daten, nicht zur Speicherung von Daten. Auch wenn die Speicherung von Daten über den SGTM gesteuert werden kann, findet diese Speicherung nicht _bei owntag_ statt.

Hiervon ausgenommen: owntag wird eingehende Daten temporär speichern, um Fehler im Betrieb zu beobachten, zu identifizieren und zu beheben ("Logging").
Das Logging, sowohl für owntag als auch für den Kunden, findet für einen Zeitraum von maximal 30 Tagen statt. Weder der Kunde noch andere Parteien haben einen _Anspruch_ auf das Logging, es handelt sich um eine reine Kulanzleistung, die nicht Bestandteil des Vertrags ist.

### Logging für den Kunden

Neben dem Logging für owntag-interne Zwecke kann owntag als Zusatzleistung die eingehenden Requests für seine Kunden loggen, um die Logeinträge dem Kunden anschließend zur Verfügung zu stellen.
Der Kunde kann diese Logs seinerseits nutzen, um beispielsweise seine Implementierungen im SGTM auf korrekte Funktionsweise zu überprüfen.

## Garantien durch owntag

owntag garantiert:

1. owntags Angebot richtet sich ausschließlich an Kunden mit Geschäftssitz innerhalb der Europäischen Union. Das heißt auch: owntag wird keine Kunden aus den USA oder andere Länder [ohne angemessenes Datenschutzniveau](https://dsgvo-gesetz.de/themen/drittland/) zulassen.

2. Die Serverressourcen, die owntag nutzt, um im Rahmen des Vertrags die vom Kunden bestellten SGTM Instanzen zu betreiben, wird owntag entweder selbst bereitstellen oder ausschließlich von solchen Unternehmen beziehen, die ihren Sitz in der Europäischen Union haben.

3. Die Serverhardware
    - mit der Nutzerdaten von owntag entgegengenommen werden
    - an die SGTM Instanz des Kunden weitergeleitet werden
    - auf der die SGTM Instanz des Kunden betrieben wird
    - auf der owntags internes Logging Daten gespeichert werden, die möglicherweise Nutzerdaten enthalten
      
    befindet sich physisch in der Europäischen Union und wird von einem Unternehmen betrieben, das seinerseits seinen Hauptsitz in der Europäischen Union hat.

4. owntag wird die eingehenden Daten zu keinem Zeitpunkt für andere Zwecke nutzen als den vertraglich vereinbarten Betrieb des SGTM.

Hinweis:

Pauschale Versprechen, Datenerhebung mit owntag sei grundsätzlich "datenschutzkonform" oder automatisch "DSGVO-kompatibel" wären unseriös, denn owntag stellt erwartbar immer nur einen Teil moderner digitaler Datenerhebung dar.  
Ein datenschutzrechtlich einwandfreie Datenerhebung erfordert aber konforme Prozesse in 100% der Prozesskette, auf die owntag keinen Einfluss hat und die in jedem Unternehmen unterschiedlich sind.  

owntag kann und wird daher zu keinem Zeitpunkt solche pauschalen Versprechen abgeben.

## Verantwortung des Kunden

Alle Nutzerdaten, die Kunden an einen durch owntag betriebenen SGTM senden, bleiben stets in der Verantwortung des Kunden.

## Support

Gegenstand der Anwenderunterstützung des Kunden ("Support") sind sämtliche Beratungs- und Unterstützungsleistungen in deutscher Sprache mit Ausnahme von Planungsarbeiten und Überwachungsleistungen.
Der Kunde hat keinen Anspruch auf Support. Jeglicher erbrachter Support ist eine reine Kulanzleistung und begründet keinen Anspruch auf weitere Erbringung von Support.

Der Kunde programmiert, wartet, betreibt die Analyse- und Marketingtechnologie-Implementierungen in seinen Setups auf den durch owntag vertragsgemäß bereitgestellten Serverressourcen in alleiniger Verantwortung.

# Zustandekommen des Vertrags

Der Vertrag kommt im elektronischen Geschäftsverkehr zu den über die Website von owntag angebotenen Server-Dienstleistungen dadurch zustande, dass der Kunde die dort angebotenen Leistungen von owntag in einem auf der Webseite durch owntag bereit gehaltenen System bestellt und owntag die Bestellung des Kunden annimmt und Setup bereitstellt.

Der Kunde ist an seine Bestellung (verbindliches Angebot) von Leistungen nach Ziffer 3.1 für die Dauer von fünf Tagen gebunden.

owntag behält sich jederzeit ausdrücklich vor, eine Bestellung aus beliebigem Grund im Einzelfall nicht anzunehmen.

Im Übrigen sind Angebote von owntag, auch Angebote auf der Webseite, stets freibleibend.

# Pflichten und Obliegenheiten des Kunden

Der Kunde ist verpflichtet, die für seine Bestellung erforderlichen Daten vollständig und wahrheitsgemäß anzugeben.
Verstößt der Kunde gegen die Pflicht zur wahrheitsgemäßen Erklärung, ist owntag berechtigt, das Vertragsverhältnis mit sofortiger Wirkung zu kündigen.

Veränderungen hinsichtlich der durch den Kunden erklärten Daten wird der Kunde unverzüglich berichtigen bzw. aktualisieren. Der Kunde ist verpflichtet, seine gegenüber owntag in der Bestellmaske angegebene E-Mail-Adresse aktuell zu halten und regelmäßig E-Mail-Eingänge von owntag abzurufen.

Nutzer werden ihre Benutzernamen und Kennwort bzw. vergleichbare Mechanismen wie Single Sign On Zugänge wie z. B. über Google, die den Zugang zur owntag Administrationsoberfläche sichern vor dem unbefugten Zugriff durch Dritte geschützt aufzubewahren.
Passwörter müssen zur Sicherheit in regelmäßigen Abständen geändert werden. In digitalen Medien darf der Kunde Benutzernamen und Kennwörter nur in verschlüsselter Form speichern.

Bei mehrmaliger falscher Eingabe eines Kennwortes kann dies zum Schutze des Kunden zu einer Sperrung der Nutzungsmöglichkeiten, für die das Kennwort gilt, führen.

Der Kunde ist verpflichtet, mengenmäßig begrenzte Inklusivleistungen nicht zu überschreiten, sofern eine Überschreitung vertraglich nicht ausdrücklich vereinbart ist. 
Ist eine solche mögliche Überschreitung vereinbart, richtet sich die Abrechnung des Trafficvolumens über die Inklusivleistung hinaus nach der vertraglichen Vereinbarung.

Der Kunde hat zu gewährleisten, dass er den ihm zur Verfügung gestellten Softwarezugang so einsetzt, dass die Infrastruktur oder Daten anderer Kunden von owntag, die Serverstabilität, Serverperformance oder Serververfügbarkeit nicht entgegen der vertraglich vorausgesetzten Verwendung beeinträchtigt werden.

Informationen von owntag an den Kunden, welche den Vertragsabschluss, die Vertragsabwicklung, insbesondere die Rechnungstellung sowie das Mahnwesen betreffen, einschließlich die Vertragsbeendigung (Kündigung), erfolgen in aller Regel in Textform (d.h. per E-Mail). Lediglich in Ausnahmefällen bzw. in Fällen gesetzlicher Verpflichtung erstellt owntag Texte in Schriftform und richtet diese an die ihm genannte Adresse des Kunden.

## Verantwortung des Kunden

Für die sämtliche Inhalte, die der Kunde auf dem durch owntag bereitgestellten Webserver abrufbar hält oder speichert (Informationen, d.h. Daten, Grafiken, Bilder, Musikstücke, Videos oder sonstige Informationen, welche über die durch owntag bereitgestellten Technologien abrufbar sind oder verbreitet), ist der Kunde nach den allgemeinen Gesetzen verantwortlich. Entsprechendes gilt für Nutzungshandlungen auf den Webservern, die der Kunde veranlasst hat.

Der Kunde hat für den Fall, dass er mit seiner Nutzung von owntag seinerseits einen Telemediendienst darstellt, weiterhin die Informationspflichten zu erfüllen, welche die Gesetze an einen Anbieter von elektronischen Informations- und Kommunikationsdiensten und Telekommunikationsdiensten stellt. Er hat die Anforderungen der Datenschutzgesetze zu beachten, soweit er selbst personenbezogene Daten verarbeitet bzw. verarbeiten lässt.

## Verbotenes

Die Leistungen von owntag dürfen durch den Kunden nicht genutzt werden, um an Dritte unaufgefordert E-Mails zu Werbezwecken (Mail-Spamming) oder den Versand von Nachrichten zu Werbezwecken (News-Spamming) zu ermöglichen, um an Dritte bedrohende oder belästigende Nachrichten zu versenden oder den unbefugten Abruf von Informationen zu ermöglichen bzw. unbefugt in Datennetze einzudringen.

Dem Kunden ist die Untervermietung von Leistungen nicht gestattet, es sei denn er ist ein von owntag autorisierter Reseller.

Der Kunde ist verpflichtet, seine Systeme, Skripte, Programme und sonstige Dateien und Daten auf den Servern von owntag so einzurichten, dass weder die Sicherheit, die Integrität noch die Verfügbarkeit der Netze, Server und Software, welche owntag zur Erbringung ihrer Dienste einsetzt, beeinträchtigt wird.  
owntag ist berechtigt, den Zugang des Kunden bzw. Dritter zu sperren bzw. zu reglementieren, wenn seine Netze, Server und Software abweichend vom Regelbetriebsverhalten agieren oder reagieren und dadurch die Sicherheit, die Integrität oder die Verfügbarkeit der Systeme von owntag beeinträchtigt wird.  
Der Kunde ist nicht berechtigt, owntags Leistungen im Rahmen illegaler Aktivitäten zu verwenden.

Darüber hinaus verbotene Nutzungsarten bzw. Nutzungshandlungen werden ggf. auf der Webseite von owntag bekannt gemacht.

Während der vorübergehenden Sperrung im Sinne der vorstehenden Absätze behält owntag den Anspruch auf die vereinbarte Vergütung.

## Verfügbarkeit

Der Kunde kann eine mittlere Zugänglichkeit der von owntag bereit gehaltenen Server und Datenwege in Höhe von 99,0% auf das Jahr erwarten.  
Hiervon ausgenommen sind Zeiten, in denen die Server aufgrund von technischen oder sonstigen Problemen, die nicht im Einflussbereich von owntag liegen (höhere Gewalt, Verschulden Dritter, etc.) nicht zu erreichen ist.

owntag kann den Zugang zu den Leistungen beschränken, sofern die Sicherheit des Netzbetriebes, die Aufrechterhaltung der Netzintegrität, insbesondere die Vermeidung schwerwiegender Störungen des Netzes, der Software oder gespeicherter Daten dies erfordern.

## Zahlungsbedingungen

Die Leistungen von owntag werden monatlich jeweils am Monatsende abgerechnet.  
Nur anteilig genutzte Monate werden tagesgenau anteilig berechnet.

Der Kunde kann per automatischem Einzug via SEPA Lastschrift oder per Kreditkarte über den Zahlungsdienstleister Stripe bezahlen.  
Andere Zahlungsarten sind nicht vorgesehen, sofern nicht ausdrücklich anders vereinbart.

Der Kunde erhält eine Rechnung bzw. Berechnung der vereinbarten und fälligen Vergütung in elektronischer Form als PDF-Dokument. Sie wird nach jedem abgelaufenen Kalendermonat an die bei owntag hinterlegte E-Mail-Adresse des abrechnungsverantwortlichen Nutzers gesendet. Ein Anspruch des Kunden auf eine digital signierte Rechnung (§ 14 Abs. 3 UStG) besteht nicht.

Im Falle des Verzugs des Kunden mit seinen fälligen Zahlungsverpflichtungen ist owntag berechtigt, den Zugang des Kunden auf die von owntag bereitgestellten Ressourcen einzuschränken. owntag wird den Kunden auf diese Folge seines Zahlungsverzugs in einer Mahnung hinweisen, welche mittels E-Mail an die vom Kunden zuletzt genannte E-Mail-Adresse versandt wird. Ist die Mahnung per E-Mail nicht zustellbar, ist owntag berechtigt, den Zugang sofort vorläufig zu sperren. Im Verzug des Kunden besteht die Zahlungspflicht des Kunden trotz gesperrtem Zugang fort.

Änderungen der Preise werden dem Kunden mindestens sechs Wochen vor ihrem geplanten Wirksamwerden in Textform mitgeteilt. Dem Kunden steht bei einer Preiserhöhung das Recht zu, den Vertrag ohne Einhaltung einer Kündigungsfrist zum Zeitpunkt des Wirksamwerdens der Preisanpassung in Textform zu kündigen. Hierauf wird owntag den Kunden in der Änderungs- mitteilung besonders hinweisen. Im Übrigen bleibt § 315 BGB unberührt.

# Sperrung

owntag wird von der technischen Möglichkeit des Sperrens des Zuganges des Kunden auf die bereit gestellten Dienste nur in erforderlichen Ausnahmefällen Gebrauch machen und stets die berechtigten Belange des Kunden berücksichtigen. Nimmt owntag eine Sperrung vor, so ist owntag ggf. zur Sperrung sämtlicher vertragsgegenständlichen Dienste und Leistungen berechtigt. Die Wahl der Sperrmaßnahme liegt insoweit im Ermessen von owntag.

Durch eine berechtigte Sperrung von owntag wird der Kunde nicht von seiner Verpflichtung entbunden, die vereinbarten Entgelte zu entrichten.

Erhält owntag Abmahnungen, Mahnungen oder Ermahnungen von dritter Seite, welche die glaubhafte Behauptung von Rechtsverletzungen enthalten, so ist owntag berechtigt, ohne weitere Rechtsprüfung den Zugang Dritter zu den beanstandeten Informationen, von welcher die Verletzung ausgeht, einstweilen zu sperren, wenn nicht der Kunde gegenüber owntag unverzüglich nachweist, dass eine Rechtsverletzung nicht vorliegt oder owntag durch den Kunden – ggf. mit Leistung einer Sicherheit – von den Folgen einer Inanspruchnahme durch Dritte freigestellt wird. Zu einer Rechtsberatung gegenüber dem Kunden ist owntag nicht verpflichtet.

owntag genügt ihren Mitteilungspflichten zur Vorbereitung bzw. Abwehr und Durchführung der Sperre, wenn sie die jeweiligen Mitteilungen hierüber per E-Mail an die vom Kunden angegebene E-Mail-Adresse sendet. Es ist Sache des Kunden, die Abrufbarkeit der von ihm benannten E-Mail-Adresse zu gewährleisten.

owntag kann die Aufhebung der Sperrung davon abhängig machen, dass der Kunde den rechtswidrigen Zustand nachweislich beseitigt und zum Ausschluss einer Wiederholungsgefahr eine vertragsstrafenbewehrte Unterlassungserklärung gegenüber owntag abgegeben hat sowie für die Zahlung einer hieraus etwaig sich zukünftig ergebenden Vertragsstrafe Sicherheit geleistet hat. Die Höhe der Sicherheit entspricht insoweit der Höhe zu erwartender Kosten von owntag für den Fall einer Inanspruchnahme von dritter Seite. Die Höhe des Vertragsstrafeversprechens orientiert sich dabei an der Bedeutung des Verstoßes.

Soweit owntag von Dritten oder von staatlichen Stellen wegen eines Verhaltens in Anspruch genommen wird, welches owntag zur Sperrung berechtigt, verpflichtet sich der Kunde, den Anbieter von allen Ansprüchen freizustellen und diejenigen Kosten zu tragen, die durch die Inanspruchnahme oder Beseitigung des rechtswidrigen Zustandes entstanden sind. Dies umfasst insbesondere auch die erforderlichen Rechtsverteidigungskosten des Anbieters.

## Pflichten zur Beendigung des Vertrags

Zum Tag der Beendigung des Vertrags ist der Kunde zur Löschung der von ihm vorgenommenen Implementierungen und Konfigurationen verpflichtet.

Für einen rechtzeitigen Export und die anschließende geeignete Aufbewahrung seiner Daten auf eigenen Speichermedien hat der Kunde selbst Sorge zu tragen.

## Aufrechnung durch den Kunden, Zurückbehaltungsrecht

Mit Forderungen von owntag kann der Kunde nur aufrechnen, soweit diese Forderungen unwidersprochen oder rechtskräftig festgestellt sind. Die Geltendmachung eines Zurückbehaltungsrechts steht dem Kunden nur wegen Gegenansprüchen zu, die aus dem Vertragsverhältnis mit owntag resultieren.

## Haftung

Eine Haftung von owntag – gleich aus welchem Rechtsgrund – besteht ausschließlich im Rahmen der nachfolgenden Bestimmungen.

Unbeschränkte Haftung: owntag haftet für Vorsatz und grobe Fahrlässigkeit. Für leichte Fahrlässigkeit haftet owntag nach Maßgabe des Produkthaftungsgesetzes aufgrund des Telekommunikationsgesetzes sowie bei Schäden aus der Verletzung des Lebens, des Körpers oder der Gesundheit von Personen.

Haftungsbeschränkung: owntag haftet bei leichter Fahrlässigkeit im Übrigen nur bei der Verletzung einer wesentlichen Vertragspflicht, deren Erfüllung die ordnungsgemäße Durchführung des Vertrags überhaupt erst ermöglicht und auf deren Einhaltung der Vertragspartner regelmäßig vertrauen darf (Kardinalpflicht). Diese Haftungsbeschränkung gilt auch zugunsten der Erfüllungsgehilfen von owntag.

Die verschuldensunabhängige Haftung von owntag auf Schadenersatz für bei Vertragsschluss vorhandene Mängel (§ 536a BGB) ist ausgeschlossen.

## Vertragslaufzeit, Kündigung, Beendigung des Vertrags

Wenn nicht anderes vereinbart ist, ist der Vertrag auf unbestimmte Zeit abgeschlossen.

Sofern nicht ausdrücklich anders vereinbart, ist der Vertrag sowohl durch owntag als auch durch den Kunden monatlich mit Ablauf des Folgemonats kündbar.

Die ordentliche Kündigung des Vertrags durch den Kunden kann nur über die owntag Administrationsoberfläche – online – geschehen, zu welcher owntag dem Kunden jederzeit Zugang zu gewähren hat.

Die nach Maßgabe der vorherigen Bestimmung erfolgte Online-Kündigung hat die hiernach umgehende Löschung sämtlicher von owntag gespeicherter Daten des Kunden auf dem für ihn bereit gestellten Speicherplatz zur Folge.

### Außerordentliche Kündigung

Den Parteien bleibt das Recht zur außerordentlichen Kündigung des Vertrages zu Hosting- oder Domain-Services vorbehalten. Für die außerordentliche Kündigung ist mindestens Textform (z.B. durch E-Mail) vereinbart. Eine außerordentliche Kündigung aus wichtigem Grund liegt insbesondere dann vor,

wenn der Kunde mit einer fälligen Zahlung länger als 1 Monat in Verzug ist, oder

der Kunde trotz Abmahnung schuldhaft gegen eine vertragliche Pflicht verstößt oder

der Kunde nicht innerhalb angemessener Frist eine Vertrags- oder Rechtsverletzung beseitigt, insbesondere der Kunde über sein Setup rechtswidrige Informationen zum Abruf bzw. zur Nutzung zur Verfügung stellt, obwohl er durch Dritte oder durch owntag auf diesen Umstand hingewiesen worden ist.

Eine Abmahnung ist entbehrlich, wenn es sich um eine Pflichtverletzung handelt, die eine Fortsetzung des Vertrages für owntag unzumutbar macht, insbesondere weil owntag wegen dieser Pflichtverletzung auch ggü. Dritten haftbar wäre.

Soweit nicht der gesamte Vertrag gekündigt wird, sondern lediglich die Kündigung eines oder mehrerer, aber nicht aller Setups erfolgt, besteht der Vertrag im Übrigen fort.

# Datenschutz

Über die Erhebung, Verarbeitung und Nutzung von personenbezogenen Daten unterrichtet owntag den Kunden gesondert, insbesondere über die Datenschutzerklärung und den Vertrag zur Auftragsdatenvereinbarung.

# Anwendbares Recht, Gerichtsstand, Unwirksamkeit

Für die von owntag auf der Grundlage dieser AGB abgeschlossenen Verträge und für die hieraus folgenden Ansprüche, gleich welcher Art, gilt ausschließlich das Recht der Bundesrepublik Deutschland. Für den Fall des Abschlusses von Verträgen mit Verbrauchern, die ihren Sitz nicht in Deutschland haben, bleiben die zwingenden verbraucherschützenden Vorschriften des Rechts der Verbraucher in ihrem jeweiligen Heimatstaat, welches für ihren Sitz gilt, von Satz 1 unberührt.

Gerichtsstand für sämtliche Ansprüche aus den Vertragsbeziehungen zwischen den Vertragsparteien sich ergebenden Streitigkeiten, insbesondere über das Zustandekommen, die Abwicklung oder die Beendigung des Vertrages ist - soweit der Kunde Vollkaufmann, juristische Person des öffentlichen Rechts oder öffentlich-rechtliches Sondervermögen ist – der Sitz von owntag.

Sollten einzelne Bestimmungen dieser AGB ganz oder teilweise unwirksam sein oder werden, so wird hierdurch die Gültigkeit der übrigen Bestimmungen nicht berührt.

# Pflichtinformationen

Soweit sich owntag zum Zwecke des Vertragsabschlusses der Telemedien bedient (Vertrag im elektronischen Geschäftsverkehr), ist owntag zur Erteilung von Informationen verpflichtet. Dies betrifft sowohl Verbraucher-Kunden, als auch Verbraucher- und Unternehmerkunden.

## Identität des Unternehmens

Vertragspartner des Kunden wird:

owntag  
Inhaber Justus Blümer  
Gneisenaustraße 10  
20253 Hamburg  
Deutschland

Ust-ID: DE316044987

Vertreter in Mitgliedsstaaten, in denen der Verbraucher seinen Wohnsitz hat, sind nicht bestellt. Der Telemediendienst von owntag bedarf keiner behördlichen Zulassung.

## Weitere Informationen

Der elektronische Bestellvorgang auf der Webseite enthält für alle Kunden angemessene, wirksame und zugängliche technische Mittel, mit deren Hilfe der Kunde Eingabefehler vor Abgabe seiner Bestellung erkennen und berichtigen kann.

## Preisangaben

Die auf der Webseite angezeigten Preise sind Nettopreise, exklusive der Mehrwertsteuer. Die Mehrwertsteuer wird auf der Rechnung separat ausgewiesen.