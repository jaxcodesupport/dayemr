# dayemr

Pieces

1. Homepage - phone number, link to a New Patient Form (Josh)
2. Dashboard - Appointment page (Damian), list/schedule (Robert), login (Diego), create accounts/roles (Sam), patient record form to enter vitals (O2, BP, HR, height, weight) (John), HPI, PMH, Chief Complaint, etc., Assessment/Plan, logout,

3. Account Records Information
   3.1 DataBase

   - Account ID (Integer, Unique Number for Account Record)
   - First Name (60 Character Limit, Employees First Name)
   - Last Name (60 Character Limit, Employees Last Name)
   - Account Roles (30 character, "Admin", "Staff", "Physician")
   - User Name (60 Character Limit, Login User Name)
   - Acct PWD (60 Character Limit, Login Password, MD5 Stored in DB)
   - Acct Stats (30 Character Limit, "Enabled", "Disabled")

   3.2 Account Actions
   3.2.1 View Acconts List (Admin Only)
   3.2.2 Create Record (Admin Only)
   3.2.3 Update Record (Admin Only)
   3.2.4 View Record (Admin, Staff, Physician) (Block Password view)
