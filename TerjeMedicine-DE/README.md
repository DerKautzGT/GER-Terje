TerjeMedicine

Medizin-Overhaul-Mod für DayZ.

![TerjeMedicine](../../logos/TerjeMedicine.jpg)


## BESCHREIBUNG

Dieser Mod bringt ein tieferes und realistischeres Gesundheitssystem ins Spiel und verstärkt die Immersion in die Gefahren des Überlebenskampfs in den weiten Landschaften von DayZ. Jede Krankheit und jede Verletzung durchläuft nun verschiedene Stadien mit jeweils eigenen Symptomen und Behandlungsmethoden. Entdecke und meistere neue Spielmechaniken, um deine Gesundheit zu erhalten und den Gefahren zu entgehen, die an jeder Ecke lauern. Jedes Symptom und jede Krankheit erfordert eine eigene Behandlung. Der Mod bietet eine große Auswahl an Medikamenten, Werkzeugen und Diagnosemethoden – vom einfachen Verband bis hin zu komplexen chirurgischen Eingriffen. **Stelle deine Überlebensfähigkeiten auf einem neuen Level auf die Probe. Behalte den Zustand deines Charakters im Blick, damit Krankheiten und Infektionen dich nicht in die Knie zwingen!**

## KOMPONENTEN

Im Mod enthaltene Mechaniken:

1. **PROPHYLAXE UND BEHANDLUNG**
   + <img src="../../images/tablets.png" width="24" alt="Medikamente"> [Medikamente](#-medikamente)
   + <img src="../../images/vaccine.png" width="24" alt="Impfstoffe"> [Impfstoffe](#-impfstoffe)
   + <img src="../../images/desinfection.png" width="24" alt="Desinfektion"> [Desinfektion](#-desinfektion)

2. **KÖRPERLICHER ZUSTAND**
   + <img src="../../images/hematoma.png" width="24" alt="Hämatome"> [Hämatome](#-hämatome)
   + <img src="../../images/bullet.png" width="24" alt="Schusswunden"> [Schusswunden](#innere-organe-schuss-und-stichwunden)
   + <img src="../../images/cut3.png" width="24" alt="Stichwunden"> [Stichwunden](#innere-organe-schuss-und-stichwunden)
   + <img src="../../images/organs.png" width="24" alt="Verletzung innerer Organe"> [Verletzung innerer Organe](#innere-organe-schuss-und-stichwunden)
   + <img src="../../images/cut2.png" width="24" alt="Chirurgische Nähte"> [Chirurgische Nähte](#-chirurgische-nähte)
   + <img src="../../images/brain.png" width="24" alt="Gehirnerschütterung"> [Gehirnerschütterung](#-gehirnerschütterung)
   + <img src="../../images/blood3.png" width="24" alt="Hämostase"> [Hämostase](#-hämostase-blutungsrate)
   + <img src="../../images/blood4.png" width="24" alt="Hämatopoese"> [Hämatopoese](#-hämatopoese-blutregeneration)

3. **INFEKTIONEN UND KRANKHEITEN**
   + <img src="../../images/influenza.png" width="24" alt="Erkältung"> [Erkältung](#-erkältung--lungenentzündung)
   + <img src="../../images/poisoning.png" width="24" alt="Lebensmittelvergiftung"> [Lebensmittelvergiftung](#-lebensmittelvergiftung)
   + <img src="../../images/biohazard.png" width="24" alt="Chemische Vergiftung"> [Chemische Vergiftung](#-chemische-vergiftung)
   + <img src="../../images/virusz.png" width="24" alt="Zombie-Virus"> [Zombie-Virus](#-zombie-virus)
   + <img src="../../images/blood2.png" width="24" alt="Sepsis"> [Sepsis](#-sepsis)
   + <img src="../../images/virus.png" width="24" alt="Tollwut"> [Tollwut](#-tollwut)

4. **SYMPTOME**
   + <img src="../../images/pain.png" width="24" alt="Schmerzen"> [Schmerzen](#-schmerzen)
   + <img src="../../images/overdose.png" width="24" alt="Überdosis"> [Überdosis](#-überdosis)

5. **EMOTIONALE ZUSTÄNDE**
   + <img src="../../images/dream.png" width="24" alt="Schlaf"> [Schlaf](#-schlaf)
   + <img src="../../images/mental.png" width="24" alt="Psychische Gesundheit"> [Psychische Gesundheit](#-psychische-gesundheit)

6. **ZONEN**
   + <img src="../../images/mental.png" width="24" alt="Psionische Zonen"> [Psionische Zonen](#-psionische-zone)

# PROPHYLAXE UND BEHANDLUNG

## ![Medikamente](../../images/tablets.png) MEDIKAMENTE

>Medikamente werden in drei Kategorien unterteilt: Tabletten, Ampullen und Injektoren. Tabletten werden in der Regel im Frühstadium einer Krankheit und zur Vorbeugung eingesetzt. Jede Packung enthält zehn Tabletten, und Packungen derselben Sorte lassen sich zusammenführen. Ampullen enthalten starke Medikamente zur Behandlung komplexer Erkrankungen oder von Krankheiten im mittleren bis schweren Stadium; zur Verabreichung wird eine Spritze benötigt. Nach jeder Injektion ist die Spritze verunreinigt und muss mit Alkohol desinfiziert oder in einem Topf mit Wasser über dem Feuer abgekocht werden. Injektoren funktionieren ähnlich wie Ampullen, benötigen aber keine Spritze, da alle Injektoren Einwegartikel sind.

## ![Impfstoffe](../../images/vaccine.png) IMPFSTOFFE

>Impfstoffe schützen vor gefährlichen Krankheiten und senken das Infektionsrisiko erheblich. Nach der Anwendung baut ein Impfstoff Immunität gegen bestimmte Infektionen auf, sodass sich der Charakter in verseuchten Umgebungen vor Erkrankungen schützen kann. Für optimalen Schutz solltest du Impfstoffe frühzeitig verabreichen, um die Immunität deines Charakters zu stärken, und regelmäßig prüfen, ob eine Auffrischungsimpfung nötig ist.

| Name       | Gegenstand                | Phase    | Form und Verpackung | Dauer (s) | Überdosis |
|:----------:|:-------------------------:|:--------:|:-------------------:|:---------:|:---------:|
| Vaxicam    | TerjeAmpouleVaxicam       | Impfung  | Ampulle             | 14400     | 0.8       |
| Zerivax    | TerjeAmpouleZerivax       | Impfung  | Ampulle             | 7200      | 1.5       |
| Rabivax    | TerjeAmpouleRabivax       | Impfung  | Ampulle             | 14400     | 1.3       |

Parameter zum [Erstellen eigener Gegenstände](../../en/Modding/README.md#1-based-on-item)
```cs
    medInfluenzaVacineTimeSec  = 14400; // Impfstoff gegen Erkältung
    medZVirusVacineTimeSec     = 7200;  // Impfstoff gegen Z-Virus
    medRabiesVacineTimeSec     = 14400; // Impfstoff gegen Tollwut
```

## ![Desinfektion](../../images/desinfection.png) DESINFEKTION

>Desinfektion ist ein zwingend notwendiges Verfahren, um die Sterilität zu wahren und Wundinfektionen vorzubeugen. Verschmutzte medizinische Gegenstände müssen vor der Benutzung gründlich desinfiziert werden, um das Infektionsrisiko zu minimieren. Vor jeder medizinischen Behandlung oder Operation sollten außerdem die Hände desinfiziert werden – besonders unter Feldbedingungen, wo das Infektionsrisiko höher ist. Eine ordnungsgemäße Desinfektion ist entscheidend für eine erfolgreiche Behandlung und für die Gesundheit in extremen Umgebungen.

| Name                      | Gegenstand           | Phase        |
|:-------------------------:|:--------------------:|:------------:|
| Alkoholtinktur            | DisinfectantAlcohol  | Desinfektion |
| Desinfektionsspray        | DisinfectantSpray    | Desinfektion |

# KÖRPERLICHER ZUSTAND

## ![Hämatome](../../images/hematoma.png) HÄMATOME

>Hämatome können entstehen, wenn dich ein Zombie trifft oder du mit stumpfen Waffen geschlagen wirst. Bei zahlreichen Hämatomen beginnt deine Gesundheit zu sinken. Sie heilen zwar mit der Zeit von selbst, doch Salben beschleunigen den Heilungsprozess.

| Name        | Gegenstand            | Form und Verpackung | Dauer (s) | Überdosis |
|:-----------:|:---------------------:|:-------------------:|:---------:|:---------:|
| Viprosal    | TerjeSalveViprosal    | Salbentube          | 300       | 0.0       |
| Capsicum    | TerjeSalveCapsicum    | Salbentube          | 400       | 0.0       |
| Finalgon    | TerjeSalveFinalgon    | Salbentube          | 600       | 0.0       |

Parameter zum [Erstellen eigener Gegenstände](../../en/Modding/README.md#1-based-on-item)
```cs
    medHematomaHeal=1; // Stärke
    medHematomaHealTimeSec=400; // Dauer (s)
```


<a id="innere-organe-schuss-und-stichwunden"></a>

## ![Innere Organe](../../images/organs.png) ![Schusswunden](../../images/bullet.png) ![Stichwunden](../../images/cut3.png) VERLETZUNGEN INNERER ORGANE, SCHUSS- UND STICHWUNDEN

>Ein Spieler kann durch Nahkampfangriffe eine Stichwunde oder durch Schusswaffen eine Schusswunde erleiden. Beide können starke Blutungen verursachen und müssen sofort verbunden werden. Hämostatische Verbände sind wirksamer als normale Verbände oder Stoff. Nach dem Verbinden kann die Wunde leicht weiterbluten, bis der Fremdkörper operativ entfernt wurde. In schwereren Fällen können diese Wunden zu Verletzungen innerer Organe führen, die tiefer liegen und schwieriger zu behandeln sind. Eine gut gepflegte kugelsichere Weste schützt vor Schusswunden; ihre Wirksamkeit wird über einen Ballistikrechner bestimmt. Leichte Westen können Kleinkalibermunition abfangen, sind aber gegen mittlere und große Kaliber wirkungslos. Fängt die Weste die Kugel erfolgreich ab, erleidet der Spieler trotzdem eine ungeschützte Verletzung in Form eines Hämatoms.

| Name                                   | Gegenstand                       | Form und Verpackung    | Volumen | Innere Organe (Stärke/Zeit) | Schusswunde (Stärke/Zeit) | Stichwunde (Stärke/Zeit) |
|:--------------------------------------:|:--------------------------------:|:----------------------:|:-------:|:---------------------------:|:-------------------------:|:------------------------:|
| Medizinische Schale mit Instrument (Keramik) | TerjeSurgicalTool_Ceramic  | Chirurgische Instrumente | 1     | 0.05/90                     | 0.2/40                    | 0.4/30                   |
| Medizinische Schale mit Instrument (Weiß)    | TerjeSurgicalTool_White    | Chirurgische Instrumente | 1     | 0.05/90                     | 0.2/40                    | 0.4/30                   |
| Feld-Chirurgieset                      | TerjeSurgicalKit                 | Chirurgisches Set      | 5       | 0.2/40                      | 0.5/25                    | 0.7/20                   |
| IFAK                                   | TerjeFirstAidKitIndividual_Black | Universal-Set          | 10      | 0.3/40                      | 0.6/30                    | 0.8/20                   |
| AFAK                                   | TerjeFirstAidKitAdvance_Black    | Universal-Set          | 20      | 0.3/40                      | 0.6/30                    | 0.8/20                   |

Parameter zum [Erstellen eigener Gegenstände](../../en/Modding/README.md#1-based-on-item)
```cs
    medBloodStop=3;
    medBloodHemostaticValue=3;
    medBloodHemostaticTimeSec=60; // Dauer (s)
    terjeSurgeryKitRefill=1;
    terjeSurgeryVisceraEffectivity=0.3; // Heilungschance
    terjeSurgeryVisceraTime=40; // Dauer (s)
    terjeSurgeryBulletEffectivity=0.6; // Heilungschance
    terjeSurgeryBulletTime=30; // Dauer (s)
    terjeSurgeryStubEffectivity=0.8; // Heilungschance
    terjeSurgeryStubTime=20; // Dauer (s)
```

## ![Chirurgische Nähte](../../images/cut2.png) CHIRURGISCHE NÄHTE

>Chirurgische Nähte werden während einer Operation gesetzt und müssen regelmäßig desinfiziert werden, um einer Sepsis vorzubeugen. Sorgfältige Hygiene und Desinfektion sind entscheidend für eine erfolgreiche Heilung und verringern das Risiko lebensbedrohlicher Infektionen.

| Name                                   | Gegenstand                       | Form und Verpackung    | Volumen | Innere Organe (Stärke/Zeit) | Schusswunde (Stärke/Zeit) | Stichwunde (Stärke/Zeit) |
|:--------------------------------------:|:--------------------------------:|:----------------------:|:-------:|:---------------------------:|:-------------------------:|:------------------------:|
| Medizinische Schale mit Instrument (Keramik) | TerjeSurgicalTool_Ceramic  | Chirurgische Instrumente | 1     | 0.05/90                     | 0.2/40                    | 0.4/30                   |
| Medizinische Schale mit Instrument (Weiß)    | TerjeSurgicalTool_White    | Chirurgische Instrumente | 1     | 0.05/90                     | 0.2/40                    | 0.4/30                   |
| Feld-Chirurgieset                      | TerjeSurgicalKit                 | Chirurgisches Set      | 5       | 0.2/40                      | 0.5/25                    | 0.7/20                   |
| IFAK                                   | TerjeFirstAidKitIndividual_Black | Universal-Set          | 10      | 0.3/40                      | 0.6/30                    | 0.8/20                   |
| AFAK                                   | TerjeFirstAidKitAdvance_Black    | Universal-Set          | 20      | 0.3/40                      | 0.6/30                    | 0.8/20                   |

## ![Gehirnerschütterung](../../images/brain.png) GEHIRNERSCHÜTTERUNG

>Eine Gehirnerschütterung kann durch einen heftigen Schlag mit einem stumpfen Gegenstand auf den Kopf, eine Explosion in der Nähe des Charakters oder den Einschlag einer Kleinkaliberkugel auf einen ballistischen Helm entstehen. Erste Symptome sind Kopfschmerzen, Schwindel, unsichere Koordination und verschwommene Sicht, die Bewegung und Kampfkraft beeinträchtigen können. Eine Gehirnerschütterung klingt mit der Zeit von selbst ab, die Erholung lässt sich aber mit speziellen Medikamenten beschleunigen, die die Schwere der Symptome verringern.

| Name    | Gegenstand          | Phase       | Stufe | Form und Verpackung | Dauer (s) | Überdosis |
|:-------:|:-------------------:|:-----------:|:-----:|:-------------------:|:---------:|:---------:|
| Noopept | TerjePillsNoopept   | Behandlung  | -     | Tabletten           | 380       | 0.35      |
| Neirox  | TerjeAmpouleNeirox  | Behandlung  | -     | Ampulle             | 600       | 0.6       |
| Neirox  | TerjeInjectorNeirox | Behandlung  | -     | Injektor            | 500       | 0.3       |

Parameter zum [Erstellen eigener Gegenstände](../../en/Modding/README.md#1-based-on-item)
```cs
    medConcussionHealTimeSec = 300; // Dauer (s)
    overdosedIncrement = 0.3; // Überdosis
```

## ![Hämostase](../../images/blood3.png) HÄMOSTASE (BLUTUNGSRATE)

>Die Hämostase ist der natürliche Prozess deines Körpers, Blutungen zu stoppen. Dein Charakter kann den Blutverlust mit bestimmten Medikamenten verlangsamen und gewinnt so wertvolle Zeit, um die Verletzung zu überleben und weitere Hilfe zu suchen.

| Name              | Gegenstand                   | Phase      | Stufe | Form und Verpackung | Dauer (s) | Überdosis |
|:-----------------:|:----------------------------:|:----------:|:-----:|:-------------------:|:---------:|:---------:|
| Vikasol           | TerjePillsVikasol            | Behandlung | 1     | Tabletten           | 300       | 0.15      |
| Erytromixelin     | TerjeInjectorErytromixelin   | Behandlung | 3     | Injektor            | 300       | 0.32      |

Parameter zum [Erstellen eigener Gegenstände](../../en/Modding/README.md#1-based-on-item):
```cs
    medBloodHemostaticValue = 1; // Stärke
    medBloodHemostaticTimeSec = 300; // Dauer (s)
    overdosedIncrement = 0.15; // Überdosis-Zuwachs
```

## ![Hämatopoese](../../images/blood4.png) HÄMATOPOESE (BLUTREGENERATION)

>Die Hämatopoese ist der Prozess, mit dem dein Körper rote Blutkörperchen neu bildet. Dein Charakter kann die Blutregeneration mit bestimmten Medikamenten beschleunigen und sich so schneller von Schrammen, Schnittwunden und Schusswunden erholen.

| Name              | Gegenstand                   | Phase      | Stufe | Form und Verpackung | Dauer (s) | Überdosis |
|:-----------------:|:----------------------------:|:----------:|:-----:|:-------------------:|:---------:|:---------:|
| Irovit            | TerjePillsIrovit             | Behandlung | 1     | Tabletten           | 120       | 0.3       |
| Magnesium Sulfate | TerjePillsMagnesiumSulfate   | Behandlung | 1     | Tabletten           | 120       | 0.3       |
| Erythropoetin     | TerjeAmpouleErythropoetin    | Behandlung | 1     | Ampulle             | 600       | 0.4       |
| Erythropoetin     | TerjeInjectorErythropoietin  | Behandlung | 1     | Injektor            | 900       | 0.4       |
| Erytromixelin     | TerjeInjectorErytromixelin   | Behandlung | 2     | Injektor            | 300       | 0.32      |

Parameter zum [Erstellen eigener Gegenstände](../../en/Modding/README.md#1-based-on-item):
```cs
    medBloodRegenValue = 1; // Stärke
    medBloodRegenTimeSec = 120; // Dauer (s)
    overdosedIncrement = 0.3; // Überdosis-Zuwachs
```

# INFEKTIONEN UND KRANKHEITEN

## ![Erkältung](../../images/influenza.png) ERKÄLTUNG / LUNGENENTZÜNDUNG

>Durch längere Kälteeinwirkung kannst du dir eine Erkältung oder Grippe zuziehen. Ohne richtige Behandlung kann sich eine leichte Erkältung verschlimmern und schließlich zu einer Lungenentzündung entwickeln. Bei einer Lungenentzündung verliert dein Charakter langsam Gesundheit. Behandle sie mit Antibiotika derselben oder einer höheren Stufe; für eine vollständige Genesung sind oft mehrere Dosen nötig. Eine leichte Erkältung lässt sich durch Ausruhen an einem warmen Ort auskurieren.

| Name          | Gegenstand                 | Phase      | Stufe | Form und Verpackung | Dauer (s) | Überdosis |
|:-------------:|:--------------------------:|:----------:|:-----:|:-------------------:|:---------:|:---------:|
| Tetracycline  | TetracyclineAntibiotics    | Behandlung | 1     | Tabletten           | 300       | 0.45      |
| Paracetamol   | TerjePillsParacetamol      | Behandlung | 1     | Tabletten           | 200       | 0.45      |
| Amibaktam     | TerjePillsAmibaktam        | Behandlung | 1     | Tabletten           | 60        | 0.05      |
| Ibuprofen     | TerjePillsIbuprofen        | Behandlung | 2     | Tabletten           | 300       | 0.35      |
| Nurofen       | TerjePillsNurofen          | Behandlung | 2     | Tabletten           | 300       | 0.52      |
| Amoxiclav     | TerjePillsAmoxiclav        | Behandlung | 2     | Tabletten           | 1200      | 0.75      |
| Piperacillin  | TerjePillsPiperacylin      | Behandlung | 2     | Tabletten           | 1100      | 0.45      |
| Ketarol       | TerjeAmpouleKetarol        | Behandlung | 2     | Ampulle             | 1200      | 0.5       |
| Amoxivan      | TerjeAmpouleAmoxivan       | Behandlung | 2     | Ampulle             | 900       | 0.3       |
| Topoisomerase | TerjeInjectorTopoizomeraza | Behandlung | 3     | Injektor            | 900       | 0.65      |
| Imipenem      | TerjeAmpouleImipenem       | Behandlung | 3     | Ampulle             | 900       | 0.7       |
| Flemoclave    | TerjeAmpouleFlemoclav      | Behandlung | 3     | Ampulle             | 1200      | 0.8       |
| Amoxiclav     | TerjeInjectorAmoxiclav     | Behandlung | 3     | Injektor            | 1800      | 0.6       |
| Vaxicam       | TerjeAmpouleVaxicam        | Impfung    | -     | Ampulle             | 14400     | 0.8       |

Parameter zum [Erstellen eigener Gegenstände](../../en/Modding/README.md#1-based-on-item)
```cs
    medAntibioticLevel = 1; // Stärke
    medAntibioticsTimeSec = 300; // Dauer (s)
    overdosedIncrement = 0.45; // Überdosis
```

## ![Lebensmittelvergiftung](../../images/poisoning.png) LEBENSMITTELVERGIFTUNG

>Eine Lebensmittelvergiftung kann durch den Verzehr von verdorbenen oder nicht durchgegarten Speisen, faulem Obst, giftigen Pilzen oder verschmutztem Wasser entstehen – oder dadurch, dass man versehentlich Stoffe wie Benzin zu sich nimmt. Symptome wie Übelkeit und Erbrechen treten kurz nach dem Verzehr auf. Bleibt der Zustand unbehandelt, kann er sich verschlimmern und zu Austrocknung und allmählichem Gesundheitsverlust führen. Zur Behandlung gehört, viel Wasser zu trinken und bestimmte Medikamente zur Linderung der Symptome einzunehmen.

| Name                | Gegenstand                 | Phase      | Stufe | Form und Verpackung | Dauer (s) | Überdosis |
|:-------------------:|:--------------------------:|:----------:|:-----:|:-------------------:|:---------:|:---------:|
| Aktivkohle          | CharcoalTablets            | Behandlung | 1     | Tabletten           | 300       | 0.01      |
| Polysorb            | TerjePillsPolisorb         | Behandlung | 1     | Tabletten           | 300       | 0.05      |
| Phthalazole         | TerjePillsFtalazol         | Behandlung | 1     | Tabletten           | 1200      | 0.25      |
| Mesalazine          | TerjePillsMesalazin        | Behandlung | 2     | Tabletten           | 600       | 0.35      |
| Chelat-Tabletten    | ChelatingTablets           | Behandlung | 2     | Tabletten           | 600       | 0.6       |
| Metoclopramid       | TerjeAmpouleMetoclopramid  | Behandlung | 2     | Ampulle             | 1200      | 0.4       |
| Heptral             | TerjeAmpouleHeptral        | Behandlung | 3     | Ampulle             | 600       | 0.6       |
| Stomaproxidal       | TerjeInjectorStomaproxidal | Behandlung | 3     | Injektor            | 900       | 0.68      |

Parameter zum [Erstellen eigener Gegenstände](../../en/Modding/README.md#1-based-on-item)
```cs
    medAntipoisonLevel = 1; // Stärke
    medAntipoisonTimeSec = 300; // Dauer (s)
    overdosedIncrement = 0.45; // Überdosis
```

## ![Chemische Vergiftung](../../images/biohazard.png) CHEMISCHE VERGIFTUNG

>Eine chemische Vergiftung entsteht durch das Einatmen giftiger Gase. Erste Symptome sind Husten, bei fortschreitendem Zustand folgen Übelkeit und Erbrechen. In den späten Stadien führt die chemische Vergiftung zu schwerem Gesundheitsverlust und kann ohne rechtzeitige Behandlung tödlich enden. Um die Wirkung zu bekämpfen, nimm ein Gegengift oder spezielle Medikamente ein, die die Giftigkeit verringern.

| Name              | Gegenstand                | Phase      | Stufe | Form und Verpackung | Dauer (s) | Überdosis |
|:-----------------:|:-------------------------:|:----------:|:-----:|:-------------------:|:---------:|:---------:|
| Rombiopental      | TerjePillsRombiopental    | Behandlung | 1     | Tabletten           | 30        | 0.15      |
| Neurocetal        | TerjeAmpouleNeirocetal    | Behandlung | 2     | Ampulle             | 500       | 1.25      |
| AntiChem Injector | AntiChemInjector          | Behandlung | 3     | Injektor            | 180       | 1.1       |

Parameter zum [Erstellen eigener Gegenstände](../../en/Modding/README.md#1-based-on-item)
```cs
    medAntibiohazardLevel = 1; // Stärke
    medAntibiohazardTimeSec = 300; // Dauer (s)
    overdosedIncrement = 0.45; // Überdosis-Zuwachs
```

## ![Zombie-Virus](../../images/virusz.png) ZOMBIE-VIRUS

>Das Zombie-Virus wird über Tröpfchen in der Luft und Körperflüssigkeiten übertragen; im Nahkampf mit Zombies besteht eine geringe Ansteckungschance. Das Risiko steigt deutlich, wenn dich ein Zombie verletzt. Das Tragen einer Gesichtsmaske und ballistischer Schutzausrüstung kann die Ansteckungswahrscheinlichkeit verringern. Das Virus hat eine lange Inkubationszeit, sodass Spieler über eine Stunde Echtzeit haben, um ein Gegenmittel zu finden. Im Endstadium der Infektion sinkt deine Gesundheit rapide.

| Name      | Gegenstand                | Phase      | Stufe | Form und Verpackung | Dauer (s) | Überdosis |
|:---------:|:-------------------------:|:----------:|:-----:|:-------------------:|:---------:|:---------:|
| Zivirol   | TerjeAmpouleZivirol       | Behandlung | -     | Ampulle             | 1000      | 2.35      |
| Zivirol   | TerjeInjectorZivirol      | Behandlung | -     | Injektor            | 1200      | 2.5       |
| Zerivax   | TerjeAmpouleZerivax       | Impfung    | -     | Ampulle             | 7200      | 1.5       |

Parameter zum [Erstellen eigener Gegenstände](../../en/Modding/README.md#1-based-on-item)
```cs
    medZAntidotTimeSec = 300; // Dauer (s)
    overdosedIncrement = 0.45; // Überdosis-Zuwachs
    terjeAddHealth = -20; // Gesundheitsverlust bei Medikamenteninjektion
    terjeAddBlood = -10; // Blutverlust bei Medikamenteninjektion
    terjeAddShock = -100; // Schockverlust bei Medikamenteninjektion
```

## ![Sepsis](../../images/blood2.png) SEPSIS

>Eine Sepsis entsteht, wenn eine Infektion in eine offene Wunde eindringt. Mit geringer Wahrscheinlichkeit kann sie durch einen Zombie-Kratzer, eine Messerwunde oder eine Schusswunde ausgelöst werden. Das Risiko steigt deutlich, wenn du die Wunde mit schmutzigen Händen versorgst. Bleibt eine Sepsis unbehandelt, verschlechtert sich deine Gesundheit nach und nach.

| Name          | Gegenstand                  | Phase      | Stufe | Form und Verpackung | Dauer (s) | Überdosis |
|:-------------:|:---------------------------:|:----------:|:-----:|:-------------------:|:---------:|:---------:|
| Flemoclav     | TerjeAmpouleFlemoclav       | Behandlung | 3     | Ampulle             | 1200      | 0.8       |
| Imipenem      | TerjeAmpouleImipenem        | Behandlung | 3     | Ampulle             | 900       | 0.7       |
| Amoxiclav     | TerjeInjectorAmoxiclav      | Behandlung | 3     | Injektor            | 300       | 0.6       |
| Topoisomerase | TerjeInjectorTopoizomeraza  | Behandlung | 3     | Injektor            | 600       | 0.65      |

Parameter zum [Erstellen eigener Gegenstände](../../en/Modding/README.md#1-based-on-item)
```cs
    medAntibioticLevel = 1; // Stärke
    medAntisepsisTimeSec = 300; // Dauer (s)
    overdosedIncrement = 0.45; // Überdosis-Zuwachs
```

## ![Tollwut](../../images/virus.png) TOLLWUT

>Tollwut wird durch Bisse infizierter Tiere, etwa von Wölfen, übertragen. Nach der Ansteckung entwickelt sich die Krankheit schleichend und ohne unmittelbare Symptome. Im ersten Stadium treten leichte Temperaturschwankungen und Schwäche auf, die oft unbemerkt bleiben. Im zweiten Stadium verschlimmert sich der Zustand: Starke Übelkeit und Erbrechen verhindern, dass der Charakter essen oder trinken kann. Im kritischen dritten Stadium führt ein Temperaturanstieg zu schnellem Gesundheitsverlust, Erschöpfung und stark eingeschränkter Überlebensfähigkeit. Ohne rechtzeitige Behandlung verläuft die Krankheit tödlich. Eine Behandlung im Frühstadium mit speziellen Medikamenten oder eine Impfung vor der Ansteckung kann das Fortschreiten der Krankheit stoppen.

| Name            | Gegenstand                 | Phase      | Stufe | Form und Verpackung | Dauer (s) | Überdosis |
|:---------------:|:--------------------------:|:----------:|:-----:|:-------------------:|:---------:|:---------:|
| Rifampicin      | TerjeAmpouleRifampicyne    | Behandlung | 3     | Ampulle             | 300       | 1.35      |
| Rabinoline      | TerjeAmpouleRabinoline     | Behandlung | 2     | Ampulle             | 600       | 0.8       |
| Rabinucoline    | TerjeInjectorRabinucoline  | Behandlung | 3     | Injektor            | 900       | 1.46      |

Parameter zum [Erstellen eigener Gegenstände](../../en/Modding/README.md#1-based-on-item):
```cs
    medRabiesAntibioticLevel = 1; // Stärke
    medRabiesAntibioticTimeSec = 300; // Dauer (s)
    overdosedIncrement = 0.45; // Überdosis-Zuwachs
```

# SYMPTOME

## ![Schmerzen](../../images/pain.png) SCHMERZEN

>Schmerzen entstehen durch verschiedene Verletzungen, wobei ihre Intensität vom Schweregrad des Traumas abhängt. Schmerzen klingen mit der Zeit zwar von selbst ab, lassen sich aber mit Schmerzmitteln der entsprechenden oder einer höheren Stufe schneller lindern.

| Name             | Gegenstand                | Phase      | Stufe | Form und Verpackung | Dauer (s) | Überdosis |
|:----------------:|:-------------------------:|:----------:|:-----:|:-------------------:|:---------:|:---------:|
| Codeine          | PainkillerTablets         | Behandlung | 1     | Tabletten           | 300       | 0.2       |
| Analgin          | TerjePillsAnalgin         | Behandlung | 1     | Tabletten           | 500       | 0.15      |
| Nimesulide       | TerjePillsNimesulid       | Behandlung | 1     | Tabletten           | 600       | 0.25      |
| Paracetamol      | TerjePillsParacetamol     | Behandlung | 1     | Tabletten           | 200       | 0.45      |
| Ibuprofen        | TerjePillsIbuprofen       | Behandlung | 1     | Tabletten           | 600       | 0.35      |
| Nurofen          | TerjePillsNurofen         | Behandlung | 1     | Tabletten           | 350       | 0.52      |
| Noopept          | TerjePillsNoopept         | Behandlung | 1     | Tabletten           | 380       | 0.35      |
| Ketarol          | TerjeAmpouleKetarol       | Behandlung | 1     | Ampulle             | 1200      | 0.5       |
| Novacaine        | TerjeAmpouleNovacaine     | Behandlung | 2     | Ampulle             | 1200      | 0.4       |
| Morphinocin      | TerjeAmpouleMorphine      | Behandlung | 3     | Ampulle             | 850       | 0.52      |
| Hexobarbital     | TerjeAmpouleGexobarbital  | Behandlung | 3     | Ampulle             | 900       | 0.65      |
| Reanimatal       | TerjeInjectorReanimatal   | Behandlung | 3     | Injektor            | 240       | 1.85      |
| Propital         | TerjeInjectorPropital     | Behandlung | 2     | Injektor            | 180       | 0.75      |
| Morphine         | Morphine                  | Behandlung | 3     | Injektor            | 300       | 0.75      |
| Promidol         | TerjeInjectorPromidol     | Behandlung | 3     | Injektor            | 600       | 0.45      |

Parameter zum [Erstellen eigener Gegenstände](../../en/Modding/README.md#1-based-on-item):
```cs
    medPainkillerLevel = 1; // Stärke
    medPainkillerTimeSec = 300; // Dauer (s)
    overdosedIncrement = 0.45; // Überdosis-Zuwachs
```

## ![Überdosis](../../images/overdose.png) ÜBERDOSIS

>Eine Überdosis tritt auf, wenn zu große Mengen an Medikamenten oder giftigen Substanzen in den Körper gelangen.  
Die Überdosis klingt allmählich ab, sobald die Giftstoffe aus dem Körper ausgeschieden werden. Sie verläuft in drei Stadien:  

>**Erstes Stadium:** Der Charakter leidet unter Übelkeit und Halluzinationen und verliert die Klarheit seiner Wahrnehmung.  

>**Zweites Stadium:** Der Zustand verschlimmert sich, und der Charakter kann das Bewusstsein verlieren und ist seiner Umgebung schutzlos ausgeliefert.  

>**Drittes Stadium:** Es kommt zu einer kritischen Verschlechterung der Gesundheit, die das Leben des Charakters bedroht.  

| Name          | Gegenstand    | Phase      | Stufe | Form und Verpackung | Dauer (s) | Überdosis |
|:-------------:|:-------------:|:----------:|:-----:|:-------------------:|:---------:|:---------:|
| Wasser        | WaterBottle   | Behandlung | 1     | Flasche             | 300       | 0.0       |

# EMOTIONALE ZUSTÄNDE

## ![Schlaf](../../images/dream.png) SCHLAF

>Dein Charakter braucht jetzt Schlaf – genau wie Nahrung und Wasser. Regelmäßige Ruhe ist unerlässlich, um Gesundheit und Ausdauer zu erhalten.  
Wird die Schlafanzeige gelb, beginnt der Charakter zu gähnen, und seine Sicht verschlechtert sich allmählich.  
Erreicht die Anzeige die rote Stufe, kann der Charakter vor Erschöpfung das Bewusstsein verlieren. Warme Orte eignen sich am besten zum Schlafen – am Lagerfeuer, in einem Zelt, in einem Haus oder in einem Schlafsack. Schlafen ist unmöglich, wenn der Charakter friert, hungert oder ernsthafte gesundheitliche Probleme hat (Krankheiten ab dem zweiten Stadium). Im Schlaf regeneriert der Charakter schnell Gesundheit und Blut und hat die Chance, sich von leichten Erkrankungen wie einer Grippe im ersten Stadium zu erholen. Schlafsäcke sorgen für zusätzliche Wärme und Komfort und machen das Schlafen unter rauen Bedingungen sicherer und effektiver.  


| Name                      | Gegenstand          | Phase    | Stufe | Form und Verpackung | Dauer (s) | Überdosis |
|:-------------------------:|:-------------------:|:--------:|:-----:|:-------------------:|:---------:|:---------:|
| MadBull® Energy Drink     | TerjeDrinkMadBull   | Erholung | 8     | Flasche             | 1.0       | 0.0       |
| Gang® Energy Drink        | TerjeDrinkGang      | Erholung | 6     | Flasche             | 1.0       | 0.0       |
| Yaguar® Energy Drink      | TerjeDrinkYaguar    | Erholung | 10    | Flasche             | 1.0       | 0.0       |
| PrayBoy® Energy Drink     | TerjeDrinkPrayboy   | Erholung | 4     | Flasche             | 1.0       | 0.0       |
| 6Energy® Energy Drink     | TerjeDrink6Energy   | Erholung | 8     | Flasche             | 0.8       | 0.0       |

Parameter zum [Erstellen eigener Gegenstände](../../en/Modding/README.md#1-based-on-item):
```cs
    medSleepingIncrementValue = 8; // Stärke
    medSleepingIncrementTimeSec = 0.8; // Dauer (s)
    overdosedIncrement = 0.45; // Überdosis-Zuwachs
```

## ![Psychische Gesundheit](../../images/mental.png) PSYCHISCHE GESUNDHEIT

>Die psychische Gesundheit des Charakters kann sich unter extremem Stress verschlechtern, etwa durch Zombie-Angriffe, längeren Aufenthalt in gefährlichen Psi-Zonen oder den Verzehr von Menschenfleisch. Das kann zu Nervenzusammenbrüchen und Halluzinationen führen. Diese Zustände können Panik und Orientierungslosigkeit auslösen und das Überleben sowie die Interaktion mit der Umgebung erschweren. Um diese Symptome in den Griff zu bekommen, nutze Antidepressiva, die die Psyche des Charakters stabilisieren und die negativen Auswirkungen von Stress abmildern.  


| Name              | Gegenstand                   | Phase      | Stufe | Form und Verpackung | Dauer (s) | Überdosis |
|:-----------------:|:----------------------------:|:----------:|:-----:|:-------------------:|:---------:|:---------:|
| Adepress          | TerjePillsAdepress           | Behandlung | 1     | Tabletten           | 150       | 0.2       |
| Agteminol         | TerjePillsAgteminol          | Behandlung | 1     | Tabletten           | 120       | 0.2       |
| Venlafaxine       | TerjePillsVenlafaxine        | Behandlung | 1     | Tabletten           | 250       | 0.3       |
| Actaparoxetine    | TerjeAmpouleActaparoxetine   | Behandlung | 2     | Ampulle             | 400       | 0.4       |
| Amitriptyline     | TerjeAmpouleAmitriptyline    | Behandlung | 3     | Ampulle             | 600       | 0.4       |
| Metralindole      | TerjeAmpouleMetralindole     | Behandlung | 2     | Ampulle             | 300       | 0.1       |
| Amfitalicyne      | TerjeInjectorAmfitalicyne    | Behandlung | 3     | Injektor            | 520       | 0.6       |

Parameter zum [Erstellen eigener Gegenstände](../../en/Modding/README.md#1-based-on-item):
```cs
    medAntidepresantLevel = 1; // Stärke
    medAntidepresantTimeSec = 300; // Dauer (s)
    overdosedIncrement = 0.45; // Überdosis-Zuwachs
```

# ZONEN

# 🧠 Psionische Zone

Psionische Zonen sind **gefährliche Gebiete mit starker psychoaktiver Wirkung**, die die psychische Gesundheit eines Charakters beeinflussen.

## ⚠️ Was die Effekte bewirken:
1. Die **Psionische Zone** breitet sich in einem Radius aus: Je näher der Charakter am Zentrum ist, desto stärker ist ihre Wirkung.

2. **Psychische Auswirkung**:
Innerhalb der Psionischen Zone verliert der Charakter nach und nach psychische Gesundheit, was sich äußert in:
  - Panik, Halluzinationen und anderen abnormalen Reaktionen.
  - Der Unfähigkeit, den Charakter normal zu steuern.

3. **Kritischer Zustand**:
Erreicht die psychische Gesundheit null, kann sich der Charakter selbst töten oder andere unvorhersehbare Handlungen ausführen, die zum Tod führen können.

## 🛡️ Psionischer Schutz
Um Psionische Zonen sicher zu betreten, musst du [Antidepressiva](#-psychische-gesundheit) einnehmen, um deinen psychischen Zustand zu stabilisieren.
Zum Schutz kannst du außerdem den **PSI-Helm** – **TerjeHeadgearPsiHelm** – verwenden. Der Standardschutz beträgt 95 %.

## 🛡️ Schutz per SteamID
Um bestimmten Spielern einen Zonenschutz zuzuweisen, musst du **Core.UseCustomProtectionConfigs** in der Datei **Core.cfg** unter **profiles\TerjeSettings\Core.cfg** aktivieren.
```cs
Core.UseCustomProtectionConfigs = true;
```
Starte den Server neu, nachdem du diesen Parameter aktiviert hast.

Im Ordner **profiles\TerjeSettings\CustomProtection** findest du dann eine Datei namens **psionic.txt**.

Dort kannst du die SteamIDs der Spieler eintragen, die du schützen möchtest. Jede SteamID muss in eine neue Zeile geschrieben werden.

#### Beispiel:
```cs
76561190000000000
76561190000000001
76561190000000002
```
---

## ⚙️ Zonenkonfiguration:
- **Intensität und Größe der Zonen** lassen sich in der [Konfiguration](../../en/Modding/README.md#zones) über die Festlegung der Gefahrenstufe anpassen.
- Ein **Schutzanzug-Set** kannst du anhand der [Anleitung](../../en/Modding/README.md#parameters-protectionbodyvalues-and-protectionbodythresholds) erstellen.
