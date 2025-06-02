# 🛠️ VoIP Troubleshooting Case Study – Red Icon, No Calls

## 🎯 Issue Summary
A VoIP phone displayed a red phone icon and could not make or receive calls. Web access to the device failed despite an assigned IP address, and the device was powered via PoE.

## 🧪 Steps Taken
1. Verified the phone had a valid IP address.
2. Confirmed the PoE switch was delivering power (device powered on).
3. Swapped Ethernet ports on the switch:
   - Problem resolved.
   - Verified that the original port was faulty (not delivering data).
4. Ethernet cable was reused in the working port — confirmed the cable was good.
5. Plan to test and document the faulty port for hardware or misconfiguration.

## ✅ Resolution
- Rerouted the device’s network cable to a known-good switch port.
- Device came online, web interface accessible, and call functionality restored.

## 💡 Lessons Learned
- PoE delivering power ≠ a fully working Ethernet port.
- Always check physical layer (Layer 1) before escalating.
- A methodical approach isolates issues efficiently.

## 🧠 Skills Demonstrated
- Network Layer 1 & 2 troubleshooting
- VoIP hardware diagnostics
- Problem isolation using cable/port swap
- Documentation of real-world IT support tasks
