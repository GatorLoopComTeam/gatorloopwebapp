# Gatorloop Webapp

### Pre-installation
Before you can run the project, you will need to have mysql installed on your computer, running an instance of the gatorloop database on localhost:3306.

### Installation Instructions
1. Clone the project into $GOPATH/src/github.com
2. Install Godep
    ```bash
     go get github.com/tools/godep
     ```
3. Install godep dependencies. First cd into the project, then run:
    ```bash
    godep restore
    ```
4. Install the project. Run from the project directory:
    ```bash
    go install
    ```
5. Run the executable in $GOPATH/bin.
    ```bash
    gatorloopwebapp
    ```
