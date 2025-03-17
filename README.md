# TaskClassObject/CArApp
## Introduction

This project, developed using **C#**, is part of an academic assignment. It contains class and object management based on Object-Oriented Programming (OOP).
This project is an **Avalonia WPF application** that simulates a car system.
Users can set the car's **color and model** and drive a certain distance.

## System Requirements
- **OS:** Linux / Windows
- **Framework:** Avalonia UI
- **Programming Language:** C#

## Project Structure
```
TaskClassObject/
└── CarApp/
├── Views/
│ ├── MainWindow.axaml
│ ├── MainWindow.axaml.cs
│ ├── App.axaml
│ ├── App.axaml.cs
├── Models/
│ ├── Car.cs
│ ├── ElectricCar.cs
├── Program.cs
├── CarApp.csproj
├── app.manifest
├── README.md
```

## System Requirements
- **.NET SDK** (latest version recommended)
- **Visual Studio** or any C# editor such as **Visual Studio Code**
- Operating system that supports **.NET Core/Framework**

## **How ​​to Install Git**
Use the following commands based on the operating system you:

### 🔹 **Windows**
1. Download **Git for Windows** 👉 [https://git-scm.com/download/win](https://git-scm.com/download/win)
2. Run the installer and follow the default settings
3. Check the installation with:
```sh
git --version
```

### 🔹 **Linux (Debian/Ubuntu & Arch/Manjaro)**
**Debian/Ubuntu:**
```sh
sudo apt update && sudo apt install git -y
```
**Arch/Manjaro:**
```sh
sudo pacman -S git
```
Check the installation:
```sh
git --version
```

### 🔹 **macOS**
1. Install **Homebrew** if you don't have it yet:
```sh
/bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)"
```
2. Install Git:
```sh
brew install git
```
3. Check the installation:
```sh
git --version
```

---

## **How ​​to Download & Run the Project**
You can use **Git** or **Download ZIP**.

### 🔹 **Option 1: Using Git (Recommended)**
1. Run the following command in **Terminal (Linux/macOS) or Command Prompt (Windows)**:
```sh
git clone https://github.com/AliasOmar/CarApp.git
cd CarApp
```

### 🔹 **Option 2: Download ZIP from GitHub**
1. Go to the repository 👉 [https://github.com/AliasOmar/CarApp](https://github.com/AliasOmar/CarApp)
2. Click **Code** → **Download ZIP**
3. Extract the file to a location of your choice
4. Navigate to the project folder:
```sh
cd path/to/CarApp
```

## **How ​​to Run a Project by Platform**

### 🔹 **Windows**
1. Make sure **.NET SDK** is installed
2. Open **Command Prompt (cmd) or PowerShell** and navigate to the project folder:
```sh
cd CarApp
 ```
3. Build and run projects:
 ```sh
 dotnet build
 dotnet run
 ```

### 🔹 **Linux (Debian/Ubuntu & Arch/Manjaro)**
1. Install **.NET SDK**
 ```sh
 sudo apt install dotnet-sdk-8.0 -y # Debian/Ubuntu
 sudo pacman -S dotnet-sdk # Arch/Manjaro
 ```
2. Navigate to the project folder and build:
 ```sh
 cd CarApp
 dotnet build
 dotnet run
 ```

### 🔹 **macOS**
1. Install **.NET SDK** using Homebrew:
 ```sh
 brew install dotnet-sdk
 ```
2. Navigate to the project folder and build:
 ```sh
 cd CarApp
 dotnet build
 dotnet run
 ```

## **Project Features**
**Task Management** – Add, edit, and delete tasks
**User Management** – User management in the system
**OOP Principles** – Concepts of **class, object, inheritance, encapsulation**

## **Additional Notes**
- If `dotnet` is not recognized, make sure **.NET SDK** is installed and added to `PATH`.
- If **Linux/macOS**, make sure **Avalonia UI** is installed before running the UI.
- If there is an error while building, try running:
```sh
dotnet restore
```
## Screenshots
![Run Task](https://github.com/user-attachments/assets/bf592d14-8eb4-475c-9bc4-069fa531f18e)
---
With these steps, you can run this project easily!

**Developed by:** [AliasOmar]

**Date:** 14-03-2025
