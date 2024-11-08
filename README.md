# Expense Tracker App

A Flutter-based expense tracking application that helps users efficiently monitor and manage their personal expenses.

## Features

- 📝 Add new expenses with title, amount, date and category
- 📊 Interactive chart showing expense distribution
- 📱 Responsive design for different screen sizes
- 🌓 Built-in dark mode support
- 🗑️ Swipe-to-delete functionality with undo option for accidental deletions
- 💰 Support for three expense categories:
  - Food
  - Travel
  - Leisure

## Technical Features

- **Responsive Layout**
  - Adapts between portrait and landscape orientations
  - Different layouts for screen widths above/below 600px
  
- **Theme Customization**
  - Custom color schemes for both light and dark modes
  - Consistent styling across the app
  - Platform-specific UI elements (iOS/Android)

- **Data Visualization**
  - Dynamic chart bars showing relative expense amounts
  - Category icons for easy identification
  - Gradient background effects

## Installation

1. Make sure you have Flutter SDK installed
2. Clone this repository:
```bash
git clone https://github.com/your-username/expense-tracker.git
```

3. Navigate to the project directory:
```bash
cd expense-tracker
```

4. Install dependencies:
```bash
flutter pub get
```

5. Run the app:
```bash
flutter run
```

## Project Structure

```
lib/
├── expenses.dart           # Main screen with expense management
├── main.dart              # App entry point and theme configuration
├── widgets/
│   ├── charts/           
│   │   ├── chart.dart     # Expense visualization chart
│   │   └── chart_bar.dart # Individual chart bars
│   ├── expenses_list/     
│   │   └── expense_list.dart # Scrollable expense list
│   └── new_expense.dart   # New expense input form
```

## Dependencies

- `flutter/material.dart`: Material Design widgets
- `flutter/cupertino.dart`: iOS-style widgets
- `intl`: Date and number formatting
- `uuid`: Unique ID generation

## System Requirements

- Flutter SDK ≥ 2.0.0
- iOS or Android device/emulator
- Portrait orientation support
