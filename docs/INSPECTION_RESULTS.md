# Inspection Results

Date: 2024-11-30 (Updated after debugging session)

## Summary

**Overall status: VERY PROMISING** - The truck is in excellent condition for 30 years old. Radio system fully functional after debugging!

## Findings

### Engine (Kyosho GS11X)
| Component | Status | Notes |
|-----------|--------|-------|
| Crankshaft | ✅ OK | Turns freely, not seized |
| Compression | ✅ OK | Can feel compression when pulling starter |
| Pull starter | ⚠️ Weak | Works but return spring is weak/slow |
| Glow plug | ❌ Missing | Hole is open - need to buy new plug |
| One-way bearing | ⚠️ Unknown | Clicking sound when spinning clutch bell - may need replacement |

### Fuel System
| Component | Status | Notes |
|-----------|--------|-------|
| Fuel tank | ✅ OK | Present and intact |
| Fuel lines | ✅ Surprisingly good | Still soft and flexible |
| Old fuel | ⚠️ Must drain | Liquid still in system - must be removed |

### Radio System (Hitec HP-2RNB)
| Component | Status | Notes |
|-----------|--------|-------|
| Transmitter (Ranger II) | ✅ WORKING | Had battery corrosion - cleaned with vinegar, now powers on |
| Receiver (HP-2RNB) | ✅ WORKING | Tested with bypass - responds to transmitter! |
| Steering servo | ✅ WORKING | Responds when receiver has power |
| Throttle servo | ✅ WORKING | Responds when receiver has power |
| Receiver battery holder | ✅ CLEANED | Was corroded - cleaned with vinegar, now outputs 5V |
| Power switch | ❌ BROKEN | Does not pass power through - must be replaced |

### Chassis & Drivetrain
| Component | Status | Notes |
|-----------|--------|-------|
| Wheels/Tires | ✅ OK | Still soft, foam inserts present |
| Drivetrain | ⚠️ Partial | Some movement to wheels but may have slack |

## Debugging Session Log

### Transmitter Fix
1. Transmitter had battery corrosion - would not power on
2. Cleaned contacts with white vinegar + toothbrush
3. Result: LED lights up, transmitter works!

### Receiver Battery Fix
1. 4x VARTA NiCd batteries had leaked - heavy white/green corrosion
2. Cleaned battery holder contacts with vinegar
3. Installed 4x fresh AA batteries
4. Measured 5.07V output - battery holder works!

### Power Switch Problem Found
1. Measured voltage at battery = 5V ✓
2. Measured voltage at receiver = 0V ✗
3. Concluded: Switch is not passing power through
4. Bypassed switch with temporary wires
5. Result: Receiver powers on, servos respond! Radio system works!

## Action Items

### Must Fix Before Running
1. **Buy glow plug** - Engine cannot fire without it
2. ~~**Clean transmitter corrosion**~~ ✅ DONE
3. ~~**Clean receiver battery holder**~~ ✅ DONE
4. **Replace power switch** - Simple on/off switch, ~30-50 kr
5. **Drain old fuel** - Old nitro turns to varnish
6. **Buy fresh nitro fuel** - Need 16-20% nitromethane

### Should Buy/Have Ready
- Glow starter/igniter (to start engine)
- AA batteries for transmitter (8x) ✅ Have
- AA batteries for receiver (4x) ✅ Have

### Nice to Fix
- Pull starter return spring (works but weak)
- Inspect one-way bearing (clicking sound)

## Updated Shopping List

### Essential (must have to run)
| Item | Est. Price (NOK) | Notes |
|------|------------------|-------|
| Glow plug | 50-100 kr | Standard size, "hot" rating for .12 engine |
| Glow starter | 250-400 kr | Rechargeable preferred |
| Nitro fuel (1L) | 150-250 kr | 16-20% nitro, 8-12% oil |
| On/off switch | 30-50 kr | Simple replacement for broken one |

### Recommended
| Item | Est. Price (NOK) | Notes |
|------|------------------|-------|
| Spare glow plugs (3-pack) | 150-200 kr | Good to have extras |
| After-run oil | 50-100 kr | Protects engine between runs |

**Estimated minimum to get running: ~500-800 kr**

## Photos Added This Session
- Battery holder with corrosion
- Power switch
- Hitec HP-2RNB receiver
- Multimeter testing
- Wiring overview
