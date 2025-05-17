# Vending Machine Power Cycle & Configuration Test  
**Technician:** Tomas Nauckunas  
**Scope:** Uninstall → transport → reinstall → startup QA  
**Units Covered:** Snack, beverage, and combo vending machines  
**Environments:** Office buildings, gyms, commercial lots  
**Period:** 2022–2025

---

## Objective

To ensure that vending machines transported and reinstalled at new locations power on correctly, maintain cooling function (if applicable), and restore correct system configurations without failure or user-facing errors.

---

## Tools Used

- Multimeter  
- Level tool  
- Coin/test card  
- Product sensor probe  
- IR thermometer  
- Internal diagnostics key or code (when accessible)

---

## QA Checklist After Reinstall

### 1. **Electrical Test**
- [ ] Machine grounded  
- [ ] Power input voltage confirmed  
- [ ] Fuse intact / surge protector present  
- [ ] System powers on cleanly (no flicker/reboot loop)

### 2. **Cooling Unit Check (if beverage/combo unit)**
- [ ] Compressor audible  
- [ ] Temperature drop confirmed (IR gun at vent + tray)  
- [ ] Interior reaches safe temp within 30 minutes  
- [ ] Fan running (no stalls or burn smell)

### 3. **Sensor + Mechanism Test**
- [ ] Item detection sensors trigger correctly  
- [ ] Product drop tray sensor confirms delivery  
- [ ] Motors run for all active rows  
- [ ] Item spiral alignment tested and reset if needed

### 4. **Payment + UI**
- [ ] Display shows welcome or idle screen  
- [ ] Coin slot accepts test insert  
- [ ] Card reader powers up (if available)  
- [ ] Touchpad/buttons responsive  
- [ ] Pricing visible and matches programming  
- [ ] Admin access tested with code/key

### 5. **Product Load & Dispense**
- [ ] Sample item loaded and dispensed for test  
- [ ] Drop tray sensor registered item delivery  
- [ ] No jams or failed ejects  
- [ ] Tray lights functional (where available)

---

## Common Issues + Fixes

| Issue | Cause | Resolution |
|-------|-------|------------|
| No power | Unstable wall voltage | Moved to regulated outlet |
| UI screen glitch | Ribbon cable loose during move | Reconnected inside control board |
| Misaligned spiral | Item dropped halfway | Manual rotation + row reset |
| Cooling failure | Compressor delay | Power cycled, waited 10 min reboot |
| Payment system down | Loose connector | Reseated + confirmed status lights |

---

## Technician Notes

- Always test **one item per row** to confirm motor alignment  
- Never stack product unless motor test is passed or risk jam  
- Some machines require **10+ minute reset time** before cooling triggers  
- UI failures are often wiring or dust-related after move, don’t assume display fault  
- Leveling is critical: uneven placement = failed item detection or jams

---

## Last Updated: May 2025
