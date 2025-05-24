# React Pomodoro Timer

A minimalist Pomodoro timer application built with React, TypeScript, and Vite. This project helps users manage their time effectively by breaking down work into focused intervals, traditionally 25 minutes in length, separated by short breaks.

## Features

* **Pomodoro Timer**: Set and track work intervals.
* **Task Input**: Name your current task.
* **Customizable Duration**: Adjust the duration of the work interval between 5 and 60 minutes.
* **Start/Stop/Interrupt**: Full control over the current cycle.
* **History Log**: View a list of all completed and interrupted cycles, along with their duration, start time, and status.
* **Persistent State**: Your cycles and current timer state are saved locally, so you won't lose your progress on refresh.
* **Responsive Design**: The application adjusts to different screen sizes.
* **Theming**: Utilizes `styled-components` for a consistent and customizable visual theme.

## Technologies Used

* **React**: A JavaScript library for building user interfaces.
* **TypeScript**: A typed superset of JavaScript that compiles to plain JavaScript.
* **Vite**: A fast build tool that provides a lightning-fast development experience.
* **Styled Components**: For writing CSS in JavaScript to style components.
* **React Router DOM**: For declarative routing in React applications.
* **React Hook Form**: For efficient and flexible form validation.
* **Zod**: A TypeScript-first schema declaration and validation library.
* **Immer**: To work with immutable states in a more convenient way within reducers.
* **Phosphor React**: For a flexible icon family.
* **Date-fns**: A comprehensive JavaScript date utility library.
* **ESLint**: For identifying and reporting on patterns found in ECMAScript/JavaScript code.

## Getting Started

To get a local copy up and running, follow these simple steps.

### Prerequisites

* npm
    ```bash
    npm install -g npm
    ```

### Installation

1.  Clone the repo:
    ```bash
    git clone [https://github.com/enzotonatto/react-pomodoro-timer.git](https://github.com/enzotonatto/react-pomodoro-timer.git)
    ```
2.  Navigate to the project directory:
    ```bash
    cd react-pomodoro-timer
    ```
3.  Install NPM packages:
    ```bash
    npm install
    ```

## Usage

To run the application in development mode:

```bash
npm run dev
