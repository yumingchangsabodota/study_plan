# **Go Programming Language Study Plan**

## **1️⃣ Section: Go Fundamentals**
### **Topics:**
- Introduction to Go: Why Go?
- Setting up Go (`go install`, `GOPATH`, `GOBIN`)
- Go project structure and module management
- Variables, constants, and data types
- Functions and control flow (`if`, `switch`, `for` loops)


### **Hands-on Project:**
##### ✅ Done [https://github.com/yumingchangsabodota/go_lang/tree/master/to_do_list]
**Build a Simple To-Do List CLI App**
- Implement a command-line to-do list where users can add, remove, and view tasks.
- Store tasks in a txt file for persistence.
- Implement a simple menu-driven interface.

---

## **2️⃣ Section: Structs, Interfaces, and Methods**
### **Topics:**
- Structs and Methods (`struct` and receiver functions)
- Interfaces and polymorphism in Go
- Embedding and composition
- Error handling (`error` interface, custom errors)

### **Hands-on Project:**
##### ✅ Done  [https://github.com/yumingchangsabodota/go_lang/tree/master/vehicle_inventory]
**Build a Vehicle Inventory System**
- Create a `struct` for vehicles with fields like `Make`, `Model`, and `Year`.
- Implement methods to add, remove, and list vehicles.
- Use interfaces to handle different vehicle types (e.g., cars, trucks, motorcycles).

---

## **3️⃣ Section: Concurrency in Go**
### **Topics:**
- Goroutines and how they work
- Channels: Unbuffered vs Buffered channels
- `sync.WaitGroup` and `sync.Mutex`
- Worker pools and pipeline concurrency patterns

### **Hands-on Project:**
**Build a Concurrent Stock Price Fetcher**
- Fetch stock prices for multiple companies concurrently from a free API.
- Use goroutines and channels to handle multiple requests.
- Display results in a table format.

---

## **4️⃣ Section: File Handling & Networking**
### **Topics:**
- Reading and writing files (`os` and `io` packages)
- HTTP requests (`net/http` package)
- JSON and XML parsing (`encoding/json`, `encoding/xml`)
- Handling APIs and web responses

### **Hands-on Project:**
**Build an Automated Log File Cleaner**
- Read and parse log files from a directory.
- Identify and delete logs older than a set threshold.
- Allow users to configure the retention period.

---

## **5️⃣ Section: Web Development with Go**
### **Topics:**
- Introduction to `net/http` for web servers
- Handling HTTP requests and responses
- Working with templates (`html/template`)
- Middleware and routing (`gorilla/mux` or `chi`)

### **Hands-on Project:**
**Build a Job Posting Board**
- Create a web app where users can post job listings.
- Display job postings with filtering options.
- Store job data in a database.

---

## **6️⃣ Section: Database Integration**
### **Topics:**
- Using SQL databases with `database/sql` and `gorm`
- Connecting to PostgreSQL/MySQL
- Executing queries and handling transactions
- Introduction to NoSQL databases (Redis, MongoDB)

### **Hands-on Project:**
**Build an Employee Attendance Tracker**
- Store employee check-in/check-out records in a database.
- Implement a web API for logging attendance.
- Generate daily attendance reports.

---

## **7️⃣ Section: Advanced Go Topics**
### **Topics:**
- Reflection and Type Assertions
- Writing tests in Go (`testing` package, `go test`)
- Benchmarking and performance optimization
- Memory management and garbage collection

### **Hands-on Project:**
**Build a Custom JSON Parser**
- Create a tool that parses JSON files and extracts specific fields.
- Implement error handling for invalid JSON data.
- Benchmark performance with large files.

---

## **8️⃣ Section: Deploying Go Applications**
### **Topics:**
- Compiling Go binaries for different platforms
- Building and deploying Go applications with Docker
- CI/CD pipelines for Go applications
- Cloud deployment (AWS Lambda, GCP, or DigitalOcean)

### **Final Hands-on Project:**
**Build and Deploy an RPC Server**
- Develop a Remote Procedure Call (RPC) server.
- Implement methods that clients can invoke remotely.
- Ensure secure communication and authentication.
- Deploy the server using Docker and Kubernetes.

---


