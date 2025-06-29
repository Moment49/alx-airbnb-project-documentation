## 🧭 **Flowchart: User Registration Workflow**

### 🔄 Flowchart Steps:

Here’s what we’ll represent in the flowchart:

1. **User submits registration form** (name, email, password, role)
2. **Backend receives request**
3. **Validate input data**

   * If invalid → return error response
4. **Check if email already exists**

   * If exists → return “email already in use”
5. **Hash password securely (bcrypt/argon2)**
6. **Create user record in database**
7. **Generate JWT token**
8. **Send success response with token**

---

## 📁 File Details for Repo

```
alx-airbnb-project-documentation/
└── flowcharts/
    ├── data-flow-diagram.png     # Final PNG flowchart export
    └── README.md                 # Optional: explain the diagram purpose
```
