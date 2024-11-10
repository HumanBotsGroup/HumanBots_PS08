# GreenBite: Food Waste Management

GreenBite is a web application designed to help users reduce food waste at home and facilitate food donation to those in need. The app allows users to log food items with expiry dates, receive alerts to consume items before they spoil, and provides recipes for leftovers. Additionally, it features a donation option for users to list surplus food they want to donate, connecting them with local shelters or food banks for pickups or drop-offs.

## Objective

The primary goal of GreenBite is to:

- Help users minimize food waste by tracking the expiry dates of items.
- Provide useful recipes to repurpose leftovers.
- Enable users to donate surplus food to those in need, supporting local shelters and food banks.

## Features

- **Food Log**: Users can log food items, including their names, quantities, and expiry dates.
- **Expiry Alerts**: Get timely alerts when food items are nearing their expiry dates to avoid spoilage.
- **Leftover Recipes**: Receive recipe suggestions based on available leftover ingredients to reduce food waste.
- **Surplus Food Donation**: Users can list food they wish to donate, and the app will connect them with local shelters or food banks.
- **Pickup and Drop-off Coordination**: Facilitate the pickup or drop-off of surplus food to the designated donation center.

## Technologies Used

- **Frontend**: React, Tailwind CSS for styling
- **Bundler**: Vite
- **State Management**: Context API (React)
- **Configuration**: Babel, PostCSS
- **Utilities**: Drizzle (for database connections or ORM as needed)
- **Notifications**: Could integrate push notifications or email alerts for expiry date reminders
- **Optional APIs**: Integration with third-party APIs for food donation shelters or food banks (optional)

## Installation

To run the app locally:

1. Clone the repository and navigate to the project directory.

2. Install the dependencies using:
   ```bash
   npm install
   ```

3. Configure the `.env` file with the necessary environment variables (e.g., API keys, database URIs, etc.).

4. Start the application using:
   ```bash
   npm run dev
   ```

5. Open the app in your browser at `http://localhost:5173`.

## Usage

### Food Logging
- To log food, click on the "Add Food" button, enter the item name, quantity, and expiry date, and click "Save". The food will be added to your log.

### Expiry Alerts
- The app will automatically send alerts when a food item is close to its expiry date (configurable settings for alert timings).

### Leftover Recipes
- Based on the food items in your log, the app will suggest recipes to utilize any leftovers or soon-to-expire food.

### Food Donation
- Go to the "Donate" section, list any surplus food you want to donate, and select the food bank or shelter you want to donate to.
- The app will coordinate pickup/drop-off details.


Thank You!
### Creators: HumanBots:
-Devika Bongarde
-Vinayak Kadate
-Prithviraj Patil
-Avadhoot Gurav
-Trupti Varma
