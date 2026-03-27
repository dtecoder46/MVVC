# MVVC

Short for Model-View-Visualization-Controller, a full-stack paradigm for data-driven development

This template features a task tracking website for boosting productivity

⚠️ This project is still in progress, any feedback is appreciated

## Planned Tech Stack
![React](https://img.shields.io/badge/react-%2320232a.svg?style=for-the-badge&logo=react&logoColor=%2361DAFB)
![TailwindCSS](https://img.shields.io/badge/tailwindcss-%2338B2AC.svg?style=for-the-badge&logo=tailwind-css&logoColor=white)
![Vite](https://img.shields.io/badge/vite-%23646CFF.svg?style=for-the-badge&logo=vite&logoColor=white)
![Bun](https://img.shields.io/badge/Bun-%23000000.svg?style=for-the-badge&logo=bun&logoColor=white)
![NodeJS](https://img.shields.io/badge/node.js-6DA55F?style=for-the-badge&logo=node.js&logoColor=white)
![MySQL](https://img.shields.io/badge/mysql-4479A1.svg?style=for-the-badge&logo=mysql&logoColor=white)
![Python](https://img.shields.io/badge/python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54)

# Overall structure

1. React
    1. Enter and add a task
        1. Displayed in the webpage
        2. Task is added to an array
        3. Array is pushed to local storage
    2. Mark task as done
        1. Choose which task (task number) to mark as done
            1. If invalid task number (0 or lower, length of array or higher), display error message
        2. When submitted, the array entry at index task_num - 1 is removed
            1. Array is pushed to local storage
            2. "Tasks done" counter is incremented by 1 and pushed to local storage
                1. Counter is displayed on the webpage
    3. When midnight
        1. Send daily task count to NodeJS
        2. Reset count on webpage to 0 and update in local storage
2. NodeJS
    1. 
3. SQL
4. Python

# Sources
[HTML Web Storage](https://www.w3schools.com/html/html5_webstorage.asp)

[Fireship Vanilla JS ToDo App](https://youtu.be/cuHDQhDhvPE?si=UFjolhSwc55hdoCU)

[JS Array Splice](https://www.w3schools.com/jsref/jsref_splice.asp)
