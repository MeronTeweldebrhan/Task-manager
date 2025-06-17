# Task Manager

A simple React + TypeScript application for managing tasks with filtering, status updates, priority changes, and deletion.

## Features

* View a list of tasks with title, description, status, priority, and due date.
* Filter tasks by status (pending, in-progress, completed) and priority (low, medium, high).
* Update task status and priority via dropdowns.
* Delete tasks.
* Responsive UI with feedback for no matching tasks.

## Tech Stack
* Frontend: React, TypeScript
* Styling: CSS (customize as needed)
* Build Tool: Vite 
 
 ## Installation

 ```
 git clone https://github.com/MeronTeweldebrhan/Task-manager
 cd task-manager
 npm install
 npm run dev

 ```
 ## Project Structure
 ```
src/
├── components/
│   ├── TaskList.tsx       # Renders the list of tasks and applies filters
│   ├── TaskFilter.tsx     # Filter dropdowns for status and priority
│   └── TaskItem.tsx       # Displays a single task with update/delete options
├── App.tsx                # Main app component managing task state and handlers
├── types.ts               # TypeScript interfaces .
```
