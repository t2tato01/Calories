# Calorie Calculator App

This Android app calculates calorie consumption based on weight, gender, and physical activity level.

## Description

This app is developed as part of an assignment for the Information Technology course at Oulu University of Applied Sciences. It demonstrates various concepts in Android development using Jetpack Compose, including:

- Dividing the app and UI into multiple composables/components.
- Using OutlinedTextField, RadioButton, and DropDownMenu for user input.
- Hoisting state up to manage data across components.
- Supporting portrait mode only.

## Composables/Components

### 1. CalorieScreen
- Main composable component that holds all UI components and data required by the application.

### 2. Heading
- Component to display a title on the screen.

### 3. WeightField
- Component for asking the person's weight.

### 4. GenderChoices
- Component to display radio buttons for selecting gender.

### 5. IntensityList
- Component for selecting the activity level from a dropdown list.

### 6. Calculation
- Component for performing the calorie calculation based on weight, intensity, and gender.

## Implementation Steps

1. Create a new empty compose activity in Android Studio.
2. Implement each component mentioned above according to the provided specifications.
3. Organize components in the CalorieScreen composable using Columns and add padding between components.
4. Hoist state up by declaring state variables in the CalorieScreen and passing them down to child components.
5. Test the app to ensure correct functionality.
6. Set screen orientation to portrait only in AndroidManifest.xml.

## Installation and Testing

1. Clone this repository.
2. Open the project in Android Studio.
3. Build and run the app on an emulator or physical device.
4. Test the app's functionality, ensuring accurate calorie calculations based on user input.

## Author

This app was developed by Jouni Juntunen for the Spring 2023 semester of the Information Technology program at Oulu University of Applied Sciences.

For any questions or further information, please contact the course instructor.
