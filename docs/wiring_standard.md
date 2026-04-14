# Wiring Standard

## Voltage Domains

- HV: 200V – 800V (traction system)
- LV: 12V or 48V (control systems)

## Communication

- CAN Bus (primary control layer)
- Optional UART fallback for legacy modules

## Connector Philosophy

- Salvaged connectors allowed
- Adapter harness system required

## Minimum Required Signals

- Throttle input
- Brake input
- Motor temperature
- Battery state of charge
- Fault line (global interrupt)
