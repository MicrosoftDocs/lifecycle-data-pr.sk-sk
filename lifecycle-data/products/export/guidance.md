---
title: Informácie k exportu údajov životného cyklu
description: Pomoc s informáciami o exporte údajov životného cyklu produktu
ms.date: 12/16/2020
layout: ContentPage
ms.openlocfilehash: 5e9dddbff5fac32e6d3cf8ef0943151d2dfe5e35
ms.sourcegitcommit: 6ea3221fd5475440480515f04f33988656d71748
ms.translationtype: HT
ms.contentlocale: sk-SK
ms.lasthandoff: 11/02/2021
ms.locfileid: "3546871"
---
# <a name="lifecycle-data-export-guidance"></a>Informácie k exportu údajov životného cyklu
Tento dokument opisuje použitie súboru exportu produktu.

## <a name="query-information"></a>Informácie o dotazoch
V dokumente Excel existujú polia na jednoduchšiu identifikáciu údajov vyplnených v tabuľke produktov.

### <a name="end-of-support"></a>Ukončenie podpory
Hodnota ukončenia podpory bude filtrovať produkty podľa dátumu ukončenia podpory produktu alebo dátumu ukončenia jeho vydania.

Možné hodnoty: Všetko (nie je použitý žiadny filter), Rok a Rozsah.

### <a name="family"></a>Rodina
Hodnota radu filtruje produkty podľa nadradenej úrovne v rámci hierarchie známej ako rad.

Možné hodnoty: Všetko (nie je použitý žiadny filter), Názov radu

### <a name="group"></a>Skupina
Hodnota skupiny filtruje produkty v rámci svojej nadradenej úrovne (radu) do konkrétnej skupiny.

Možné hodnoty: Všetko (nie je použitý žiadny filter), Názov skupiny

## <a name="table-columns"></a>Stĺpce tabuľky
Tabuľka produktov obsahuje stĺpce definujúce produkt, edície, vydania a zodpovedajúce dátumy podpory.

> [!NOTE]
> K dispozícii bude riadok pre každú kombináciu produktu, edície a vydania.

### <a name="product"></a>Produkt
Názov produktu.

### <a name="edition"></a>Vydanie
Stĺpec edície sa vyplní, keď produkt obsahuje edície. Keď nie je k dispozícii žiadna edícia produktu, toto pole bude prázdne.

### <a name="release"></a>Vydanie
Stĺpec vydania sa vyplní, keď produkt obsahuje viacero vydaní.
Keď má produkt len jedno vydanie, toto pole bude prázdne.

### <a name="support-policy"></a>Politika podpory
Toto pole definuje, ktorou politikou podpory sa produkt riadi.

Možné hodnoty: [Pevná](/lifecycle/policies/fixed), [Moderná](/lifecycle/policies/modern), Súčasť

### <a name="start-date"></a>Dátum začiatku
Dátum začiatku podpory pre produkt.

### <a name="mainstream-date"></a>Dátum bežnej podpory
Ak je politika podpory **Pevná** alebo **Súčasť**, je to dátum ukončenia bežnej podpory produktu.
  
Ak je politika podpory **Moderná**, toto pole bude prázdne.

### <a name="extended-end-date"></a>Predĺžený dátum ukončenia
Keď je politika podpory **Pevná** alebo **Súčasť**, je to predĺžený dátum ukončenia podpory produktu.

Ak je politika podpory **Moderná**, toto pole bude prázdne.

### <a name="retirement-date"></a>Dátum vyradenia
Keď je politika podpory **Pevná** alebo **Súčasť**, toto pole bude prázdne.

Keď je politika podpory **Moderná**, bude to dátum vyradenia produktu.

### <a name="release-start-date"></a>Dátum začiatku vydania
Dátum začiatku podpory pre vydanie. Keď má produkt len jedno vydanie, toto pole bude prázdne.
 
### <a name="release-end-date"></a>Dátum ukončenia vydania
Dátum ukončenia podpory pre vydanie.
Keď má produkt len jedno vydanie, toto pole bude prázdne.

### <a name="docs-url"></a>Adresa URL dokumentov
Adresa URL pre rozšírenú dokumentáciu.
