<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>ToDo List</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            background-color: #f4f4f4;
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }

        #container {
            max-width: 600px;
            margin: 50px auto;
            background-color: #fff;
            padding: 20px;
            border-radius: 8px;
            box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
        }

        h1 {
            text-align: center;
            color: #333;
        }

        #taskInput {
            width: 100%;
            padding: 10px;
            box-sizing: border-box;
            margin-bottom: 10px;
        }

        #taskList {
            list-style: none;
            padding: 0;
        }

        .task {
            display: flex;
            justify-content: space-between;
            align-items: center;
            padding: 10px;
            border: 1px solid #ddd;
            border-radius: 4px;
            margin-bottom: 8px;
            background-color: #fff;
        }

        .task button {
            background-color: #ff6b6b;
            color: #fff;
            border: none;
            padding: 8px;
            cursor: pointer;
            border-radius: 4px;
        }

        .task button:hover {
            background-color: #ff4f4f;
        }
    </style>
</head>

<body>
    <div id="container">
        <h1>ToDo List</h1>
        <input type="text" id="taskInput" placeholder="Add a new task...">
        <ul id="taskList"></ul>
    </div>

    <script>
        // You can add your JavaScript code for handling tasks here
    </script>
</body>

</html>
