# todo.html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <meta name="theme-color" content="#062e3f">


    <!-- Google Font: Quick Sand -->
    <link href="https://fonts.googleapis.com/css2?family=Work+Sans:wght@300&display=swap" rel="stylesheet">

    <!-- font awesome (https://fontawesome.com) for basic icons; source: https://cdnjs.com/libraries/font-awesome -->
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/5.12.0-2/css/all.min.css" integrity="sha256-46r060N2LrChLLb5zowXQ72/iKKNiw/lAmygmHExk/o=" crossorigin="anonymous" />

    <link rel="shortcut icon" type="image/png" href="assets/favicon.png"/>
    <link rel="stylesheet" href="todo.css">
    <title>To Do Task</title>

</head>

<body>
    <div id = "header">
        
        <div class="flexrow-container">
            <div class="standard-theme theme-selector"></div>
            
        <h1 id="title">ToDOList<div id="border"></div></h1>
    </div>

  <div id="form">
        <form>
            <input class="todo-input" type="text" placeholder="Enter your task to be done...">
            <button class="todo-btn" type="submit">Add Your Task!</button>
        </form>
    </div>


  <div id="myUnOrdList">
        <ul class="todo-list">
            
        </ul>
    </div>
    <script src="todo.js" type="text/javascript"> </script>
</body>
</html>
