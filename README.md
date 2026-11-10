# Effektivpreis-Index 🐸

Offene Marktdaten von [froschtarife.de](https://froschtarife.de/) zu Handytarifen mit Smartphone in Deutschland.

**Was kostet ein Handytarif wirklich, wenn du das mitbestellte Handy versiegelt verkaufst?** Diese Zahl nennen wir Effektivpreis. Wir rechnen sie für jedes Angebot in unserem Vergleich aus und fassen sie hier als Median je Netz zusammen. Dazu kommt, wie weit die Ankaufportale für dasselbe Neugerät auseinanderliegen.

- Index mit Verlauf und Methode: <https://froschtarife.de/effektivpreis-index/>
- Ankaufportale im Vergleich: <https://froschtarife.de/verkaufen.php#vergleich>

## Dateien

| Datei | Inhalt |
|---|---|
| `daten/index-netze_JJJJ-MM-TT.csv` | Median-Effektivpreis und Median-Grundpreis je Netz (o2, Telekom, Vodafone, alle) an einem Stichtag, mit Anzahl der Angebote |
| `daten/ankauf-unterschiede_JJJJ-MM-TT.csv` | Wie weit höchstes und niedrigstes Gebot der Ankaufportale (ZOXS, Clevertronic, WIRKAUFENS) für dasselbe versiegelte Neugerät auseinanderliegen: Kennzahlen und die zehn größten Unterschiede |

Trennzeichen ist das Semikolon, Beträge in Euro mit Punkt als Dezimalzeichen, Kodierung UTF-8. Ab 14.11.2026 kommt der Tagesverlauf des Index als eigene Datei dazu.

## So rechnen wir

**Effektivpreis** = (Grundpreis aller 24 Monate + Gerät + Anschluss + Versand + Einlösekosten − eingerechnete Boni − Ankaufspreis) ÷ 24

- Grundlage sind alle Angebote mit frisch geprüftem Preis am Stichtag aus den angeschlossenen Shops; je Gerät und Tarif zählt ein Angebot.
- Young- und GigaKombi-Tarife sind nicht dabei, damit die Werte ohne besondere Voraussetzungen gelten.
- Der Ankaufspreis ist das Gebot eines Ankaufportals für das Neugerät im Zustand „Neu“, originalverpackt.
- Der Effektivpreis ist eine Rechengröße. Abgebucht wird jeden Monat der volle Grundpreis.

**Ankauf-Unterschiede:** Je Handy (Marke, Modell, Speicher) und Portal zählt das höchste Gebot für Neuware über alle Farben. Gezählt werden nur Handys mit mindestens zwei Portalen, deren Preise höchstens 24 Stunden auseinander und höchstens 48 Stunden alt sind. Die Datei enthält nur Unterschiede und Zählungen, keine einzelnen Portal-Preise.

Die Daten zeigen die Angebote unserer Partner-Shops, nicht den ganzen Markt. Preise ändern sich laufend; maßgeblich ist immer, was Shop und Portal beim Abschluss anzeigen.

## Nutzung

Die Daten stehen unter [CC BY 4.0](LICENSE). Du darfst sie mit Quellenangabe frei verwenden, zum Beispiel so:

> Quelle: froschtarife.de, Effektivpreis-Index (Stand TT.MM.JJJJ)

Bitte verlinke dabei <https://froschtarife.de/effektivpreis-index/>.

## Transparenz

froschtarife.de finanziert sich über Partnerprovisionen von Shops und Ankaufportalen. Auf die Rechnung und die Reihenfolge hat das keinen Einfluss. Wie das genau läuft: <https://froschtarife.de/ratgeber/so-verdienen-wir-geld/>. Kontakt und Anbieter: <https://froschtarife.de/impressum/>.

Quakige Grüße vom Froschteich 🐸
