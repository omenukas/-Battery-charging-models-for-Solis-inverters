# Žiemos režimo rezervas – Backup SOC ir Reserve Mode

**Valdo akumuliatoriaus rezervą ir inverterio Reserve Mode žiemos sezonui.**

- YAML: `../../automations/lt/lt/lt_winter_mode_reserve.yaml`
- [English version](../en/lt_winter_mode_reserve.md)

## Priklausomybės
- `input_boolean.akumuliatoriu_rankinis_rezervavimas`
- `input_boolean.ziemos_rezimas_elektrinei`
- `input_number.akumuliatoriaus_rezervavimas`
- `input_number.akumuliatoriaus_rezervavimas_vasarai`
- `number.set_value`
- `number.solis_waveshare_backup_soc`
- `switch.reserve_battery_mode`
- `switch.turn_off`
- `switch.turn_on`

## Kaip naudoti
- Nukopijuokite YAML į savo Home Assistant.
- Įsitikinkite, kad reikalingi helperiai sukurti (žr. **Priklausomybės**).
- Perkraukite automatikas/korteles arba Home Assistant.