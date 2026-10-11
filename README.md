# Healthcare Portal — Blue Team Security Project

A full-stack healthcare web application that demonstrates **7 real-world web vulnerabilities** and their fixes across two switchable versions — a **Vulnerable** version where all attacks succeed, and a **Safe** version where every attack is blocked.

---

##  Use Case

A **healthcare portal** where patients can:
- Log in to their account
- Search medical patient records
- Post comments on their care
- Update their profile email

The application is deliberately built in two versions to allow direct, hands-on comparison of vulnerable and secure implementations.

---

## Tech Stack

| Layer | Technology |
|-------|-----------|
| **Backend** | Node.js + Express |
| **Database** | MySQL (real queries — no ORM in the vulnerable version) |
| **Frontend** | HTML5 + CSS3 + Vanilla JavaScript |
| **Auth** | Express-session with cookies |
| **CSRF Defense (Safe)** | `csurf` + SameSite cookies |
| **HTTP Headers (Safe)** | `helmet` |
