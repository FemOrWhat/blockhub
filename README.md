**Note:** All of these are for **ChromeOS**.  

#  Unblockers  

> **Disclaimer:** I am **not** responsible for any damage done to your Chromebook, nor will I fix anything if something goes wrong. If you need help, open an issue. **None of these will bypass network blocks.**  

---

## 📢 Want to add more tricks? **Fork this!**  


---

## Incognito Trick  
*Discovered by my friend :3*  

✅ Works on **all extensions**  
🔹 **Confirmed working on ChromeOS 126** (patched in 131)  

### **Requirements:**  
- A network that requires sign-in (opens a window asking for a username and password)  

### **Steps:**  
1. Connect to the Wi-Fi network (often named something like "**____ External Guests**" or "**____ Staff Personal Technology**").  
2. When the sign-in window appears, press **Ctrl + T**.  
3. If an **Incognito window** opens, you're good to go! If not, check your ChromeOS version.  

---

## Extension Corrupter / ABC Hack  
*Discovered by ?*  

✅ Works on **any extension**  
🔹 **Confirmed working on ChromeOS 119** (not tested on 120+)  

### **Requirements:**  
- Bookmarklets must be unblocked  
- Bookmarks bar must be visible  

### **Steps:**  
1. Find the **extension ID**:  
   - Go to `chrome://extensions/`.  
   - Click **Details** on the extension you want to block.  
   - Copy the **ID** from the search bar (e.g., `haldlgldplgnggkjaafhelgiaglafanh` for GoGuardian).  
2. Open `chrome-extension://YOUR-ID-HERE/manifest.json`, replacing `YOUR-ID-HERE` with your extension’s actual ID.  
3. Add these two bookmarklets to your bookmarks bar:  
   - `chrome://hang/`  
   - `chrome://kill`  
4. On the **manifest.json** page, click the **first bookmark** (`hang`).  
5. Quickly **reload the page**.  
6. Click the **second bookmark** (`kill`) **repeatedly and rapidly**.  

> **Result:** This **completely disables** any extension until sign-out.  

---

## GetGone for GoGuardian  
*Discovered by ?*  

✅ Works on **GoGuardian**  
🔹 **Confirmed working on ChromeOS 121** (patched in 122+)  

### **Requirements:**  
- GoGuardian must be installed  

### **Steps:**  
1. **Turn off** your internet connection.  
2. **Sign out** of your Chromebook.  
3. **Sign back in** with any account.  
4. Open a new tab (**don’t enter a URL yet**).  
5. Click **rapidly** on the GoGuardian extension (not the license one) for about **30 seconds**—it should be pinned.  
6. If the extension **turns dark gray**, it worked! 🎉 If not, go back to step **2**.  

> If the icon **turns white**, double-check your version.  
> **Note:** Sometimes GoGuardian will randomly reactivate.  
