# 🏠 HostelSOS
HostelSOS is a modern hostel-issue reporting application built for the **Google AdMob App Development Challenge 2025**.  
It enables students to anonymously report hostel issues, track complaint status in real-time, and view analytics — while providing hostel management with an organized system to respond efficiently.

---

## 🚀 Features
- Anonymous issue reporting  
- Issue categories (Maintenance, Safety, Cleanliness, etc.)  
- Severity tagging (Low / Medium / High)  
- Photo uploads  
- Real-time status tracking (Pending → In Progress → Resolved)  
- Analytics dashboard (issue distribution, severity trends, Hostel Condition Score)  
- Notification system for updates  
- Dark & Light modes  
- Google AdMob monetization (non-intrusive)

---

## 🧠 Technology Stack

### **Frontend / App Development**
**Lovable AI**  
- Used to build UI screens, navigation, and app logic  
- Supports rapid prototyping and exportable builds  

### **Backend**
**Supabase (PostgreSQL + API)**  
- Stores all issue reports, categories, severity, timestamps  
- Provides RESTful APIs for CRUD operations  
- Offers real-time subscriptions for updates  

### **Authentication**
**Supabase Auth**  
- Secure login handling  
- Manages user sessions  
- Supports anonymous usage where needed  

### **File Storage**
**Supabase Storage**  
- Stores uploaded issue images  
- Provides accessible secure URLs  

### **Notifications**
**Supabase Triggers + Lovable Logic**  
- Sends in-app notifications when issue status is updated  

### **Monetization**
**Google AdMob**  
- Integrated strategically into non-intrusive screens  
- Allows app to remain free to use  

### **Deployment**
- Built and exported through Lovable AI  
- Deliverable APK tested on Android devices  

---

## 📦 Repository Structure


## License
This project is licensed under the Apache License 2.0.  
See the LICENSE file for details.
