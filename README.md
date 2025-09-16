# Home Assistant – Solis baterijų krovimo automatikos ir kortelės (LT/EN)

<a href="https://buymeacoffee.com/omenukas">
  <img src="https://cdn.buymeacoffee.com/buttons/v2/default-yellow.png" alt="Buy Me A Coffee" height="42">
</a>



🟡 **Ši versija – lietuvių kalba.**  
🔵 [English version](README.en.md)

## Apžvalga

Šiame repozitoriume pateikiu keletą automatizacijų, kurios galėtų padėti valdyti ir prižiūrėti, kaupiklius, prijungtus prie Jūsų Solis įtampos keitiklio. Galima automatizacijas pritaikyti ir kitų gamintojų įtampos keitikliams, parenkant tinkamus sensorius, tačiau šis projektas paruoštas, naudojant [Solis modbus](https://github.com/Pho3niX90/solis_modbus) integraciją. Kadangi naudoju Waveshare modbus keitiklį, tai Solis integracijoje sensoriai turi atitinkamus pavadinimus, kuriuos automatizacijose jums gali reikėti pakoreguoti pagal savo sensorių atitinkamus pavadinimus.
Mano Solis dashboard'as atrodo taip:
 
![dashboard](docs/img/dashboard_overview.jpg)



Home Assistant **automatizacijos** ir **Lovelace kortelės** pateikiamos dviem kalbomis: **lietuviškai (LT)** ir **angliškai (EN)**. LT yra numatytoji; kiekviename kataloge yra atitikmuo EN.

## Struktūra
```
automations/
  ├─ lt/  # lietuviškos automatikos (YAML)
  └─ en/  # angliškos automatikos (YAML)
cards/
  ├─ lt/  # lietuviškos Lovelace kortelės (YAML)
  └─ en/  # angliškos Lovelace kortelės (YAML)
helpers/
  ├─ lt/helpers_lt.yaml  # LT helperių aprašymai su ikonėlėmis
  └─ en/helpers_en.yaml  # EN helperių aprašymai su ikonėlėmis
```

## Kaip naudoti
1. **Helperiai**
   Automatizacijose ir kortelėse naudojama visa eilė helper tipo subjektų (entity). Todėl pradžioje reikia sukurti visus reikalingus helper'ius. **SVARBU** naudoti tos pačios kalbos automatizacijas, korteles ir helper'ius - Visi komponentai turi būti arba tik angliški arba tik lietuviški.
   - YAML naudotojams: įtraukite `helpers/lt/helpers_lt.yaml` **arba** `helpers/en/helpers_en.yaml` į `configuration.yaml`.
   - Jei helperius kūrėte per UI, šiuos failus naudokite kaip pavyzdį pavadinimams/ikonėlėms. Nepamirškite patikrinti ar susikūrė tiksliai toks Entity ID.

3. **Automatikos**  
   - Pasirinktos kalbos `.yaml` nukopijuokite į `config/automations/` ir **perkraukite automatikas**.

4. **Kortelės**  
   - Kortelių YAML įkelkite į dashboard’ą (Raw configuration editor) arba įtraukite per `!include`.



Jeigu patiko mano darbas, visada galite tai įvertinti 
<a href="https://buymeacoffee.com/omenukas">
  <img src="https://cdn.buymeacoffee.com/buttons/v2/default-yellow.png" alt="Buy Me A Coffee" height="42">
</a>
