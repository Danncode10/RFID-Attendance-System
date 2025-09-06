# 📱 **Screen Flow (Wireframe for Officer App)**

### 1. **Login Screen**

* 🔑 Username & Password input
* 👉 “Login” button
* (Optional: Simple logo / header text like *Dept. Attendance System*)

---

### 2. **Dashboard (Home)**

* Big clean cards/buttons for:

  * ➕ **Create Event**
  * 📋 **View Events**
  * 👤 **Register Student**
  * 🚪 **Logout**
* Top section: *Welcome, Officer \[Name]*

---

### 3. **Create Event**

* Input fields:

  * 📝 Event Name
  * 📅 Date/Time (auto-filled but editable)
* “Save Event” button → returns to Dashboard

---

### 4. **Event List (View Events)**

* List of all events (e.g., *Sportsfest Day 1 – Sept 20, 2025*).
* Tap an event → goes to **Event Attendance Screen**.

---

### 5. **Event Attendance Screen**

* Title: *Sportsfest Day 1*
* ✅ List of students:

  * Name + Student No + Status (Present/Absent/Time In/Time Out).
  * Status color-coded (Green/Red/Blue).
* 📊 Summary bar:

  * Total Students | Present | Absent
* 📤 Export button (CSV/Excel).

---

### 6. **Register Student Screen**

* RFID reader scans UID → App shows: *“Unknown Card Detected”*.
* Officer enters:

  * Name
  * Student No
* Tap “Register” → Student is added to DB.

---

# 🎨 Aesthetic Suggestions

* Use **flat, modern design** (light colors, simple icons).
* Use **cards and rounded buttons** (big enough for easy clicking).
* Use icons for quick recognition:

  * 📋 for Events
  * 👤 for Students
  * ➕ for Create
  * 🚪 for Logout
* Color scheme idea:

  * Primary: Deep Blue (trust/professional)
  * Accent: Green (success) + Red (alert)

---

⚡ **Flow Example (Officer using app):**

1. Officer logs in → Dashboard.
2. Creates event *Sportsfest Day 1*.
3. Students tap cards → UID received.

   * If registered → log attendance.
   * If not → officer registers student.
4. Officer opens Event Attendance → sees list + summary.
5. End of event → export report.

---
