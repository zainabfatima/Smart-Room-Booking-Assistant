# Smart-Room-Booking-Assistant
his project is a conversational AI chatbot that helps users book rooms and notifies the team via email using IBM Watson Assistant and IBM Cloud Functions.
# WatsonRoomie - AI Room Booking Chatbot 🤖🏨

This project is a conversational AI chatbot that helps users book rooms and notifies the team via email using IBM Watson Assistant and IBM Cloud Functions.

---

## 🛠 Features

- Built with IBM Watson Assistant
- Handles room bookings, greetings, cancellations, and FAQs
- Sends email notifications through Gmail SMTP using IBM Cloud Functions
- Supports slot-filling to collect date, time, and phone number
- Interactive and customizable chatbot experience

---

## 📦 File Structure

| File                      | Purpose                                                |
|---------------------------|--------------------------------------------------------|
| `skill-Room-Booking.json` | Chatbot's intents, entities, dialog, and webhook config|
| `IBM_Cloud_Function.py`   | Sends email when booking is completed                  |
| `README.md`               | Instructions to set up the project                     |
| `demo.gif`                | Demo of chatbot functionality                          |

---

## 🚀 How to Run

### 1. Clone This Repository

```bash
git clone https://github.com/shsarv/Machine-Learning-Projects.git
cd "AI Room Booking Chatbot [IBM WATSON]"
