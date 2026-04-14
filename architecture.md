# System Architecture

## Overview

The Junker EV system is divided into four abstraction layers:

### 1. Hardware Layer
- Motors (AC induction, BLDC, hub motors)
- Battery modules (EV packs, second-life cells)
- Sensors (throttle, brake, temperature)

### 2. Interface Layer
- CAN bus communication
- Power distribution bus (400V / 800V)
- Signal normalization layer

### 3. Control Layer (VCU)
- Torque request handling
- Battery safety enforcement
- Regenerative braking logic

### 4. Application Layer
- Drive modes (eco / sport / utility)
- Telemetry dashboard
- Diagnostic tools

## Key Idea

All hardware is treated as "unknown until described by a profile."
