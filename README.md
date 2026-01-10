# Scholio
Scholio is a school website template that helps you set up your school for a good online presence.

![cover](scholio.png)

## Details
- [Live Link](https://mtm-scholio.netlify.app)
- [Source Code Link](https://github.com/Marktawa/corporama)

## Prerequisites
To use this repo make sure [`git`](https://git-scm.com) is installed on your computer.

## Getting Started

Clone the repo.
```shell
git clone https://github.com/Marktawa/scholio
```

Change directories.
```shell
cd scholio
```

Run a web server. (Any will do. I just happen to use Python)
```shell
python -m http.server 8080
```

Visit site in your browser to view the landing page.

## Customization

### Edit content
Just open the `index.html` file in your code editor. All the content is written in HTML and is found in the `body` section of the file

### Edit design
Open the `index.html` file in your code editor. Go to the `<style>` section and edit the CSS for the web page. You can change the color palette, the fonts. Feel free to dig in

### Edit metadata
For SEO purposes you can change the `title` and `description` of the page in the `<head>` section of the page.

### Edit media
All media is stored in the root of the folder. You can change the logo by replacing the `logo.png` file with a different file but still name it `logo.png`. You can replace the `favicon.ico` file as well. It is in the root of the folder.

## Deployment
Once you are done editing and are satisfied with the results, you can deploy to any static web host. I advise to host on free ones like GitHub pages and so on. For this guide we include instructions for Netlify

### Sign up and Sign in for Netlify

Sign up for a [Netlify](netlify.com) account and visit the dashboard. 

Click create a New Netlify site.

On your local machine create a new folder called `site` where you put the production files for your site.

Copy your `index.html file`, your `logo.png`, and `favicon.ico`, and any other files associated with your website to your `site` folder.

Upload to Netlify, give it a name and then wait while Netlify deploys your site. 

After your site is deployed you will have a new website with a `.netlify.app` subdomain.

### Custom Domain Set up

Purchase a domain. Update the DNS settings for your website with the alias DNS provided by Netlify if you want to host your site on a custom domain. An automatic SSL cerfificate is given to your website. You will have to wait for at most 48 hours for all this to work.

## Quality Assurance

This was built with best practices in mind. With an impressive Lighthouse score across the board. Accessible, SEO ready, and Performant. 100% Guaranteed Quality.

## Author

This template was authored by Mark Munyaka. Mark Munyaka is a web developer and technical writer. If you have any issues, suggestions or maybe you want to work on a project. You can get in touch with him as follows:

* **Email**: markmunyaka@gmail.com
* **Portfolio**: [markmunyaka.netlify.app](https://markmunyaka.netlify.app)
* **Blog**: [dev.to/markmunyaka](https://dev.to/markmunyaka)
* **LinkedIn**: [linkedin.com/in/mark-munyaka-a878137b/](https://www.linkedin.com/in/mark-munyaka-a878137b/)
* **GitHub**: https://github.com/Marktawa

## License

This project is licensed under the MIT License

---

Copyright 2026. Mark T. Munyaka. All Rights Reserved.

