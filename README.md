# ArcList ᚬᚱᚴᛚᛁᛋᛏ
ArcList is a minimalist, intuitive to-do app built with Go and HTMX. The app's primary purpose is to explore and showcase the potential of HTMX for seamless, modern front-end interactivity, paired with Go's robust back-end capabilities.

## Features
- **Real-time Task Updates**: Thanks to HTMX, ArcList enables quick, seamless task interactions without full-page reloads.
- **Simple and Clean Interface**: A focus on efficiency and minimalism ensures only the essentials are front and center.
- **Go-Powered Back-End**: Built with Go for high performance, stability, and simplicity.
 
## Setting up the Project and Contributing to the Project

Prerequisites
 - [Go](https://go.dev/doc/install)

To setup the project locally follow the steps:
1. Fork the project.
2. Clone your forked repository onto your local machine.

    ```
    git clone https://github.com/<YOUR-GITHUB-USERNAME>/ArcList.git
    ```
4. Add the upstream repository

    ```
    cd ArcList
    git remote add upstream https://github.com/acmpesuecc/ArcList.git
    git pull upstream main
    ```
6. Add a new branch ( THIS STEP IS OPTIONAL and you can continue to work on the main branch )

    ```
    git checkout -b <NEW-BRANCH-NAME>
    ```
8. Now to Run the application, Go to the repository root directory

    ```
    go run main.go
    ```

> [!NOTE]  
> It might ask for permission, please 'Allow'
    
10. Naviagte to http://localhost:8080/
11. After making changes to your codebase, stage and push the code to your forked repo
   
    ```
    git add <\files_that_you_made_changes>
    git commit -m "<COMMIT-MESSAGE>"
    git push -u origin <BRANCH-NAME>
    ```
   
11. Finally have Fun 😃 and Happy Contributing !! 🥳
