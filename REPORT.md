# 📌 Rättningsrapport – fed24d-the-last-todos-ellinorjohansson

## 🎯 Uppgiftens Krav:
# 📋The Last Todo

A simple and user-friendly Todo application built with React and TypeScript.
It allows users to add, sort, complete, and view tasks. All todos are saved in the browser's local storage, so your tasks persist even after refreshing the page.

## Table of Contents

- [Features](#features)
- [Tech Stack](#tech-stack)
- [Installation](#installation)
- [Screenshots](#screenshots)
- [Authors](#authors)

## ✨Features
✅ Add new tasks with checkbox support

📥 Store todos in localStorage

🔁 Toggle task completion

📂 Sort tasks alphabetically (A–Z / Z–A)

📃 View active and completed tasks in separate lists

💬 Show custom messages when lists are empty

🎨 Responsive and styled with Tailwind CSS

## Tech Stack

- ![Vite](https://img.shields.io/badge/Vite-%23646CFF.svg?style=for-the-badge&logo=vite&logoColor=white)
- ![React](https://img.shields.io/badge/React-%2361DAFB.svg?style=for-the-badge&logo=react&logoColor=black)
- ![HTML5](https://img.shields.io/badge/HTML5-%23E34F26.svg?style=for-the-badge&logo=html5&logoColor=white)
- ![TypeScript](https://img.shields.io/badge/TypeScript-%23007ACC.svg?style=for-the-badge&logo=typescript&logoColor=white)
- ![TailwindCSS](https://img.shields.io/badge/TailwindCSS-%2338B2AC.svg?style=for-the-badge&logo=tailwind-css&logoColor=white)

## Installation

Install fed24d-the-last-todos-ellinorjohansson locally with npm

```bash
# Clone this repository
$ git clone https://github.com/Medieinstitutet/fed24d-the-last-todos-ellinorjohansson

# Go into the repository
$ cd fed24d-the-last-todos-ellinorjohansson

# Install dependencies
$ npm install

# Run app
$ npm run dev
```

## Screenshots

### Desktop

![Screenshot desktop](/src/assets/screenshot/todo_screenshot.png)

## Authors

- [@ellinorjohansson](https://www.github.com/ellinorjohansson)






## (Tar bort efter betyg är satt)

[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-22041afd0340ce965d47ae6ef1cefeee28c7c493a6346c4f15d667ab976d596c.svg)](https://classroom.github.com/a/Tfc19Mhg)
# Inlämningsuppgift Todo

I denna inlämningsuppgift kommer ni att skapa er egen todo-lista.
Sidan skall visa ett antal punkter som skall göras. Dessa skall då komma upp på skärmen i form av en lista. När uppgiften är slutförd skall användaren kunna markera uppgiften som slutförd och uppgiften skall då tas bort från listan.

## Betyg G

- Skapa en hårdkodad lista med punkter att göra (hitta på egna punkter, dessa skall inte bara vara en text)
- Presentera listan på skärmen, helst med lite kontroll. Detta betyder i en html-struktur t.ex. i en ul/li-lista
- Implementera klickhändelse för att hantera borttagandet av en todo.
- Todo markeras som klar på skärmen och markeras som klar i javascript-listan.
- Ni behöver använda localStorage så att listan inte börjar om från början varje gång sidan används.
- Ni behöver använda er av en komponent.
- Ni behöver använda er av state med en lista med objekt.

## Betyg VG

- Alla punkter under G
- Kunna visa även klara händelser och klicka tillbaka den så att de blir oklara igen.
- Skapa ett formulär som tillåter att en användare skapar nya todos efterhand.
- Kunna sortera ordningen på dina todos.
- Implementera ett valfritt grafiskt ramverk, t.ex. tailwind eller material ui.
- Ni behöver ha minst tre komponenter.
- Ni måste använda Lifting State Up.

## Allmänt

Projektet ni har är ett vite-projekt. D.v.s. ni måste köra:

```shell
npm i
```

och

```shell
npm run dev 
```

för att köra projektet.

- Det finns många sätt att lösa denna uppgift på. Om ni känner er osäkra på någonting, fråga hellre någon gång för mycket så att ni känner er säkra på vad ni utvecklar.
- Ni får gärna ändra strukturen i projektet, detta är bara en grund.
- Börja med att planera ert arbete, börja inte med Visual Studio Code, även om det är lockande.
- Gör ert bästa att inte stressa. Lättare sagt än gjort, jag vet. Men ingen mår bättre av att stressa.
- Ha roligt, skratta när det blir fel och fortsätt att vara nyfiken :)


## 🔍 ESLint-varningar:


## 🏆 **Betyg: VG**
📌 **Motivering:** Studentens lösning uppfyller både G- och VG-kraven i uppgiften. Applikationen implementerar React och TypeScript på ett välstrukturerat och effektivt sätt, inklusive användandet av komponenter och hantering av state. Lifting State Up har implementerats, liksom sortering och visning av både aktiva och slutförda todos. Användandet av localStorage säkerställer att todos sparas mellan siduppdateringar.

💡 **Förbättringsförslag:**  
För att ytterligare förbättra koden kan felhantering läggas till, särskilt när det gäller interaktionen med localStorage. Man kan också överväga att implementera någon form av ID- eller task-kollisionskontroll vid skapandet av nya todos för att hantera eventuell dubblettproblematik.