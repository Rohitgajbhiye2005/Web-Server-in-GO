# Web Server in Go

This is a simple web server built using **Golang**. It handles HTTP requests, serves static files, and processes form submissions.

## 🚀 Features
- Serves static files from the `/static` directory.
- Handles dynamic routes like `/hello` and `/form`.
- Parses form data and responds with user input.

## 📂 Project Structure

## 🛠️ Installation & Setup

### **1. Clone the repository**
```sh
git clone https://github.com/Rohitgajbhiye2005/Web-Server-in-GO.git
cd Web-Server-in-GO
go run main.go
This will start the server at http://localhost:8080.

📜 API Endpoints
Route	Method	Description
/	GET	Serves static files
/hello	GET	Returns "Hello, it's Rohit!"
/form	POST	Accepts form data and responds
📝 Example Form Submission
Open static/form.html in your browser.

Fill out the form and submit.

The server will process the request and display the submitted data.

💡 Future Enhancements
Add a database to store form submissions.

Implement logging for debugging.

Improve error handling.

📜 License
This project is open-source under the MIT License.

