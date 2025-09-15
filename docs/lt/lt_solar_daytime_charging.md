# Akumuliatorių įkrovimas nuo saulės – dienos logika

**Dienos metu krauna akumuliatorių iš saulės pagal prognozes ir slenksčius.**

- YAML: `../../automations/lt/lt/lt_solar_daytime_charging.yaml`
- [English version](../en/lt_solar_daytime_charging.md)

## Priklausomybės
- `input_boolean.ziemos_rezimas_elektrinei`
- `input_datetime.reakcija_i_laika`
- `input_number.reakcija_i_dienos_max_generacija`
- `input_number.reakcija_i_gamybos_prognoze`
- `sensor.solcast_pv_forecast_forecast_today`
- `sensor.solcast_pv_forecast_peak_forecast_today`
- `sensor.solis_waveshare_battery_soc`
- `switch.feed_in_priority_mode`
- `switch.turn_off`
- `switch.turn_on`

## Kaip naudoti
- Nukopijuokite YAML į savo Home Assistant.
- Įsitikinkite, kad reikalingi helperiai sukurti (žr. **Priklausomybės**).
- Perkraukite automatikas/korteles arba Home Assistant.