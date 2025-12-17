# Personal Expense Tracker - Flutter App

A beginner-friendly Flutter mobile app for tracking personal expenses with local data persistence.

## Features

- ✅ Add expenses with amount, category, and description
- ✅ View scrollable list of all expenses
- ✅ See total spending summary
- ✅ Data persists between app restarts
- ✅ Clean, intuitive mobile UI

## Quick Start

1. **Install Flutter**: Follow [Flutter installation guide](https://docs.flutter.dev/get-started/install)

2. **Verify installation**:
   ```bash
   flutter doctor
   ```

3. **Get dependencies**:
   ```bash
   flutter pub get
   ```

4. **Run the app**:
   ```bash
   flutter run
   ```

## Example Usage

After running the app, you can:

1. **Add an expense**: Enter amount ($25.50), select category (Food), add description (Weekly groceries)
2. **View summary**: See total expenses and transaction count at the top
3. **Browse expenses**: Scroll through your expense history with icons and dates
4. **Restart app**: Your data will still be there thanks to local storage

## Sample Data Output

```
Total Expenses: $127.85
3 transactions

📱 App Display:
🍽️  Weekly groceries     Food • 15/12/2024        $25.50
🚗  Gas station          Transport • 14/12/2024   $45.00  
🎬  Movie tickets        Entertainment • 13/12/2024 $57.35
```

## Code Structure

- `main.dart` - Complete app with UI and logic
- `Expense` class - Data model for expenses
- `ExpenseHomePage` - Main screen with form and list
- SharedPreferences - Local data storage
- Material Design - Clean, native mobile UI

## Learning Objectives

This project teaches:
- Flutter widget composition
- State management with StatefulWidget
- Form handling and validation
- Local data persistence
- List views and navigation
- Mobile UI best practices