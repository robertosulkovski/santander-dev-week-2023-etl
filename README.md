# Santander Dev Week 2023 ETL

ETL pipeline developed during Santander Dev Week using Python, OpenAI API and a custom Spring Boot banking API.

---

## Technologies

- Python
- Pandas
- OpenAI API
- Spring Boot
- Java
- Swagger
- Postman
- Google Colab
- Ngrok

---

## ETL Flow

1. Extract users from Spring Boot API
2. Transform data with OpenAI-generated messages
3. Load updated data back into the API
4. Export final dataset to CSV

---

## Creating Users via Postman

![Postman](assets/postman-create-user.png)

---

## API Before AI Processing

![Swagger Before](assets/swagger-before-openai.png)

---

## OpenAI ETL Execution

![Colab](assets/colab.png)

---

## API After AI Processing

![Swagger After](assets/swagger-after-openai.png)

---

## Dataset

Input dataset:

```text
data/SDW2023.csv
