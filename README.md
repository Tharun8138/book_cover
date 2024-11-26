# Ex.06 Book Front Cover Page Design
# Date:26.11.2024
# AIM:
To design a book front cover page using HTML and CSS.

# DESIGN STEPS:
## Step 1:
Create a Django Admin project.

## Step 2:
Create an app in the Django interface.

## Step 3:
Create a folder named 'static' in the app folder.

## Step 4:
Create a new HTML file in the static folder.

## Step 5:
Write the HTML code with relevant CSS properties.

## Step 6:
Choose the appropriate style and color scheme.

## Step 7:
Insert the images in their appropriate places.

## Step 8:
Publish the website in the LocalHost.

# PROGRAM:
```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Web Development Book Cover</title>
    <style>
        * {
            box-sizing: border-box;
            margin: 0;
            padding: 0;
        }

        body {
            display: flex; 
            justify-content: center;
            align-items: center;
            height: 100vh;
            background: linear-gradient(135deg, #e2e2e2, #ffffff);
            font-family: 'Arial', sans-serif;
        }

        .book-cover {
            width: 350px;
            height: 500px;
            background: #2c3e50;
            color: white;
            padding: 20px;
            border-radius: 15px;
            box-shadow: 0 8px 30px rgba(0, 0, 0, 0.5);
            text-align: center;
            position: relative;
            overflow: hidden;
        }

        .book-title {
            font-size: 28px;
            margin-bottom: 15px;
            font-weight: bold;
            text-shadow: 2px 2px 5px rgba(0, 0, 0, 0.6);
        }

        .book-author {
            font-size: 20px;
            margin-bottom: 25px;
            color: #ecf0f1;
        }

        .book-image {
            width: 100%;
            height: 180px;
            background-image:url('harry potter.jpeg');
            background-size:cover;
            background-position: center;
            border-radius: 10px;
            margin-bottom: 20px;
            border: 2px solid #3498db;
            transition: transform 0.3s;
        }

        .book-image:hover {
            transform: scale(1.05);
        }

        .book-description {
            font-size: 15px;
            color: #bdc3c7;
            line-height: 1.5;
            margin-bottom: 20px;
        }

        .button {
            display: inline-block;
            padding: 10px 20px;
            font-size: 16px;
            color: white;
            background-color: #2980b9;
            border: none;
            border-radius: 10px;
            text-decoration: none;
            transition: background-color 0.3s ease;
        }

        .button:hover {
            background-color: #3498db;
        }

        .footer {
            position: absolute;
            bottom: 10px;
            width: 100%;
            font-size: 12px;
            color: #ecf0f1;
        }
    </style>
</head>
<body>
    <div class="book-cover">
        <div class="book-title">Harry Potter </div>
        <div class="book-author">by J.K.Rowling</div>
        <div class="book-image"></div>
        <div class="book-description">
            In the novels, Harry is described as having his father's perpetually untidy black hair, his mother's bright 
            green eyes, and a lightning bolt-shaped scar on his forehead. He is short and skinny for his age, with a thin 
            face and "knobbly" knees, and he wears Windsor glasses.
        </div>
        <div class="footer">Published: 1997</div>
    </div>
</body>
</html>
```
```
class myhandler(BaseHTTPRequestHandler):
    def do_GET(self):
        print("request received")
        self.send_response(200)
        self.send_header('content-type', 'text/html; charset=utf-8')
        self.end_headers()
        self.wfile.write(content.encode())
server_address = ('',8000)
httpd = HTTPServer(server_address,myhandler)
print("my webserver is running...")
httpd.serve_forever()
```
# OUTPUT:
![Screenshot 2024-11-26 130918](https://github.com/user-attachments/assets/ccaecd51-52fe-4777-8469-5899f9d4eea9)


# RESULT:
The program for designing book front cover page using HTML and CSS is completed successfully.
