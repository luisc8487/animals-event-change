# React Animal Generator App

React Application that allows users to generate and display random animals with a fun interactive feature.

## Features

- A button labeled **"Click Me!"** that, when clicked, randomly selects an animal from a predefined list and displays it on the screen.
- Each animal is displayed alongside a heart icon slightly to the right of it.
- Clicking on an animal image increases the size of the heart icon, adding an interactive element to the app.

## How It Works

### 1. Random Animals Generation:

- A list of animals (`cat`, `dog`, `cow`, `gator`, `horse`, `bird`) is predefined.
- When the button is clicked, an animal is randomly selected from this list and added to the display.

### 2. Dynamic Rendering:

- The `useState` hook is used to manage the state of the animal list.
- The `map` method is used to iterate through the list of animals and render each one as a component on the client side.

### 3. Interactive Heart Icon:

- Each animal is displayed with a heart icon.
- Clicking on the animal image triggers an `onClick` event handler that increases the size of the heart icon.

## How to Run the App

1. Clone the repository to your local machine.
2. Navigate to the project directory and install dependencies using `npm install`.
3. Start the development server with `npm start`.
4. Open [http://localhost:3000](http://localhost:3000) in your browser to view the app.
