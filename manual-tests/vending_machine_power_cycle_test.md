# Vending Machine Power Cycle & Configuration Test  
**Technician:** Tomas Nauckunas  
**Scope:** Uninstall → transport → reinstall → startup QA  
**Units Covered:** Snack, beverage, and combo vending machines  
**Environments:** Office buildings, gyms, commercial lots  
**Period:** 2022–2025

---

## 🎯 Objective

To ensure that vending machines transported and reinstalled at new locations power on correctly, maintain cooling function (if applicable), and restore correct system configurations without failure or user-facing errors.

---

## 🛠 Tools Used

- Multimeter  
- Level tool  
- Coin/test card  
- Product sensor probe  
- IR thermometer  
- Internal diagnostics key or code (when accessible)

---

## 🔧 QA Checklist After Reinstall

### ⚡ 1. **Electrical Test**
- [x] Machine grounded  
- [x] Power input voltage confirmed  
- [x] Fuse intact / surge protector present  
- [x] System powers on cleanly (no flicker/reboot loop)

### 🧊 2. **Cooling Unit Check (if beverage/combo unit)**
- [x] Compressor audible  
- [x] Temperature drop confirmed (IR gun at vent + tray)  
- [x] Interior reaches safe temp within 30 minutes  
- [x] Fan running (no stalls or burn smell)

### 🔧 3. **Sensor + Mechanism Test**
- [x] Item detection sensors trigger correctly  
- [x] Product drop tray sensor confirms delivery  
- [x] Motors run for all active rows  
- [x] Item spiral alignment tested and reset if needed

### 💳 4. **Payment + UI**
- [x] Display shows welcome or idle screen  
- [x] Coin slot accepts test insert  
- [x] Card reader powers up (if available)  
- [x] Touchpad/buttons responsive  
- [x] Pricing visible and matches programming  
- [x] Admin access tested with code/key

### 🔁 5. **Product Load & Dispense**
- [x] Sample item loaded and dispensed for test  
- [x] Drop tray sensor registered item delivery  
- [x] No jams or failed ejects  
- [x] Tray lights functional (where available)

---

## ⚠️ Common Issues + Fixes

| Issue | Cause | Resolution |
|-------|-------|------------|
| No power | Unstable wall voltage | Moved to regulated outlet |
| UI screen glitch | Ribbon cable loose during move | Reconnected inside control board |
| Misaligned spiral | Item dropped halfway | Manual rotation + row reset |
| Cooling failure | Compressor delay | Power cycled, waited 10 min reboot |
| Payment system down | Loose connector | Reseated + confirmed status lights |

---

## 🧠 Technician Notes

- Always test **one item per row** to confirm motor alignment  
- Never stack product unless motor test is passed — or risk jam  
- Some machines require **10+ minute reset time** before cooling triggers  
- UI failures are often wiring or dust-related after move — don’t assume display fault  
- Leveling is critical: uneven placement = failed item detection or jams

---

## 📅 Last Updated: May 2025
