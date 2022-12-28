# Simple template for symfony + react + typescript

(updating [old repo here](https://github.com/Thomas-Radulesco/symfony-react-sass-template))
Now you've got Symfony 6.2.3, PHP 8.2, React 17.0.2 and Typescript

## Welcome 👋

### This repo will allow you to build an app using Symfony 🎹, React ⚛️ and Sass  

1. Install a development environment for PHP, which also delivers the PHP executable (like [Laragon](https://laragon.org/download/))

2. Install [Composer](https://getcomposer.org/download/)

3. Install [Symfony CLI](https://symfony.com/download)

4. Install [Node.js and npm](https://nodejs.org/en/)

5. Install [Yarn](https://yarnpkg.com/getting-started/install)

6. Clone this repo

7. Open a terminal in the directory you cloned this repo in, and enter :

    - `composer update`,
    - `yarn install`
  
8. If everything is OK, you can proceed with :
    - `symfony serve`
    You can stop the Symfony server anytime in that terminal with `CTRL+C`. If you want to detach the symfony server from that terminal (notice that you won't see its logs then!), to continue working in it, feel free to enter `symfony serve -d`. In that case you'll need `symfony server:stop` to stop the server
    - `yarn watch` to start the front server. Like the Symfony one, you can stop it anytime with `CTRL+C`
    Or you can enter `yarn build` to build your front app (but there's no point in building an empty app, is it ?)
  
  You should be good to go ! React front files are in `assets/`. For example, if you want to modify the "home", you have to modify `assets/Components/Home.js`.
  Symfony back files are in `src/` . Your twig templates are in `templates/`


9. If not, feel free to open an issue, but I can't guarantee I'd be available to care about it.

---

I might have forgotten some steps, I don't know. But if you are here, I assume you are a developper so you must be able to find your solutions by yourself.

### 💻 Have fun coding 💻
