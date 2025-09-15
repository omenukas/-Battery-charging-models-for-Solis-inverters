# ESO planinis atjungimas – pasiruošimas ir atstatymas

**Pasiruošia planiniam ESO atjungimui ir vėliau atstato nustatymus.**

- YAML: `../../automations/lt/lt/lt_grid_planned_outage_prep_restore.yaml`
- [English version](../en/lt_grid_planned_outage_prep_restore.md)

## Priklausomybės
- `calendar.eso_planiniai_darbai`
- `input_boolean.akumuliatoriu_rankinis_rezervavimas`
- `input_boolean.turn_off`
- `input_boolean.turn_on`
- `number.set_value`
- `number.solis_waveshare_backup_soc`
- `sensor.solis_waveshare_a_phase_voltage`
- `sensor.solis_waveshare_b_phase_voltage`
- `sensor.solis_waveshare_battery_soc`
- `sensor.solis_waveshare_c_phase_voltage`
- `switch.grid_time_of_use_charging_period_1`
- `switch.reserve_battery_mode`
- `switch.turn_off`
- `switch.turn_on`

## Kaip naudoti
- Nukopijuokite YAML į savo Home Assistant.
- Įsitikinkite, kad reikalingi helperiai sukurti (žr. **Priklausomybės**).
- Perkraukite automatikas/korteles arba Home Assistant.