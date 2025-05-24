# 🏥 Hospital Management System – Angular UI

A modern and role-based hospital management web application built using **Angular 14**, featuring secure login, patient CRUD, diagnostic details, appointment scheduling, and medicine tracking — designed for doctors and admins.

---

## 🚀 About Me

I'm a full stack developer with a strong interest in crafting responsive, intuitive web applications.  
👨‍💻 I am passionate about Web Development & enjoy learning new things and working on real-world projects that create impact.

---

## 📌 Project Purpose

This project showcases a clean and responsive **frontend-only** Angular dashboard for healthcare management. It is adapted and personalized from an open-source full-stack application to focus on frontend development and UI enhancement.

---

## 💡 Features

- 🔐 Role-based login for Doctor and Admin
- 🧑‍⚕️ Doctor Dashboard:
  - View and update patient diagnostics
  - Add and manage medicines
- 👩‍💼 Admin Dashboard:
  - View appointments
  - Add/update appointment records
- 🔍 Search patient by name
- ⚙️ Clean Angular routing and form validation

---

## 🛠️ Tech Stack

| Layer       | Tools                           |
|-------------|----------------------------------|
| Frontend    | Angular 14, TypeScript, HTML, CSS |
| UI Library  | Angular Material (optional)       |
| Backend     | Spring Boot + Java (not included here) |
| Database    | MySQL (used in backend)    

# Hospital Management System Project

The Hospital Management Application is built with Angular and Springboot. The primary objective of the project is to design and develop a hospital management website which can be accessed by the doctor and admin. 

The doctor has the authority to view the current list of patients who are under treatment, including their diagnostic details. The doctor can perform CRUD operations with the patients in his dashboard. Doctor has the access to add and maintain the medicine list in his dashboard.

Admin dashboard displays the current patient list excluding few sensitve diagnostic details. Admin has the access to maintain the appointment list in his dashboard. Admin can also perform CRUD operations in the appointment list. 

Sprinboot is used as a middleware for database connection and api generation. MySQL8 workbench is used as the database. Angular 14 is used as the frontend framwork for component generation, routing, statemanagement, api calling for all the components. This project was generated with [Angular CLI](https://github.com/angular/angular-cli) version 14.0.4.

📦 **Clone this Project**
To get started locally, clone this repository using:

```bash
git clone https://github.com/akshaybagujar1001/hospital-management-angular-ui.git

## 📷 Screenshots

**1. Home Page of the Application:**  
![Home Page](https://raw.githubusercontent.com/akshaybagujar1001/hospital-management-angular-ui/main/src/assets/1.jpg)

**2. News Feeds:**  
![News Feeds](https://raw.githubusercontent.com/akshaybagujar1001/hospital-management-angular-ui/main/src/assets/2.jpg)

**3. Doctor Login Component with Authentication:**  
![Doctor Login](https://raw.githubusercontent.com/akshaybagujar1001/hospital-management-angular-ui/main/src/assets/3.jpg)

**4. Doctor Dashboard Component:**  
![Doctor Dashboard](https://raw.githubusercontent.com/akshaybagujar1001/hospital-management-angular-ui/main/src/assets/4.jpg)

**5. Search by Name Feature:**  
![Search](https://raw.githubusercontent.com/akshaybagujar1001/hospital-management-angular-ui/main/src/assets/5.jpg)

**6. Viewing Patient Diagnostics:**  
![Patient Diagnostics](https://raw.githubusercontent.com/akshaybagujar1001/hospital-management-angular-ui/main/src/assets/6.jpg)

**7. Add Medicine Component:**  
![Add Medicine](https://raw.githubusercontent.com/akshaybagujar1001/hospital-management-angular-ui/main/src/assets/7.png)

## Development server

Run `ng serve` for a dev server. Navigate to `http://localhost:4200/`. The application will automatically reload if you change any of the source files.

## Code scaffolding

Run `ng generate component component-name` to generate a new component. You can also use `ng generate directive|pipe|service|class|guard|interface|enum|module`.

## Build

Run `ng build` to build the project. The build artifacts will be stored in the `dist/` directory.

## Running unit tests

Run `ng test` to execute the unit tests via [Karma](https://karma-runner.github.io).

## Running end-to-end tests

Run `ng e2e` to execute the end-to-end tests via a platform of your choice. To use this command, you need to first add a package that implements end-to-end testing capabilities.

## Further help

To get more help on the Angular CLI use `ng help` or go check out the [Angular CLI Overview and Command Reference](https://angular.io/cli) page.
