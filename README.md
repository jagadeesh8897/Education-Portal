# Education-Portal 

A **custom ServiceNow application** designed to digitalize core school operations — from admissions to exam result declarations — with **automation, notifications, and smart workflows**.  

---

## 📹 Project Demo  
👉 [Watch Demo Video](https://drive.google.com/drive/folders/1W_JnOeTH7cB3QeFH7oPqz0oogsu0Y7Sl)
*(or check `/demo/project-demo.mp4` if downloaded from repo)*  

---

## 🚀 Key Highlights  

✅ **Student & Parent Management**  
- Maintain student profiles and link parent records.  
- Store academic, contact, and guardian details.  

✅ **Admissions Workflow**  
- Auto-generate admission numbers.  
- Manage fees, application dates, and status updates.  
- Parents receive **email notifications** upon admission decision.  

✅ **Exams & Marks Recording**  
- Support for **Internal** (FA1, FA2…) and **External** exams.  
- Capture subject-wise marks and total marks.  
- Auto-calculate **percentage** across multiple subjects.  

✅ **Results Automation**  
- Business Rule to set **Pass/Fail** based on percentage (≥ 35 = Pass).  
- Auto-update result whenever new marks are entered.  
- Parents notified via **email** once results are declared.  

✅ **Real-time Updates**  
- Client Scripts to instantly update **percentage** when selecting an exam.  
- Business Rules to recalculate results dynamically.  

---

## 🛠️ How It Was Built  

1. **Data Model**  
   - Custom tables: `Student`, `Parent`, `Admission`, `Exam`, `Marks`, `Exam Result`.  
   - Relationships mapped (Student ↔ Parent, Student ↔ Exam Result).  

2. **Forms & UI**  
   - Designed form layouts for logical grouping (Personal Info, Marks, Results).  
   - Configured list views with important fields (ID, Name, Grade, Status).  

3. **Automation**  
   - **Business Rules**: Admission No. generation, percentage calculation, pass/fail assignment.  
   - **Client Scripts**: Real-time percentage updates via GlideAjax.  

4. **Notifications**  
   - Admission decision → Parent email.  
   - Exam results declared → Parent email with marks & percentage.  

---

## 🧑‍💻 Tech Stack  

- **ServiceNow Platform** (Scoped App Development)  
- **GlideRecord, GlideAggregate, GlideAjax** APIs  
- **Business Rules & Client Scripts**  
- **Notifications & Email Templates**  

---

## 📌 Demo Flow  

1. **Add Student & Parent** → Student linked with guardian.  
2. **Submit Admission** → Decision email sent to parent.  
3. **Create Exam & Enter Marks** → Subject-wise marks recorded.  
4. **Exam Result Generated** → Percentage auto-calculated + Result (Pass/Fail).  
5. **Parent Notified** → Email with child’s exam performance.  

---

## 👤 Author  

**Jagadeesh Sege**  
🎓 B.Tech CSE – 4th Year, Srinivasa Ramanujan Institute of Technology  
💡 Passionate about ServiceNow Development, Automation, and Business Workflow Design  

