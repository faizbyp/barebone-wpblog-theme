# Barebone Wordpress Theme

Made your own fully-customizable Wordpress theme from scratch with PHP and Bootstrap 5 CSS framework

## Setup
(Assuming that you already have your Wordpress site installed)
- Fork this repository
- Add it to `wp-content/themes` directory of your Wordpress site
- Download and install [Node.js](https://nodejs.org/en/download/)
- Install node_modules and bootstrap: `npm install`

## Development

### Styling

- Customize Bootstrap in `bootstrap/bootstrap.scss` (make sure to edit the sass `.scss` file, **not** the compiled `.css`)
- Watch customized bootstrap sass file: `npm run dev`

[Read Bootstrap 5 documentation](https://getbootstrap.com/docs/5.2/getting-started/introduction/)

### Functions

- Add Wordpress functions in `functions.php` file
- Use the imported functions in your desired page file

[More about Wordpress functions](https://developer.wordpress.org/reference/functions/)
