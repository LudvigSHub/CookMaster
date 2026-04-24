# 🍳 CookMaster

CookMaster is a desktop recipe management application built with WPF and the MVVM pattern in C#.

The project focuses on clean structure, separation of concerns, and maintainable UI logic.

### 🚀 Features
### 📖 View and manage recipes
### 🧾 Structured ingredient handling
### 🔄 Data binding with real-time UI updates
### 🧠 Clear separation between UI and logic using MVVM
### 🎯 Reusable components such as converters and services


## 🏗️ Architecture

The project follows the MVVM (Model-View-ViewModel) pattern.

```text
CookMaster
├── Models - Data structures and domain models
├── Views - XAML user interface
├── ViewModels - UI logic and state handling
├── Services - Application logic and helpers
├── Infrastructure - Base classes and utilities
├── Converters - Value converters for UI binding
└── Resources - Styles, themes, and assets
```

## Key Concepts
- Data Binding between View and ViewModel
- INotifyPropertyChanged for reactive UI updates
- Commands (ICommand) for user interactions
- Value Converters for UI transformations
  
## 🛠️ Tech Stack
- Language: C#
- Framework: WPF (.NET)
- Architecture: MVVM
- UI: XAML

## ⚙️ Getting Started
1. Clone the repository

git clone https://github.com/LudvigSHub/CookMaster.git

cd CookMaster

2. Open in Visual Studio
Open CookMaster.sln
Set CookMaster as startup project

4. Run the application
Press F5
Or click Run

## 🧠 Purpose of the Project

This project was created to practice:
- Building desktop applications with WPF
- Applying the MVVM design pattern
- Structuring a scalable and maintainable codebase
- Working with data binding and UI state management

## 📌 Notes
- This is an early project in my development journey
- Later projects show more advanced backend architecture and full-stack systems
- The focus here is on UI structure, MVVM, and clean separation of concerns
