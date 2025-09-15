# Solar – Periodic Charging

**Performs a periodic full battery charge every N days at a set time.**

- YAML: `../../automations/en/en/solar_periodic_charging.yaml`
- [Lithuanian version](../lt/solar_periodic_charging.md)

## Dependencies
- `input_boolean.solar_winter_mode`
- `input_datetime.set_datetime`
- `input_datetime.solar_charge_2_last_run`
- `input_datetime.solar_charge_2_time`
- `input_number.solar_charge_2_days_interval`
- `sensor.solis_waveshare_battery_soc`
- `switch.grid_time_of_use_charging_period_2`
- `switch.turn_off`
- `switch.turn_on`

## How to use
- Copy the YAML into your Home Assistant setup.
- Ensure the required helpers exist (see **Dependencies**).
- Reload automations/cards or restart Home Assistant.