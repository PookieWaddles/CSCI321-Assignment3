# PlatTrack – SwiftUI Static UI

## Overview

PlatTrack is a PlayStation trophy tracking app designed to help users monitor their game progress and platinum achievements.

This project was developed for **CSCI 321 Assignment 3**, focusing on building a **static user interface using SwiftUI**.

---

## Features

This application includes four fully designed static screens:

### List Screen

* Displays a collection of tracked games
* Uses `ScrollView` and `ForEach`
* Custom reusable component: `GameRowView`

### Detail Screen

* Shows detailed information for a selected game
* Includes trophy breakdown and notes
* Uses `ScrollView` and `GroupBox`

### Form Screen

* Simulates adding/editing a game
* Includes:

  * TextField
  * Picker
  * Toggle
  * Slider
  * DatePicker
* Contains styled Save and Cancel buttons

### Profile Screen

* Displays user stats and profile information
* Serves as an additional custom screen

---

## Technologies Used

* Swift
* SwiftUI

---

## Key Concepts Demonstrated

* Layout using `VStack`, `HStack`
* Lists with `ScrollView` and `ForEach`
* Reusable components (View Extraction)
* SwiftUI modifiers (padding, background, styling)
* UI containers (`GroupBox`, `Section`, `Form`)
* State management using `@State`

---

## Project Structure

```
PlatTrack/
├── Models/
├── Views/
├── Components/
├── Screenshots/
└── README.md
```

---

## Screenshots

Screenshots of each screen are included in the `Screenshots/` folder:

* List Screen
* Detail Screen
* Form Screen
* Profile Screen

---

## Notes

* This project focuses on **UI layout only**
* Navigation and functionality will be implemented in future assignments

---

## Author

Manuel Corral
CSCI 321 – Spring 2026
