# Winter Mode Reserve – Backup SOC & Reserve Mode

**Manages battery reserve and inverter reserve mode for winter season.**

- YAML: `../../automations/en/en/winter_mode_reserve.yaml`
- [Lithuanian version](../lt/winter_mode_reserve.md)

## Dependencies
- `input_boolean.manual_battery_reserve`
- `input_boolean.solar_winter_mode`
- `input_number.battery_reserve`
- `input_number.battery_reserve_summer`
- `number.set_value`
- `number.solis_waveshare_backup_soc`
- `switch.reserve_battery_mode`
- `switch.turn_off`
- `switch.turn_on`

## How to use
- Copy the YAML into your Home Assistant setup.
- Ensure the required helpers exist (see **Dependencies**).
- Reload automations/cards or restart Home Assistant.