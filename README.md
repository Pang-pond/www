https://github.com/lolboyTH

Explain in detail which files need to be created and how to write the code completely.
-

Act as a senior backend engineer and explain the solution step-by-step.

For the following problem, provide a complete implementation guide.

Include:

1. Concept explanation (what this technology is and why it is used)
2. Project setup and installation commands
3. Folder / project structure
4. All files that must be created
5. Complete code for each file
6. Explanation of what each part of the code does
7. How to run and test the program
8. Example request and response
9. Common mistakes and best practices

Make the explanation beginner-friendly but technically accurate so it can be followed during an exam.

Problem:
[PUT THE QUESTION HERE]
```

---

# ตัวอย่างใช้กับโจทย์ในสไลด์

## 1️⃣ REST API CRUD + Search + Sorting + Swagger
```text
Act as a senior backend engineer and explain step-by-step how to build a CRUD REST API for a Book management system using Node.js Express.

Requirements:
- Proper HTTP status codes
- Search and sorting functions
- Swagger documentation
- No database required (use in-memory data)

Include:
- project setup
- folder structure
- full code for each file
- explanation
- example requests
```
# 2️⃣ JSON-RPC Smart Home
Explain step-by-step how to implement a JSON-RPC 2.0 server in Node.js using the jayson library.

Requirements:
- Method toggleSmartLight
- Parameters: roomName (string), brightness (integer)
- Return message: "Light in [roomName] set to [brightness]%"

Include:
- project setup
- folder structure
- full server code
- example request and response
```



3️⃣ gRPC Streaming
Explain step-by-step how to build a gRPC streaming service in Node.js using Protocol Buffers.

Requirements:
- service CryptoService
- rpc streamPrices returns stream PriceUpdate
- server pushes random price every 500ms
- client prints "Current BTC Price: $value"

Include:
- .proto file
- server code
- client code
- setup instructions
```



# 4️⃣ Prisma Lab (Author / Book / Category)

Explain step-by-step how to use Prisma to:

1. Create an Author named "J.K. Rowling"
2. Create a Book titled "Harry Potter and the Philosopher's Stone" linked to the author
3. Create a Category named "Fantasy"
4. Update the book to connect it to the Fantasy category

Include:
- prisma schema explanation
- full Node.js code
- nested create
- connect relation
```

---

# 5️⃣ JWT Authentication (โจทย์สุดท้าย)
Explain step-by-step how to implement JWT authentication in a Node.js Express API.

Requirements:
- POST /login
- if username = admin -> role admin
- otherwise role user
- authentication middleware
- authorization middleware (admin only)
- protected route /admin-only

Include:
- project setup
- folder structure
- full code
- example request and response
```

# PROMPT สั้นสุด (จำง่ายตอนสอบ)

จำแค่ประโยคนี้พอ

```text
Explain step-by-step with project structure, full code for each file, setup instructions, and example requests.
```

แล้วใส่โจทย์ต่อท้าย

