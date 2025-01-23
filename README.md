# Flipper0-iOS-Crash  
**Educational Ducky Script to Demonstrate Bluetooth Exploitation on iOS Devices**  

## **Description**  
This repository provides a Ducky Script designed for the Flipper Zero, enabling a Bluetooth-based attack to crash iOS devices. By using the "Bad BT" (Bluetooth) approach, this script leverages a specific "exploit"(spam) that crashes devices running iOS versions <18.2.  

**Disclaimer: This script is intended solely for educational and awareness purposes.**  
It demonstrates the dangers of outdated firmware and vulnerabilities. Misuse of this script for illegal activities is strictly prohibited. Always test responsibly and with prior consent from the device owner.  

---

## **Features**  
- Demonstrates how malformed inputs can cause system instability via Bluetooth.  
- Compatible with the Flipper Zero for easy deployment and execution.  

---

## **How It Works**  
The included Ducky Script executes a series of commands intended to overwhelm and exploit weaknesses in the target device's input system, leading to a crash. Below is a breakdown of the script:  

1. **Initial Steps:**  
   - The script starts by opening a spotlight-like search using `GUI h`, followed by `GUI SPACE`, to ensure the target system's attention is redirected to running commands.  

2. **Triggering the Crash:**  
   - The script simulates a repeated, rapid combination of inputs (`GUI-SHIFT 4`) with precise timing (`DELAY 1`) to overload the iOS Bluetooth stack.  
   - The repetitive input triggers a buffer overflow or resource exhaustion, causing the device to become unresponsive or crash.  

3. **Final Outcome:**  
   - The device's crash or restart occurs due to the vulnerability in processing repeated malformed inputs through Bluetooth channels.  

---

## **Prerequisites**  
1. A Flipper Zero device capable of running Ducky Scripts.  
2. Knowledge of transferring and executing scripts on the Flipper Zero.  
3. An iOS device

---

## **Usage**  
1. **Transfer the Script:**  
   - Copy the provided `payload.txt` to the Flipper Zero’s storage.  
   - Ensure Bluetooth is enabled on the Flipper Zero.  

2. **Execution:**  
   - Open the Ducky Script file on the Flipper Zero.  
   - Execute the script in proximity to a target device (within Bluetooth range).  

3. **Testing Ethically:**  
   - Ensure you have explicit permission from the device owner before testing.  

---

## **Recommendations for Users**  
- **Update iOS Firmware:** Always keep your iOS devices updated to avoid vulnerabilities like this.  
- **Limit Bluetooth Use:** Disable Bluetooth when not actively using it to reduce exposure to potential exploits.  
- **Monitor Bluetooth Activity:** Be cautious of unknown devices attempting to connect or interact.  

---

## **Important Disclaimer**  
This script is provided for **educational purposes only** to raise awareness of Bluetooth security risks. Misuse of this script, including unauthorized testing or malicious activity, may be illegal and is strictly discouraged.  
The author is not responsible for any damages caused by improper use of this script. Use responsibly and ethically.  
