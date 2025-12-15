# Performed-manual-API-testing-using-Insomnia-on-Swagger-Petstore-API-

## -- Project Performed manual API testing using Insomnia on Swagger Petstore API to validate CRUD functionality and response handling
 Tools: Google Sheets, Insomnia, Test Case Design, Manual Testing

## 📌 Deskripsi Proyek
 Repository ini berisi dokumentasi manual API testing yang dilakukan pada Swagger Petstore API menggunakan Insomnia sebagai API client.
 
 proyek ini bertujuan untuk menunjukkan kemampuan saya dalam:
 - Memahami REST API
 - Menyusun test plan dan test case API
 - Melakukan pengujian manual (positive & negative scenario)
 - Memvalidasi response API (status code, response body, dan struktur data)
 - Mendokumentasikan hasil testing secara rapi dan terstruktur
 
 
 # 🔍 Scope of Testing
 
 Base URL: https://petstore.swagger.io/v2
 API Reference: Swagger Petstore

 # How To Access Petstore API
  1. Open The App Insomnia
  2. Click new request
  3. Fill in the name and method according to the endpoint to be tested.
  4. Fill in the URL petstore.swagger.io/v2 and add the appropriate endpoint to be tested.
  5. Click button send.
  
  ## 📌 Endpoints Tested

| HTTP Method | Endpoint                   | Purpose                        |
|-------------|----------------------------|--------------------------------|
| GET         | `/pet/findByStatus`        | Fetch pets by status           |
| GET         | `/pet/{petId}`             | Retrieve specific pet          |
| POST        | `/pet`                     | Create new pet                 |
| PUT         | `/pet`                     | Update existing pet            |
| DELETE      | `/pet/{petId}`             | Delete specific pet            |

# 🧪 Tools & Skills Used

  Tool: Insomnia (for manual API testing)
  Documentation: Swagger Petstore
  Test Design: Positive & Negative Test Cases
  Test Management: Google Spreadsheet
  Validation: Response body, status code, and schema structure

# 📂 Files in This Repository
  To access test cases and evidence, please access the link below.
# 📘 [Full Test Case Documentation](https://docs.google.com/spreadsheets/d/1CXtV_Wkme__WvCL6R1mqpGJpnOCYBJZOhRmAvcqho98/edit?usp=sharing)

# 🧠 Key Learnings

  - Understanding input validation & negative testing
  - Creating structured manual test cases
  - Documenting expected & actual results


## 💼 CATATAN

- Project ini dibuat untuk sebagai bukti dokumentasi lengkap dari proses testing terhadap Swagger Petstore API. Tiap file di simpan dalam directory yang berbeda sehingga memudahkan dokumentasi dan pengembangan selanjutnya. Saran dan masukan akan sangat berguna dalam proses berkembang saya, Terima kasih!.

## 🚀 Pengembangan Selanjutnya
- Automation API testing (Postman / Newman / REST Assured)
- Penambahan assertion otomatis
- Integrasi ke CI/CD pipeline

--- 

💼 Author
Budi Octaviandy – Manual QA & PL/SQL Developer
🔗 LinkedIn: [My Linkedin Profile](https://www.linkedin.com/in/budi-octaviandy-56a4311a0/)

---

> _“Quality is never an accident; it is always the result of intelligent effort.” — John Ruskin_

![Status](https://img.shields.io/badge/Testing-API-blue)
![Tool](https://img.shields.io/badge/Insomnia-Used-success)
![Learning](https://img.shields.io/badge/Learning-Continuous-orange)
