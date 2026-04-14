# Safety Model

## High Voltage Safety Rules

- All battery packs must include independent BMS monitoring
- Minimum isolation resistance threshold required before activation
- Emergency contactor cutoff required on all builds

## Fault Handling Philosophy

System defaults to:
- FAIL SAFE (no torque output)
- NOT FAIL ACTIVE

## Critical Fault Conditions

- Overvoltage (> pack limit)
- Thermal runaway risk
- CAN bus desync or invalid state
- Brake/throttle conflict

## Emergency Behavior

On critical fault:
1. Torque request = 0
2. Contactor open
3. System enters locked diagnostic mode
