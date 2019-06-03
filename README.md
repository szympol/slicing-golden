# Slicing Golden Theme

Slicing a project of a website in Photoshop from PSD to Responsive Website. Based on [PSD Golden template](https://github.com/szympol/slicing-golden/blob/master/images/zadanie-golden.psd).

## Getting Started

- [View project online](https://szympol.github.io/slicing-golden/)

Please follow instructions below, if you are willing to run the project locally.

### Prerequisites

Both [Git](https://git-scm.com/downloads) and [Node](https://nodejs.org/en/download/) are required to run this project locally. 

### Installing

Please copy and paste below commands to your Git terminal step by step to get a development env running.

Download a repository:

```node
git clone git@github.com:szympol/slicing-golden.git slicing-golden
```

Go to the project working directory:

```node
cd slicing-golden
```

Install all of the dependencies with the following command:

```node
npm install
```

View the project

```node
npm run watch
```

#### Under the hood of `npm run watch`

This command watches any changes in `sass/style.scss`. Once a change detected, SCSS file starts to be converted into `css/style.css` with autoprefixes attached. This command also deploys the project to the live stream on `http://localhost:3000`.

## Built With

- [Bootstrap 3](https://getbootstrap.com/docs/3.3/) - popular HTML, CSS, and JS framework for developing responsive, mobile first projects on the web.

## Author

- **Szymon Polanowski** - [GitHub Account](https://github.com/szympol)

## License

This project is licensed under the MIT License.
