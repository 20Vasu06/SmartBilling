🧾 Smart Billing System
🔍 Real-Time Object Detection + Automated Invoicing via SMS & PDF
A smart point-of-sale (POS) system powered by YOLOv8, Streamlit, and Twilio that detects items through a webcam, generates an invoice on the fly, and supports digital payment workflows — all designed to impress users and juries alike.

🚀 Features
🎥 Real-time item detection using YOLOv8 (Ultralytics)
📦 Automatic billing with live total and itemized view
➕➖ Manual quantity adjustment for detected items
📲 Mobile number input to send invoices via SMS
🖨️ PDF invoice generation with:
Date/time
Item list
Total amount
Payment method
✔️ PAID label
💳 Payment methods:
Pay at Counter
Pay Online (QR-based UPI support)
✅ Confirm payment flow with visual feedback
📤 Send e-invoice via SMS using Twilio
🧾 Start new bill button resets app to mobile number screen
🎨 Visually enhanced UI using custom styling and responsive layout
🛠️ Tech Stack
Category	Technology
Frontend	Streamlit
ML Model	YOLOv8
Invoice Engine	ReportLab (reportlab)
SMS API	Twilio Python SDK
Payment UI	UPI QR integration
CV Backend	OpenCV (cv2)
Deployment	Anaconda + Streamlit
🔧 Installation
Clone the repository:
git clone https://github.com/your-username/smart-billing-app.git
cd smart-billing-app
Create environment (optional but recommended):
conda create -n smartbill python=3.10
conda activate smartbill
Install dependencies:
pip install -r requirements.txt
Run the app:
streamlit run app.py
🔐 Twilio Setup
Create a free Twilio account
Get your:
ACCOUNT_SID
AUTH_TOKEN
TWILIO_PHONE_NUMBER
Replace them inside your app.py:
TWILIO_SID = "your_twilio_sid"
TWILIO_AUTH_TOKEN = "your_auth_token"
TWILIO_PHONE_NUMBER = "+1xxxxxxxxxx"
📄 PDF Invoice Example
Every invoice PDF includes:

Date & time
Detected items
Manual adjustments
Payment method
✔️ PAID stamp
Ready for download/print
🧠 Future Enhancements (Planned)
📊 Sales analytics dashboard
🧑 Admin login + user roles
📱 WhatsApp invoice sending
🧾 Download CSV bill history
☁️ Firebase or Supabase integration
👤 Author
Pawan Bhatia
📧 pawanbhatia1304@gmail.com
🐱 GitHub

🏁 License
MIT License
