# Brainnco Front-End Challenge 🍀

A React front end that renders the results of the Brazilian CAIXA lotteries, built as a technical
challenge proposed by [Brainnco](https://github.com/brainnco-exs/readme-frontend).

## About

The app fetches lottery data from an API and lets the user switch between draws. Selecting a
different lottery re-themes the whole page — colour scheme, logo, draw number, draw date and the
drawn numbers all update together.

## Features

- Supports all six lotteries: Mega-Sena, Quina, Lotofácil, Lotomania, Timemania and Dia de Sorte
- Lottery selection through a dropdown
- The theme colour, draw number, draw date and drawn numbers update on selection
- Loading spinners while each request is in flight
- Error state when a request fails
- A 404 page for unmatched routes
- Responsive down to mobile widths

## Tech stack

- [React](https://react.dev/)
- [Styled Components](https://styled-components.com/)
- [React Router](https://reactrouter.com/)
- [Axios](https://github.com/axios/axios)

## Running it locally

Requires [Node.js](https://nodejs.org/en/) — the project was built against **16.17.0 LTS**.

```bash
git clone https://github.com/Brunomon2812/Case-Brainnco.git
cd Case-Brainnco
npm install
npm start
```

The app runs on http://localhost:3000 by default.

## Screenshots

### Desktop

![Mega-Sena results](https://user-images.githubusercontent.com/104601906/194668661-7c7f8345-b99f-4767-9e59-fc7ed91105eb.png)

![Lotomania results](https://user-images.githubusercontent.com/104601906/194668680-4c67564a-201c-4080-8167-74bd964082ad.png)

![Loading spinner state](https://user-images.githubusercontent.com/104601906/194668651-d8972164-93b1-43f9-a1a6-93f8513af5f4.png)

![Request error state](https://user-images.githubusercontent.com/104601906/194668647-3bb62624-68f4-400d-be35-36363c994c9c.png)

![404 page](https://user-images.githubusercontent.com/104601906/194668721-3e4f703c-d8df-4a2d-b41e-4d090b120c0a.png)

### Mobile

<img width="284" alt="Mobile layout" src="https://user-images.githubusercontent.com/104601906/194669763-c9017d9b-4c38-4f41-9c67-727640db6ac8.png">

## Challenge brief

The original specification for this challenge: [brainnco-exs/readme-frontend](https://github.com/brainnco-exs/readme-frontend)

## Author

Bruno Monteiro — [GitHub](https://github.com/Brunomon2812) · [LinkedIn](https://www.linkedin.com/in/brunoarmonteiro/)
