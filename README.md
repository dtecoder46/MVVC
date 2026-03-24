# MVVC
![daily.dev](https://img.shields.io/badge/daily.dev-CE3DF3?style=for-the-badge&logo=daily.dev&logoColor=white)
![Firefox](https://img.shields.io/badge/Firefox-FF7139?style=for-the-badge&logo=Firefox-Browser&logoColor=white)
![Visual Studio Code](https://img.shields.io/badge/Visual%20Studio%20Code-0078d7.svg?style=for-the-badge&logo=visual-studio-code&logoColor=white)
![HTML5](https://img.shields.io/badge/html5-%23E34F26.svg?style=for-the-badge&logo=html5&logoColor=white)
![JavaScript](https://img.shields.io/badge/javascript-%23323330.svg?style=for-the-badge&logo=javascript&logoColor=%23F7DF1E)
![CSS](https://img.shields.io/badge/css-%23663399.svg?style=for-the-badge&logo=css&logoColor=white)
![Fedora](https://img.shields.io/badge/Fedora-294172?style=for-the-badge&logo=fedora&logoColor=white)

Short for Model-View-Visualization-Controller, a full-stack paradigm for data-driven development

This template features a task tracking website for boosting productivity

## Stack Used
1. React
2. Tailwind
3. Vite
4. Bun
5. NodeJS
6. SQL
7. Python

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
