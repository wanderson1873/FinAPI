<div align="center">

# FinAPI

[![Learning project](https://img.shields.io/badge/📚_learning_project-Rocketseat_Ignite_%C2%B7_2021-2563EB?style=for-the-badge)](https://rocketseat.com.br/)

**A small banking API: open an account, deposit, withdraw and read the statement.**

![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black)
![Node.js](https://img.shields.io/badge/Node.js-339933?style=flat-square&logo=nodedotjs&logoColor=white)
![Express](https://img.shields.io/badge/Express-000000?style=flat-square&logo=express&logoColor=white)

</div>

---

## 📌 About

Accounts are identified by CPF. The API covers creating, updating and deleting an account, deposits, withdrawals with balance checks, the full statement, the statement for a date, and the balance. Built during Rocketseat's **Ignite** Node.js track.

## 🧠 What I practiced

- **REST design** for a small domain: `/account`, `/deposit`, `/withdraw`, `/statement` and `/balance`.
- **Express middlewares** to find the account from a header and reject unknown customers.
- **Business rules in the API:** no duplicate CPF and no withdrawal above the balance.

## 🚀 Run locally

You need Node.js and Yarn (or npm).

```bash
git clone https://github.com/wanderson1873/FinAPI.git
```

Runs on `http://localhost:3333`:

```bash
cd FinAPI/backend
yarn install
yarn dev
```

---

<div align="center">

**Wanderson Oliveira** · Websites & AI solutions that bring businesses more customers

[![derson.cloud](https://img.shields.io/badge/derson.cloud-2563EB?style=flat-square&logo=googlechrome&logoColor=white)](https://derson.cloud)
[![Email](https://img.shields.io/badge/Email-EA4335?style=flat-square&logo=gmail&logoColor=white)](mailto:wanderson1873@gmail.com)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=flat-square&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/wanderson1873/)
[![WhatsApp](https://img.shields.io/badge/WhatsApp-25D366?style=flat-square&logo=whatsapp&logoColor=white)](https://wa.me/17816664150)

<sub>Released under the [MIT License](LICENSE).</sub>

</div>
