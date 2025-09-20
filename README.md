# 🎟️ Event Registration & Attendee Management – Salesforce Application

## 📌 Project Overview
The **Event Registration & Attendee Management System** is a Salesforce-based solution designed to digitize and centralize event organization activities.  
The goal is to streamline **event creation, attendee registration, and automated confirmation communication**, while also providing organizers with real-time dashboards and reports.

This solution enables:  
- ✅ Event managers to create and track events  
- ✅ Attendees to register easily  
- ✅ Automatic confirmation emails upon successful registration  
- ✅ Reports & Dashboards showing registrations per event for better decision-making  

---

## 🚀 Phase 1: Problem Understanding & Industry Analysis

### **Problem Statement**
Event organizers often face challenges such as:  
1. Manual attendee registrations (spreadsheets, paper forms)  
2. Lack of automated communication with attendees  
3. Difficulty in tracking event capacity and attendance  
4. No central dashboard to view registrations across events  

### **Solution**
A Salesforce-based centralized system to:  
- Manage **Events** and **Attendees** using custom objects  
- Create relationships between events and attendees  
- Automate confirmation emails via **Flows & Email Alerts**  
- Provide **real-time dashboards** to track attendees per event  

---

## ⚙️ Phase 2: Org Setup & Configuration
- Created a Salesforce Developer Org  
- Enabled Lightning Experience  
- Configured **Tabs, App Launcher access, and Object permissions**  

---

## 🗂️ Phase 3: Data Modeling & Relationships
- **Custom Objects:**  
  - `Event` → Stores event details (Name, Date, Location, Capacity)  
  - `Attendee` → Stores attendee details (Name, Email, Registered Event)  

- **Relationships:**  
  - Lookup relationship from **Attendee → Event**  

---

## 🔄 Phase 4: Process Automation (Admin)
- Built a **Record-Triggered Flow** on Attendee creation  
- Configured **Email Alerts** linked to the Flow  
- Created a **Lightning Email Template** for confirmation  

---

## 💻 Phase 5: Apex Programming (Developer)
- For this phase, the project does not require Apex  
- **Future scope:**  
  - Apex class for **bulk registrations import**  
  - Apex trigger for **event capacity validation**  

---

## 🖥️ Phase 6: User Interface Development
- Created **Tabs** for Event and Attendee objects  
- Customized **Page Layouts** to show related attendees under each event  
- Added navigation in the Salesforce App for easy access  

---

## 🌐 Phase 7: Integration & External Access
- **Current scope:** No external integration  
- **Future scope:** Integrate with external event management apps (e.g., Eventbrite, Google Calendar)  

---

## 📊 Phase 8: Data Management & Deployment
- Loaded sample data for Events and Attendees  
- Version-controlled metadata & documentation in **GitHub**  
- Deployment possible via **Change Sets / SFDX**  

---

## 📈 Phase 9: Reporting, Dashboards & Security Review
- **Report:** Number of Attendees per Event  
- **Dashboard:** Visual charts of registrations  
- Reviewed **Object permissions & field-level security** for Attendees and Events  

---

## 🔮 Future Scope / Enhancements
- Event capacity validation & waitlist feature  
- Integration with **Payment Gateway** for paid events  
- Attendee self-registration portal (**Experience Cloud**)  
- Mobile-friendly LWC for attendees to register directly  

---

## 👨‍💻 Author
Adarsh M
B.E. Computer Science Engineering  
📍 India  
