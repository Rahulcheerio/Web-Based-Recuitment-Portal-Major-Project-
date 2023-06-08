
# Project Title
Job Portal is a MERN Stack based web app which helps in streamlining the flow of job application process. It allows users to select there roles (applicant/recruiter), and create an account. In this web app, login session are persistent and REST APIs are securely protected by JWT token verification. After logging in, a recruiter can create/delete/update jobs, shortlist/accept/reject applications, view resume and edit profile. And, an applicant can view jobs, perform fuzzy search with various filters, apply for jobs with an SOP, view applications, upload profile picture, upload resume and edit profile. Hence, it is an all in one solution for a job application system.

## API Reference

#### Get all items

```http
  GET /api/items
```

| Parameter | Type     | Description                |
| :-------- | :------- | :------------------------- |
| `api_key` | `string` | **Required**. Your API key |

#### Get item

```http
  GET /api/items/${id}
```

| Parameter | Type     | Description                       |
| :-------- | :------- | :-------------------------------- |
| `id`      | `string` | **Required**. Id of item to fetch |

#### add(num1, num2)

Takes two numbers and returns the sum.


## Run Locally

Clone the project

```bash
  git clone https://github.com/Rahulcheerio/Web-Based-Recuitment-Portal-Major-Project-.git
```

Go to the project directory

```bash
  cd my-project
```

Go to the Backend directory

```bash
  cd backend
```

Install dependencies

```bash
  npm install --force
```

Start the Backend

```bash
  npm start
```

Go to the Frontend directory

```bash
  cd frontend
```

Install dependencies

```bash
  npm install --force
```

Start the Frontend

```bash
  npm start
```

## Authors

- [@Rahulcheerio](https://github.com/Rahulcheerio)
- [@prabhatgupta23](https://github.com/prabhatgupta23)
- [@Parth-Dingliwal](https://github.com/Parth-Dingliwal)

## Demo

Link to demo
https://drive.google.com/file/d/1yqp7z0d_bGCXeuOSulhgNdfzskjh3YNX/view?usp=share_link

## Tech Stack

**Client:** React, Bootstrap 

**Server:** Node, Express

**Database:** MongoDB 

**State_Management** Redux ,Context API

**Realtime** Socket.IO

## Screenshots
                                                             ` Welcome Page `
![image](https://github.com/Rahulcheerio/Web-Based-Recuitment-Portal-Major-Project-/assets/124549131/72055c36-66ea-4549-87f3-40423af92162)

                                                             ` Add Jobs Page `
![image](https://github.com/Rahulcheerio/Web-Based-Recuitment-Portal-Major-Project-/assets/124549131/b259723d-a1df-4923-afbb-30d1ce10f4df)

                                                           ` Filter on Jobs Added `
![image](https://github.com/Rahulcheerio/Web-Based-Recuitment-Portal-Major-Project-/assets/124549131/367eaead-cab3-4084-8ce3-f7c5cebb3e96)

                                                            `Realtime Code Editor`
![image](https://github.com/Rahulcheerio/Web-Based-Recuitment-Portal-Major-Project-/assets/124549131/093324c4-91ab-455c-be5b-4e97a0fadbcb)

## Optimizations
Improved the functionality of website using indexing on backend , pagination , lazy-loading .

## Contributing

Contributions are always welcome!

See `contributing.md` for ways to get started.

Please adhere to this project's `code of conduct`.
