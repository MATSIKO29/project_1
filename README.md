<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>School Club Application System</title>
    <link rel="stylesheet" href="styles.css"><style>
      body  {
        font-family: Arial, sans-serif;
        background-image: url(/images/club1.png);
    }
    
    header {
        background-color: #333;
        color: #fff;
        padding: 20px;
        text-align: center;
    }
    
    main {
        max-width: 600px;
        margin: 0 auto;
        padding: 20px;
    }
    
    form {
        margin-bottom: 20px;
    }
    
    label {
        display: block;
        margin-bottom: 5px;
    }
    
    input[type="text"],
    input[type="email"],
    select {
        width: 100%;
        padding: 8px;
        margin-bottom: 10px;
        border: 1px solid #ccc;
        border-radius: 4px;
    }
    
    button {
        background-color: #15ea1c;
        color: white;
        padding: 10px 20px;
        border: none;
        border-radius: 4px;
        cursor: pointer;
    }
    
    button:hover {
        background-color: #000000f3;
    }
    
    #error {
        color: red;
        margin-top: 10px;
    }
    ul{
        text-align: center;
        padding: 20px;
    }
    a{
        padding: 20px;
        text-decoration: none;
        font-size: 15px;
    }
    
    </style>
</head>
<body>
    <header>
        <h1>Welcome to the School Club Application System</h1>
    </header>
    <nav>
        
        
        </div>
    </nav>
    <main>
        <form id="applicationForm">
            <label for="name">Name:</label>
            <input type="text" id="name" name="name" required><br>
            <label for="email">Email:</label>
            <input type="email" id="email" name="email" required><br>
            <label for="club">Select Club:</label>
            <select id="club" name="club" required>
                <option value="art">Art Club</option>
                <option value="music">Music Club</option>
                <option value="AERG">AERG club</option>
                <option value="Media">Media club</option>
                <option value="Yim">Yim club</option>
            </select><br>
            <label for="Reason">Reason</label>
            <input type="text" id="Reason" name="Reason" required><br>
            <button type="submit">Submit Application</button>
        </form>
        <div id="response"></div>
    </main>
   
</body>
</html>
