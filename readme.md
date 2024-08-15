<h1 align="center">The Source Code of schola.co.uk</h1>

<p align="center">This website was built with Hugo and the Hugoplate theme, customised to suit our own use.</p>

---

## Getting Started

First you need to [clone](https://github.com/zeon-studio/hugoplate) or [download](https://github.com/zeon-studio/hugoplate/archive/refs/heads/main.zip) the template repository, and then let's get started with the following process:

### Prerequisites

To start using this template, you need to have some prerequisites installed on your machine.

- [Hugo Extended v0.124+](https://gohugo.io/installation/)
- [Node v20+](https://nodejs.org/en/download/)
- [Go v1.22+](https://go.dev/doc/install)

### Project Setup

We build this custom script to make your project setup easier. It will create a new Hugo theme folder, and clone the Hugoplate theme into it. Then move the exampleSite folder into the root directory. So that you can start your Hugo server without going into the exampleSite folder. Use the following command to setup your project.

```bash
npm run project-setup
```

### Install Dependencies

Install all the dependencies using the following command.

```bash
npm install
```

### Development Command

Start the development server using the following command.

```bash
npm run dev
```
---

## Customization

This template has been designed with a lot of customization options in mind. You can customize almost anything you want, including:

### Site Config

You can change the site title, base URL, language, theme, plugins, and more from the `hugo.toml` file.

### Site Params

You can customize all the parameters from the `config/_default/params.toml` file. This includes the logo, favicon, search, SEO metadata, and more.

### Colors and Fonts

You can change the colors and fonts from the `data/theme.json` file. This includes the primary color, secondary color, font family, and font size.

### Social Links

You can change the social links from the `data/social.json` file. Add your social links here, and they will automatically be displayed on the site.

---

## Advanced Usage

We have added some custom scripts to make your life easier. You can use these scripts to help you with your development.

### Update Theme

If you want to update the theme, then you can use the following command. It will update the theme to the latest version.

```bash
npm run update-theme
```

> **Note:** This command will work after running `project-setup` script.

### Update Modules

We have added a lot of modules to this template. You can update all the modules using the following command.

```bash
npm run update-modules
```

### Remove Dark Mode

If you want to remove dark mode from your project, you can use the following command to remove dark mode from your project.

```bash
npm run remove-darkmode
```

> **Note:** This command will work before running `project-setup` script. If you already run the `project-setup` command, then you have to run `npm run theme-setup` first, and then you can run this command. afterward, you can run `npm run project-setup` again.

---

## Build And Deploy

After you finish your development, you can build or deploy your project almost everywhere. Let's see the process:

### Build Command

To build your project locally, you can use the following command. It will purge all the unused CSS and minify all the files.

```bash
npm run build
```

### Deploy Site

We have provided 5 different deploy platform configurations with this template, so you can deploy easily.

- [Netlify](https://www.netlify.com/)
- [Vercel](https://vercel.com/)
- [Github Actions](https://github.com/features/actions)
- [Gitlab Ci](https://docs.gitlab.com/ee/ci/)
- [AWS Amplify](https://aws.amazon.com/amplify/)

And if you want to Host some other hosting platforms. then you can build your project, and you will get a `public` folder. that you can copy and paste on your hosting platform.

> **Note:** You must change the `baseURL` in the `hugo.toml` file. Otherwise, your site will not work properly.

---

## Guide to Staying Compliant

### Reporting Issues

We use GitHub Issues as the official bug tracker for this Template. Please Search [existing issues](https://github.com/zeon-studio/hugoplate/issues). It’s possible someone has already reported the same problem.
If your problem or idea has not been addressed yet, feel free to [open a new issue](https://github.com/zeon-studio/hugoplate/issues).

### License

Copyright (c) 2024 - Luke Stratta

**Code License:** Released under the [MIT](https://github.com/zeon-studio/hugoplate/blob/main/LICENSE) license.

**Image license:** The images are only for demonstration purposes. They have their license, we don't have permission to share those images. Images are courtesy of Pixabay


