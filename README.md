# oibsip_3

<!==This code is create webpage for Todo List ==>
<!==This code is done by Siripuram Rahul ==>
<!DOCTYPE html>
<html>

<head>
  <title>Todo List</title>
  <link rel="stylesheet" type="text/css" href="./style.css">
</head>

<body>
  <h1><u>To-do List</u></h1>
  <fieldset style="width:600px; margin-left:27%;border: 5px solid black;"><div id="app">
    <div class="s">
      <input type="text" id="taskInput" placeholder="Enter a task">
      <button onclick="addTask()">Add Task</button>
    </div>
    <div class="j">
     <h2> Tasks To Perform:-- </h2>
      <ul id="taskList"></ul>
    </div>
  </div>
</fieldset>
  <script src="./script.js"></script>
</body>

</html>
