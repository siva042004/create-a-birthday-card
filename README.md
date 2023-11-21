# Exp--9-Create-a-Birthday-card-using-HTML-and-CSS
```
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Birthday Card</title>
  <style>

    .body{
        display: flex;
        align-items: center;
        justify-self: center;
    }

    .card {
        display: flex;
        flex-direction: column;
        justify-content: space-between;
        border-radius: 0.75rem;
        background-color: white;
        width: 300px;
        height: 370px;
        box-shadow: 0 4px 6px -1px rgba(0,0,0,.1),
        0 2px 4px -2px rgba(0,0,0,.1);
        margin-left: 600px;
        margin-top: 170px;
      }
      
      .header {
        position: relative;
        background-clip: border-box;
        margin-top: 1.5rem;
        margin-left: 1rem;
        margin-right: 1rem;
        border-radius: 0.75rem;
        background-color: rgb(33 150 243);
        box-shadow: 0 10px 15px -3px rgba(33,150,243,.4),0 4px 6px -4px rgba(33,150,243,.4);
        height: 14rem;
      }
      
      .info {
        border: none;
        padding: 1.5rem;
        text-align: center;
      }
      
      .title {
        color: rgb(38 50 56);
        letter-spacing: 0;
        line-height: 1.375;
        font-weight: 600;
        font-size: 1.25rem;
        margin-bottom: 0.5rem;
      }
      
      .footer {
        padding: 0.75rem;
        border: 1px solid rgb(236 239 241);
        display: flex;
        align-items: center;
        justify-content: space-between;
        background-color: rgba(0, 140, 255, 0.082);
      }
      
      .tag {
        font-weight: 300;
        font-size: .75rem;
        display: block;
      }
      
      .action {
        -webkit-user-select: none;
        -moz-user-select: none;
        user-select: none;
        border: none;
        outline: none;
        box-shadow: 0 4px 6px -1px rgba(33,150,243,.4),0 2px 4px -2px rgba(33,150,243,.4);
        color: rgb(255 255 255);
        text-transform: uppercase;
        font-weight: 700;
        font-size: .75rem;
        padding: 0.75rem 1.5rem;
        background-color: rgb(33 150 243);
        border-radius: 0.5rem;
      }
      
      
  </style>
</head>
<body>
    <div class="card">
        <div class="header"></div>
        <div class="info">
          <p class="title">Wishing you a fantastic day filled with joy and happiness</p>
          <p>May all your dreams and wishes come true!</p>
          <p>Celebrate and enjoy your special day!</p> </p>
        </div>
        <div class="footer">
          <p class="tag">#HAPPYBIRTHDAY </p>
          <button type="button" class="action">My wishes</button>
        </div>
        </div>
</body>
</html>

```

# output
![Screenshot (86)](https://github.com/21002624/Exp--9-Create-a-Birthday-card-using-HTML-and-CSS/assets/113762183/22a04e20-7f78-4b66-b2e2-c59769e13463)

