# Inspection Results

Date: 2024-11-30 (Initial inspection)
Last updated: 2025-12-31

## Summary

**Overall status: NEARLY READY TO RUN!**

Radio system fully working with new crystals. Engine has new glow plug. Fresh fuel acquired. Just need to drain old fuel and find a fitting antenna.

## Current Status

### Engine (Kyosho GS11X)
| Component | Status | Notes |
|-----------|--------|-------|
| Crankshaft | ✅ OK | Turns freely, not seized |
| Compression | ✅ OK | Can feel compression when pulling starter |
| Pull starter | ✅ FIXED | Cleaned cord and mechanism - works properly now |
| Glow plug | ✅ INSTALLED | New OS 8 glow plug installed |
| Air filter | ✅ NEW | New filter installed (slightly larger, fits OK) |
| One-way bearing | ⚠️ Unknown | Clicking sound when spinning clutch bell - may need replacement |

### Fuel System
| Component | Status | Notes |
|-----------|--------|-------|
| Fuel tank | ✅ CLEANED | Flushed with IPA, drying |
| Fuel lines | ✅ OK | Original lines still soft and flexible |
| Fuel filter | ✅ CLEANED | Flushed with IPA, flows OK |
| Fresh fuel | ✅ READY | 2.5L nitro fuel (16%) purchased |

### Radio System (Hitec HP-2RNB)
| Component | Status | Notes |
|-----------|--------|-------|
| Transmitter (Ranger II) | ✅ WORKING | Cleaned, new crystal installed |
| Transmitter antenna | ❌ MISSING | Purchased antenna too thick - need thinner one |
| Receiver (HP-2RNB) | ✅ WORKING | Responds to transmitter! |
| Crystals | ✅ MATCHED | Both TX and RX now 27.145 MHz |
| Steering servo | ✅ WORKING | Responds to transmitter input |
| Throttle servo | ✅ WORKING | Responds to transmitter input |
| Battery holder | ✅ NEW | New holder with switch installed |
| Power switch | ✅ NEW | Replaced with new switch from AliExpress |

### Chassis & Drivetrain
| Component | Status | Notes |
|-----------|--------|-------|
| Wheels/Tires | ✅ OK | Still soft, foam inserts present |
| Drivetrain | ⚠️ Partial | Some movement to wheels but may have slack |
| Chassis | ✅ CLEANED | Washed and cleaned |

---

## Restoration Log

### Session 1: Initial Inspection (2024-11-30)
- Transmitter had battery corrosion - cleaned with vinegar
- Receiver battery holder had NiCd leak - cleaned with vinegar
- Discovered crystal mismatch (TX: 27.045 MHz, RX: 26.995 MHz)
- Found power switch broken - bypassed for testing
- Confirmed servos work when receiver gets power

### Session 2: Parts Installation (2024-12-28)
- Washed truck exterior - much cleaner now
- Transmitter also cleaned - has glossy finish under the dirt
- Installed OS 8 glow plug - went smoothly
- Installed new air filter (slightly larger, fits OK)
- Replaced both crystals with matching 27.145 MHz pair
- Installed new battery holder with integrated switch
- **RADIO NOW FULLY WORKING** - both servos respond to TX!
- Antenna from AliExpress didn't fit (too thick for TX hole)
- Drained and cleaned fuel system with isopropanol (Blårens)
- Old fuel had turned to varnish/gunk (IPA turned blue-green)
- Flushed fuel filter - flows OK
- System disassembled and drying
- Pull starter issue: cord doesn't retract properly (weak spring or dirt buildup)
- Plan: lubricate with WD-40 before first start attempt

### Session 3: First Start Attempt (2025-12-31)
- Lubricated pull starter with WD-40
- Reassembled fuel system
- Filled with fresh 16% nitro fuel
- Glow starter charged and working (plug glows orange)
- Radio system working, servos responding

**Start attempt: UNSUCCESSFUL**

Observations:
- Fuel flows through lines to carburetor area
- Glow plug is dry - fuel not reaching combustion chamber
- Pull starter still sluggish despite WD-40 - hard to pull fast enough
- Fuel filter has minor leak (not introducing air)
- Possible minor leak near engine area

**Hypotheses:**
1. **Pull starter too weak** - Can't pull fast/hard enough to create proper suction
2. **Needle valve too lean** - Mixture screw may be closed too much
3. **Carburetor gummed up** - Old fuel residue may be blocking internal passages
4. **Compression/vacuum issue** - Not creating enough suction to draw fuel in

### Session 3 continued: Pull Starter Fix (2025-12-31)
- Disassembled pull starter unit (removed wheel to access screws)
- Found: cord/rope was heavily soiled and stiff from 30 years of dirt
- Cleaned all parts with isopropanol (IPA)
- Washed cord thoroughly - now soft and flexible again
- Reassembled pull starter
- **RESULT: Pull starter now works properly!** Spring returns cord without issues
- Comparison to old photos shows cord now hangs with natural slack (was stiff before)
- Plan: Apply silicone spray tomorrow for optimal lubrication

**Root cause identified:** The dirty/stiff cord was preventing the spring from retracting properly. Cleaning restored full function.

---

## Remaining Tasks

### To Get Engine Running
| Task | Status |
|------|--------|
| Drain old fuel | ✅ Done |
| Reassemble fuel system | ✅ Done |
| Fill with fresh fuel | ✅ Done |
| Charge glow starter | ✅ Done |
| First start attempt | ❌ Failed - fuel not reaching combustion chamber |
| Fix pull starter | ✅ Done - cleaned, cord was stiff from dirt |
| Apply silicone spray to pull starter | ⏳ Tomorrow |
| Adjust carburetor (needle valve) | ⏳ May still need adjustment |
| **Second start attempt** | ⏳ After silicone spray |
| Replace fuel filter | ⏳ Minor leak observed - low priority |
| Find fitting TX antenna | ⏳ Low priority |

### Nice to Have
| Task | Priority |
|------|----------|
| Fine-clean transmitter | Low |
| Inspect one-way bearing | Low |
| Replace pull starter spring | Low |

---

## Parts Acquired

| Item | Source | Status |
|------|--------|--------|
| OS 8 Glow Plug | Elefun | ✅ Installed |
| HPI Nitro Starter Pack | Elefun | ✅ Received |
| Fuel lines (spare) | Elefun | ✅ Received (not needed yet) |
| Air filter | ? | ✅ Installed |
| 27.145 MHz Crystal Pair | AliExpress | ✅ Installed |
| Battery holder + switch | AliExpress | ✅ Installed |
| M4 Antenna | AliExpress | ❌ Doesn't fit (too thick) |
| Nitro fuel 16% (2.5L) | ? | ✅ Ready |

---

## Antenna Issue

The M4 telescopic antenna purchased from AliExpress is too thick to fit through the antenna hole in the transmitter housing.

**Next steps:**
1. Try screwing the antenna onto the TX antenna mount to check if thread matches
2. Measure the hole diameter in the TX housing
3. Find a thinner antenna that fits

---

## Photos
- Battery holder with corrosion (before)
- Power switch
- Hitec HP-2RNB receiver
- Multimeter testing
- Wiring overview
- TX internals showing crystal
