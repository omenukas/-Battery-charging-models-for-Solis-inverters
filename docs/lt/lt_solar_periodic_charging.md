# Solis – periodinis krovimas

**Kas N dienų atlieka pilną akumuliatoriaus įkrovimą nustatytu laiku.**

- YAML: `../../automations/lt/lt/lt_solar_periodic_charging.yaml`
- [English version](../en/lt_solar_periodic_charging.md)

## Priklausomybės
- `input_boolean.ziemos_rezimas_elektrinei`
- `input_datetime.set_datetime`
- `input_datetime.solis_krovimo2_laikas`
- `input_datetime.solis_krovimo2_paskutinis_vykdymas`
- `input_number.solis_krovimo2_dienu_intervalas`
- `sensor.solis_waveshare_battery_soc`
- `switch.grid_time_of_use_charging_period_2`
- `switch.turn_off`
- `switch.turn_on`

## Kaip naudoti
- Nukopijuokite YAML į savo Home Assistant.
- Įsitikinkite, kad reikalingi helperiai sukurti (žr. **Priklausomybės**).
- Perkraukite automatikas/korteles arba Home Assistant.