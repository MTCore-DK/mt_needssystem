# MT Needs System  

## Dansk

**Beskrivelse**  
MT Needs System er et overlevelsessystem til FiveM. Spilleren skal spise, drikke og sove, hvilket påvirker health, stamina, bevægelse og syn. Lav hunger, thirst eller søvn giver gradvist effekter som sløret syn og langsommere bevægelse for en realistisk hardcore survival oplevelse.  

**Funktioner**  
- Mad og drikke via ox_inventory  
- Progress bar og animationer via ox_lib  
- HUD med Hunger, Thirst og Sleep  
- Effekter på spiller:  
  - Lav hunger, thirst eller søvn  langsommere bevægelse  
  - Lav stamina og health-skade  
  - Sløret syn ved ekstrem lav hunger, thirst eller søvn  
- Dehydration-effekt  lav thirst skader health gradvist  
- Notifikationer via ox_lib ved kritiske niveauer  
- Sprogvalg: dansk eller engelsk  

**Installation**  
1. Placer `mt_needsystem` i din `resources` mappe.  
2. Tilføj `start mt_needsystem` i din `server.cfg`.  
3. Sørg for, at ox_inventory og ox_lib er installeret på serveren.  

**Konfiguration**  
- Rediger `config.lua` for at ændre:  
  - Items til mad og drikke  
  - Hvor meget mad/drikke/søvn restaurerer  
  - Kritiske niveauer for effekter  
  - Sprog (`"dk"` eller `"en"`)  

**Commands**  
- `/eat`  spis mad, hvis i inventory  
- `/drink`  drik, hvis i inventory  
- `/sleep`  sov for at genoprette sleep  

---

## English

**Description**  
MT Needs System is a survival system for FiveM. Players need to eat, drink, and sleep, which affects health, stamina, movement, and vision. Low hunger, thirst, or sleep gradually causes effects like blurred vision and slower movement for a realistic hardcore survival experience.  

**Features**  
- Food and drinks via ox_inventory  
- Progress bar and animations via ox_lib  
- HUD showing Hunger, Thirst, and Sleep  
- Player effects:  
  - Low hunger, thirst, or sleep  slower movement  
  - Reduced stamina and health damage  
  - Blurred vision at extreme low levels  
- Dehydration effect low thirst gradually damages health  
- Notifications via ox_lib at critical levels  
- Language selection: Danish or English  

**Installation**  
1. Place `mt_needsystem` in your `resources` folder.  
2. Add `start mt_needsystem` to your `server.cfg`.  
3. Make sure ox_inventory and ox_lib are installed on the server.  

**Configuration**  
- Edit `config.lua` to change:  
  - Food and drink items  
  - How much food/drink/sleep restores  
  - Critical thresholds for effects  
  - Language (`"dk"` or `"en"`)  

**Commands**  
- `/eat`  eat food if in inventory  
- `/drink`  drink if in inventory  
- `/sleep`  sleep to restore sleep  
