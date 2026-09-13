# Dr. Igris - Sovereign Device License & Remote Revocation Registry
Managed by **Taher Abdelkader (طاهر عبد القادر)**

This repository controls the remote licensing and device revocation status for **Dr. Igris AI Assistant**.

---

## 🚫 How to Block a Device / User (طريقة حظر أي جهاز أو مستخدم)

1. Open [`blocked_devices.txt`](blocked_devices.txt) directly here on GitHub (or from the GitHub mobile app).
2. Click the **Edit (pencil)** icon.
3. Add the customer's **Motherboard Serial Number** OR **Dr. Igris Device ID** on a new line:
   ```text
   # Blocked User: John Doe (Refund requested)
   PF2K89AB
   IGRIS-A4B7-91CF-E320-X8K9
   ```
4. Click **Commit changes**.
5. **Done!** The device is blocked worldwide within seconds. The app will immediately revoke their license and refuse to open.

---

## 🟢 How to Unblock a Device (طريقة إلغاء الحظر)

1. Open [`blocked_devices.txt`](blocked_devices.txt) and click **Edit**.
2. Delete the blocked ID line (or put `#` before it).
3. Click **Commit changes**.
