## Getting Started with the To-Do List App

This is the readme file for the To-Do List application, a simple app built with HTML, JavaScript, and potentially Docker (optional).

### Cloning the Repository

To get started, you'll need to clone this repository to your local machine. Here's how:

1. Open your terminal or command prompt.
2. Navigate to the directory where you want to clone the repository.
3. Run the following command:

```bash
git clone https://github.com/Kosisookeke/todo_list.git
```

This will download the project files to your local machine.

### Running the Application (Without Docker)

1. Navigate to the project directory:

```bash
cd todo_list
```

2. Open `index.html` in your web browser. You can do this by either dragging the file into your browser window or using the following command in your terminal (assuming you have a program that opens html files):

```bash
open index.html
```

This will launch the To-Do List application in your browser.

### Running the Application (Using Docker - Optional)

**Prerequisites:**

- Docker installed on your machine. You can find instructions for installing Docker on [https://www.docker.com/](https://www.docker.com/).

1. Build the Docker image:

```bash
docker build -t todo_list_app .
```

2. Run the Docker container:

```bash
docker run -p 8080:80 todo_list_app
```

This will build a Docker image for the application and run a container based on that image. The `-p 8080:80` option maps port 8080 on your host machine to port 80 inside the container, allowing you to access the application in your browser at `http://localhost:8080`.

**Note:** Using Docker is an optional way to run the application. If you're not familiar with Docker, you can simply run the application without it as described in the previous section.

### Usage

The To-Do List application allows you to add, remove, and mark tasks as complete. You can interact with the application through the provided HTML elements and JavaScript functionalities.

**Features:**

- Add new tasks to the list.
- Mark tasks as completed.
- Remove tasks from the list.

**Additional Notes:**

- This is a basic To-Do List application and may not have all the features you might expect from a more complex application.
- Feel free to modify the code to add new features or customize the application to your liking.
