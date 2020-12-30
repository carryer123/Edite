<div align="center">
  <img src="./public/images/Logo512.svg" alt="Edite" width="96">
  <h1>Welcome to Edite repository</h1>
  <strong>Your new Photoshop</strong>
  <h6>Made with ❤️  by Esaú Morais</h6>
</div>
<br>

## Edite

> Your new Photoshop • A simple way to edit your photos and getting satisfied.

* 🧭 **Mission:** Make the **users' job easier** on image editing, providing simple tools, but also effective.
* 🔭 **Vision:** Incentive people to **explore** photo editing, making it easy and simple.
* ⚖️  **Values:** Build in a **minimalist** way can also be effective.

## 📌 Try Edite

Edite is currently available just for Desktop/Tablet browsers (Chrome, Firefox, Edge, etc.) in general to have a better experience.

<p align="center">
  <img src="./public/images/GitHub Banner.png" alt="Edite">
  <br>
  <a href="https://edite.netlify.app">
    <strong>🚀 Try now</strong>
  </a>
</p>

## 🛠️  Built with

* 🎨 **UI Design:** Figma
* ⚛️  **Front-End:** React
* 🌳 **Services:** Cloudinary

## 🚀 Running Edite Locally

Let's setup Edite locally, following up the setups below to quickly get started.

Before running, you need to setup the services required to run the Edite App.

### ⚙️  Setting Up Services

#### Edite Landing Page

👉 Edite uses Facebook Messenger Plugin for the customers messaging service.

1. Go to [Facebook for Developers](https://developers.facebook.com/apps).

    1.1. Click the "Create App" button.

    1.2. Complete the app information.

    1.3. To finish, click the "Create App" button.

    1.4. With that, you'll be able to have an `App ID`.

2. You also need to create a [Facebook Page](https://www.facebook.com/pages/creation/).

    2.1. Complete the page information.

    2.2. Then, you can find the `Page ID` at the end of the "About" page.

⚠️  Remember to add the environment variables based on the [`env_sample`](./.env_sample)

💡 If you will not contribute to the Landing Page or try to learn how this service works, you can skip to the next section.

#### Edite App

👉 Edite uses Cloudinary services to upload presets.

1. Create an account on [Cloudinary](https://cloudinary.com/) (or log in, if you already have one)

2. After done with the first step, you'll be able to access the console:

<div align="center">
  <img src="https://cloudinary-res.cloudinary.com/image/upload/f_auto,q_auto,c_scale/training/cloudinary-console-example.png" alt="Cloudinary console" width="550">
  <br>
  <small>Cloudinary console</small>
</div>

3. Get you API Url, clicking on the _More_ button:

<div align="center">
  <img src="https://getcontenttools.com/images/pages/tutorials/image-uploads-with-cloudinary/account-details.png" alt="More button" width="550">
  <br>
  <small>More button to get API Url</small>
</div>

4. Now, you just need to create a Upload preset. Go to _Settings_ (icon), then, the _Upload_ tab:

<div align="center">
  <img src="https://support.cloudinary.com/hc/article_attachments/360023056072/upload-preset.png" alt="Upload presets" width="550">
  <br>
  <small>Upload presets page</small>
</div>

5. To finish, make sure to add and save:

    5.1. Upload preset name
  
    5.2. Signing mode as _unsigned_

    5.3. Folder

⚠️  Remember to add the environment variables based on the [`env_sample`](https://github.com/Edite-App/Edite-Webapp/blob/main/.env_sample)

### ⚛️  Setting Up Edite App

1. Fork this project

![Forking the project](https://camo.githubusercontent.com/6f03010c651d060f8b7cfc17da7098c1757c4ead/68747470733a2f2f6669727374636f6e747269627574696f6e732e6769746875622e696f2f6173736574732f526561646d652f666f726b2e706e67)

2. Clone the forked repository

    `git clone https://github.com/user/Edite` (if you use `git`)

    or

    `gh repo clone https://github.com/user/Edite` (if you use `gh` cli)

3. Install the dependencies

    `npm install` (if you use `npm`)

    or

    `yarn` (if you use   `yarn`)

4. Start the project

    `npm start` (if you `npm`)

    or

    `yarn start` (if you use `yarn`)

## 🙌 Want to Contribute?

You are more than welcome to contribute to all kinds of contributions:

* 🤔 Request/Suggest a feature
* 🐛 Report a bug
* 📖 Make this documentation better
* ‍💻 Contribute with the code

Before start, it's heavily recommended to check Edite's [guidelines](https://github.com/Edite-App/.github/blob/main/CONTRIBUTING.md).

## ⭐ Rate Edite

<p>
  <a href="https://www.producthunt.com/posts/edite">
    <img alt="Edite ProductHunt" align="center" src="https://img.shields.io/badge/producthunt-%23DA552F.svg?&style=for-the-badge&logo=product-hunt&logoColor=white" />
  </a> &nbsp; Checkout Edite on ProductHunt and give your feedback!
</p>

## 🎉 Acknowledgements

It is a pleasure to mention [Daily.dev](https://daily.dev) organization as the head contributor to making this project documentation better.

* [Daily.dev repository](https://github.com/dailydotdev/daily)
* [Daily.dev default docs](https://github.com/dailydotdev/.github)
* [Daily.dev Web app repository](https://github.com/dailydotdev/daily-webapp)

---

## 📑 License

Distributed under the [MIT License](./LICENSE)
