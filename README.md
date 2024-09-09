# React Frontend Interview Test: Steam Featured Games

## Overview

This repository contains a practical frontend interview test designed to evaluate candidates' skills in React, TypeScript, and modern web development practices. The test involves building a Steam featured games list application, demonstrating proficiency in using React hooks, optimizing performance, applying CSS styles, and structuring code effectively.

## Test Structure

- **Duration**: 2 hours total
  - 1 hour for independent implementation
  - 1 hour for code review with a developer

## Project: Steam Featured Games List

Candidates are tasked with creating a Steam featured games list application with the following key features:

1. Fetch and display data from: https://store.steampowered.com/api/featured/
2. Create a dynamic title that changes every 5 seconds to another game name
3. Implement filtering based on supported operating systems
4. Display game header image as a popup when an item is clicked
5. Add a like button to each item in the list

## Technical Requirements

- React with TypeScript
- Hooks (useState, useEffect, custom hooks)
- Performance optimization techniques (React.memo, useCallback, useRef)
- Custom CSS styling (no design libraries)
- Proper code structure and organization

## Specific Requirements

1. **Data Fetching and Display**
   - Fetch data from the provided Steam API endpoint
   - Display the featured games in a list
   - Style the list using custom CSS (no design libraries)

2. **Dynamic Title**
   - Create a title component that changes every 5 seconds to display another game name from the list

3. **Filtering**
   - Implement a filter for the list based on the operating systems that support each game

4. **Popup Image**
   - When an item in the list is clicked, display the game's header image as a popup

5. **Like Button**
   - Add a like button to each item on the list

6. **React Hooks**
   - Use `useState` for managing game data and UI state
   - Use `useEffect` for data fetching and the changing title
   - Create a custom hook for managing the games data

7. **Performance Optimization**
   - Implement `React.memo` to prevent unnecessary re-renders
   - Use `useCallback` for event handlers
   - Implement `useRef` for the interval in the changing title

8. **CSS Styling**
   - Style the application using CSS modules or CSS-in-JS
   - Make the design responsive
   - Implement a dark/light mode toggle

9. **Code Structure**
   - Organize components in a logical folder structure
   - Use TypeScript interfaces for props and state
   - Implement proper error handling and loading states

## Bonus Points

- Implement virtualization for the game list to handle large datasets efficiently
- Add unit tests for components and hooks

## Evaluation Criteria

- Correct implementation of React concepts and hooks
- Efficient data fetching and state management
- Implementation of all required features
- Application of performance optimization techniques
- Quality and responsiveness of CSS styling
- Overall code structure and organization
- Completeness of the solution within the time limit

## API Note

The provided API (https://store.steampowered.com/api/featured/) may have CORS restrictions. In a real-world scenario, this would be handled server-side. For this test, candidates can use a CORS proxy or mock the API response.

## Note for Candidates

This test is designed to evaluate your skills in a practical, time-constrained scenario. Focus on demonstrating your understanding of React, TypeScript, and frontend best practices. Good luck!

---

For any questions or clarifications about this interview process, please contact the HR department.
