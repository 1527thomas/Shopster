<div id="top"></div>

[![Contributors][contributors-shield]][contributors-url]
[![Forks][forks-shield]][forks-url]
[![Stargazers][stars-shield]][stars-url]
[![Issues][issues-shield]][issues-url]
[![MIT License][license-shield]][license-url]
[![LinkedIn][linkedin-shield]][linkedin-url]

<!-- PROJECT LOGO -->
<br />
<div align="center">
  <a href="https://github.com/1527thomas/Shopster">
    <img src="./src/assets/Shopster.png" alt="Logo" width="80" height="80">
  </a>

<h3 align="center">Shopster</h3>

  <p align="center">
    An E Commerce website built with React that sells computer gaming related hardware.
    <br />
    <a href="https://github.com/1527thomas/Shopster"><strong>Explore the docs »</strong></a>
    <br />
    <br />
    <a href="https://github.com/1527thomas/Shopster">View Demo</a>
    ·
    <a href="https://github.com/1527thomas/Shopster/issues">Report Bug</a>
    ·
    <a href="https://github.com/1527thomas/Shopster/issues">Request Feature</a>
  </p>
</div>

<!-- TABLE OF CONTENTS -->
<details>
  <summary>Table of Contents</summary>
  <ol>
    <li>
      <a href="#about-the-project">About The Project</a>
      <ul>
        <li><a href="#built-with">Built With</a></li>
      </ul>
    </li>
    <li>
      <a href="#getting-started">Getting Started</a>
      <ul>
        <li><a href="#prerequisites">Prerequisites</a></li>
        <li><a href="#installation">Installation</a></li>
      </ul>
    </li>
    <li><a href="#usage">Usage</a></li>
    <li><a href="#roadmap">Roadmap</a></li>
    <li><a href="#contributing">Contributing</a></li>
    <li><a href="#license">License</a></li>
    <li><a href="#contact">Contact</a></li>
  </ol>
</details>

<!-- ABOUT THE PROJECT -->

## About The Project

[![Product Name Screen Shot][product-screenshot]](https://shopsterjs.netlify.app/)

Shopster is a e commerce website that sells computer gaming related hardware. It leverages commerce.js in order to create these products and allows the user to add them to a cart and checkout. Users can checkout by filling out the shipping address form and payment form. Payments are handled by Stripe.js. Upon completion of payment, both the store and the user will receive a confirmation email about the cart, user, and payment information.
<br></br>
Click on the screenshot to demo!

<p align="right">(<a href="#top">back to top</a>)</p>

### Built With

- [Create React App](https://create-react-app.dev/)
- [React.js](https://reactjs.org/)
- [CommerceJS](https://commercejs.com/)
- [StripeJS](https://stripe.com/docs/stripe-js/react)
- [Material-UI](https://mui.com/getting-started/usage/)
- [Netlify](https://www.netlify.com/)

<p align="right">(<a href="#top">back to top</a>)</p>

<!-- GETTING STARTED -->

## Getting Started

This is an example of how you may give instructions on setting up your project locally.
To get a local copy up and running follow these simple example steps.

### Prerequisites

This is an example of how to list things you need to use the software and how to install them.

- npm
  ```sh
  npm install npm@latest -g
  ```

### Installation

1. Get a free API Key at [https://commercejs.com/](https://commercejs.com/)
2. Get a free API Key at [https://stripe.com/](https://stripe.com/)
3. Clone the repo
   ```sh
   git clone https://github.com/1527thomas/Shopster.git
   ```
4. Install NPM packages
   ```sh
   npm install
   ```
5. Enter your API in a `.env`
   ```js
   REACT_APP_CHEC_PUBLIC_KEY = ENTER YOUR API
   REACT_APP_STRIPE_PUBLIC_KEY = ENTER YOUR API
   ```

<p align="right">(<a href="#top">back to top</a>)</p>

<!-- USAGE EXAMPLES -->

## Usage

<p align="right">(<a href="#top">back to top</a>)</p>

<!-- ROADMAP -->

## Roadmap

- [x] Landing page with products
- [x] Add to cart button for each product
- [x] Checkout page with updated cart items
- [x] Shipping address form with Country and Subdivisions and Shipping Options
- [x] Card payment from StripeJS
- [x] Confirmation emails to both store and user
- [ ] User accounts and login
- [ ] Previous user orders

See the [open issues](https://github.com/1527thomas/Shopster/issues) for a full list of proposed features (and known issues).

<p align="right">(<a href="#top">back to top</a>)</p>

<!-- CONTRIBUTING -->

## Contributing

Contributions are what make the open source community such an amazing place to learn, inspire, and create. Any contributions you make are **greatly appreciated**.

If you have a suggestion that would make this better, please fork the repo and create a pull request. You can also simply open an issue with the tag "enhancement".
Don't forget to give the project a star! Thanks again!

1. Fork the Project
2. Create your Feature Branch (`git checkout -b feature/AmazingFeature`)
3. Commit your Changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the Branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

<p align="right">(<a href="#top">back to top</a>)</p>

<!-- LICENSE -->

## License

Distributed under the MIT License. See `LICENSE.txt` for more information.

<p align="right">(<a href="#top">back to top</a>)</p>

<!-- CONTACT -->

## Contact

Thomas Wang - 1527thomas@gmail.com

Project Link: [https://github.com/1527thomas/Shopster](https://github.com/1527thomas/Shopster)

<p align="right">(<a href="#top">back to top</a>)</p>

<!-- MARKDOWN LINKS & IMAGES -->
<!-- https://www.markdownguide.org/basic-syntax/#reference-style-links -->

[contributors-shield]: https://img.shields.io/github/contributors/1527thomas/Shopster.svg?style=for-the-badge
[contributors-url]: https://github.com/1527thomas/Shopster/graphs/contributors
[forks-shield]: https://img.shields.io/github/forks/1527thomas/Shopster.svg?style=for-the-badge
[forks-url]: https://github.com/1527thomas/Shopster/network/members
[stars-shield]: https://img.shields.io/github/stars/1527thomas/Shopster.svg?style=for-the-badge
[stars-url]: https://github.com/1527thomas/Shopster/stargazers
[issues-shield]: https://img.shields.io/github/issues/1527thomas/Shopster.svg?style=for-the-badge
[issues-url]: https://github.com/1527thomas/Shopster/issues
[license-shield]: https://img.shields.io/github/license/1527thomas/Shopster.svg?style=for-the-badge
[license-url]: https://github.com/1527thomas/Shopster/blob/master/LICENSE.txt
[linkedin-shield]: https://img.shields.io/badge/-LinkedIn-black.svg?style=for-the-badge&logo=linkedin&colorB=555
[linkedin-url]: https://linkedin.com/in/thomas-wang1
[product-screenshot]: https://raw.githubusercontent.com/1527thomas/Shopster/master/src/assets/ShopsterSS.png
