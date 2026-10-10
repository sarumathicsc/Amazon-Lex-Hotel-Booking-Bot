# 🏨 Amazon Lex Hotel Booking Bot

An interactive hotel booking chatbot built using **Amazon Lex** to collect guest details and hotel booking preferences through a conversational interface.

## 📌 Project Overview

The Hotel Booking Bot is designed to simplify the hotel reservation process by collecting essential information from users through a chatbot conversation. It uses Amazon Lex intents, slots, and slot types to structure the booking flow.

## ✨ Features

- 🛎️ Hotel booking intent using `BookHotel`
- 👤 Collects guest name and contact number
- 📅 Captures check-in and check-out dates
- 🌙 Collects the number of nights
- 👥 Captures the number of guests
- 📍 Collects the preferred hotel location
- 🛏️ Supports room type selection
- 🤖 Includes a fallback intent for unrecognized requests
- ⚙️ JSON-based bot configuration for Amazon Lex

## 🛠️ Technologies Used

- **Amazon Lex** – Conversational chatbot platform
- **JSON** – Bot, intent, slot, and locale configuration
- **AWS** – Cloud platform for chatbot development and deployment

## 📂 Project Structure

```text
Amazon-Lex-Hotel-Booking-Bot/
├── HotelBookingBot/
│   ├── Bot.json
│   └── BotLocales/
│       └── en_US/
│           ├── BotLocale.json
│           ├── Intents/
│           │   ├── BookHotel/
│           │   │   ├── Intent.json
│           │   │   └── Slots/
│           │   └── FallbackIntent/
│           └── SlotTypes/
│               └── RoomTypeSlot/
│                   └── SlotType.json
└── Manifest.json
```

## 🚀 Getting Started

1. Clone this repository:

   ```bash
   git clone https://github.com/sarumathicsc/Amazon-Lex-Hotel-Booking-Bot.git
   ```

2. Open the project folder and review the bot configuration JSON files.

3. Sign in to the AWS Management Console and open Amazon Lex.

4. Import the bot configuration using the supported Amazon Lex import process.

5. Review the bot's intents, slots, slot types, and locale settings.

6. Build and test the bot in the Amazon Lex console. Configure any required AWS permissions and integrations before deployment.

## 🌐 Project Links

- **GitHub Repository:** https://github.com/sarumathicsc/Amazon-Lex-Hotel-Booking-Bot
- **Amazon Lex:** https://aws.amazon.com/lex/
- **AWS Management Console:** https://console.aws.amazon.com/

> **Note:** The GitHub repository contains the chatbot configuration files. A live chatbot website is not included by default; a separate frontend and deployment setup would be required to publish a public booking interface.

## 🎯 Learning Outcomes

- Understanding conversational AI and chatbot design
- Working with intents, slots, and slot types in Amazon Lex
- Structuring chatbot configurations using JSON
- Exploring AWS cloud-based chatbot development

## 👩‍💻 Author

**Sarumathi H**

GitHub: [@sarumathicsc](https://github.com/sarumathicsc)

---

⭐ If you find this project useful, consider starring the repository!
