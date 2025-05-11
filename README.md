# Banking-JEE-Web-App
# 🏦 Banking JEE App

This is a fully functional Java EE (J2EE) web application built using EJBs, JPA, Servlets, and JSP, hosted on GlassFish Server with Derby as the database. It supports role-based access for **Clients**, **Bankers**, and **Admins**.

---

## 💡 Features

- ✅ Role-based login (Client, Banker, Admin)
- ✅ Secure architecture with 3-tier design
- ✅ JPA (with JPQL) and EJB (stateless session beans)
- ✅ Entity classes and Facade pattern with AbstractFacade
- ✅ Uses JDBC Derby pool
- ✅ GlassFish integration (NetBeans-friendly)

---

## 🧱 Technologies

- Java EE 8
- EJB (Session Beans)
- JPA (with JPQL)
- JSP/Servlet
- Derby Database (via JDBC Pool)
- GlassFish Server
- NetBeans IDE

---

## 📁 Project Structure

```bash
BankEJBModule/
├── za.ac.tut.entities/       # Entity classes (e.g. Customer)
├── za.ac.tut.bl/             # Business logic (AbstractFacade, CustomerFacade)
├── META-INF/persistence.xml

BankWebApp/
├── za.ac.tut.web/            # Servlets
├── web/index.jsp             # Frontend
├── WEB-INF/web.xml           # Deployment descriptor


