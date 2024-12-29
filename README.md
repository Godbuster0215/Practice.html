<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Tourist Places</title>
    <style>
        body{
            font-family: Arial, Helvetica, sans-serif;
            margin: 0;
            padding: 0;
            display: flex;
            justify-content: center;
            align-items: flex-start;
            height: 100vh;
            background-color: #f9f9f9;
        }
        .container{
            display: flex;
            flex-wrap: wrap;
            width: 90%;
            justify-content: space-between;
            margin-top: 20px;
        }
        .left-section, .right-section{
            width: 100%;
            margin-bottom: 20px;
            background-color: #ffffff;
            border: 1px solid #ccc;
            border-radius: 8px;
            padding: 15px;
            box-shadow: 0 4px 6px rgba(0, 0, 0, 0);
        }
        @media (min-width: 768px)
        {
            .left-section, .right-section{
                width: 45px;
            }
        }
            h2{
                text-align: center;
                color: #333;
            }
            ol, ul{
                margin: 0;
                padding: 0 20px;
            }
            li{
                margin: 5px 0;
            }
    </style>
</head>
<body>
    <div class="container">
        <!-- Left Section: cities-->
         <div class="left-section">
            <h2>Tourist Places</h2>
            <ol>
                <li>Paris</li>
                <li>Rome</li>
                <li>Tokyo</li>
                <li>New York</li>
            </ol>
         </div>

         <!--Right Section: Places-->
         <div class="right-section">
            <h2>Tourist Places</h2>
            <ul>
                <li>Eiffel Tower (Paris)</li>
                <li>Colosseum (Rome)</li>
                <li>Mount Fuji (Tokyo)</li>
                <li>Statue of liberty (New York)</li>
            </ul>
         </div>
    </div>
</body>
</html>
