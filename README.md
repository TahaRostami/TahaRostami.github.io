# TahaRostami.github.io

A Jekyll theme I designed and implemented for my website using W3.CSS and inspired by a template from W3schools

## A Comment For Myself:

bundle exec jekyll serve --livereload

## Some Statistics

Whole project: 1 day

# **Creating a GitHub Pages Website with a Jekyll Theme**

Whether you're an experienced programmer or just starting out, there may come a time when you need to create a simple website. This guide is designed to assist you in that endeavor.

## **Introduction**

- GitHub is a platform that enables developers to store and manage their code.
- GitHub also offers the added benefit of hosting simple websites for free.
- It's important to note that GitHub currently supports only static websites.
- A static website can only deliver content that has been pre-authored by the developer, such as HTML, CSS, JS, PDF files, and more. It cannot support dynamic behaviors like commenting, emailing, chatting, streaming, etc., unless you employ workarounds or third-party tools.
- To create a static website on GitHub, referred to as GitHub Pages, you first need to create a repository.
- In simple terms, a repository is akin to a project.
- If you wish to create a personal website, your repository should be named something like [your GitHub username].github.io.
- Once you have set up your repository, you can start developing your website using HTML, CSS, JS, and other web technologies if you're familiar with them.
- Many people, however, prefer to use available templates to streamline the process.
- I have developed a Jekyll template based on W3.CSS, a CSS framework that offers various built-in features and components to enhance your website's appearance.
- Jekyll is a static website generator with its own syntax and features that make managing static websites easier. GitHub seamlessly supports Jekyll, unlike many other static website generators.
- Using a Jekyll template with W3.CSS as the CSS framework provides the advantage of built-in GitHub support, allowing you to easily update your website's content without the need to recompile it after every change. Furthermore, W3.CSS ensures your website adheres to basic standards while allowing simple customization if you have knowledge of HTML, CSS, JS, or W3.CSS.

## **How to Use the Template I Developed?**

Here's a step-by-step guide on how to make the most of the template I've created for you:

1. Go to this address: **https://github.com/TahaRostami/TahaRostami.github.io**.
2. Click on the "Fork" button. This will create a copy of the template I developed as a new repository in your GitHub account.
3. Go to the settings section of the created repository and change the repository name to follow this template: [your GitHub username].github.io.
4. After a few minutes, you will have a website with the same content as mine, available at the repository name you set. To verify, enter [your GitHub username].github.io in a new browser tab to view your website.
5. To change the profile picture, navigate to your repository, open the **`_layouts/default.html`** file, and find **`<img src="https://avatars.githubusercontent.com/u/30346122?v=4" …`**. Replace the URL **`"https://avatars.githubusercontent.com/u/30346122?v=4"`** with the URL of the picture you want to use.
6. If you want to remove a single page, delete the corresponding file directly from your repository. For example, if you don't need the "SHARED" page, delete its corresponding file from the repository's home directory.
7. To add a single page, create a new .md (Markdown) file with any name you prefer. Then, update the .markdown file and customize its content. Content should be written in Markdown language, and you can occasionally add HTML/CSS elements as needed. You can click on existing single pages such as "chess.markdown" or "index.markdown" to get an idea of what your custom single page may need. You can also search for "Markdown for GitHub" to learn more about this language and discover additional formatting options.
8. If you want to remove a page that has sub-pages, like "publications" and "projects," delete the corresponding folder and all its contents starting with an underscore (_). Then, open the **`_config.yml`** file and remove the section that corresponds to what you've deleted.
9. To add a page with sub-pages, create a new folder starting with an underscore (_), and add the necessary filename without including an underscore (_) in the **`_config.yml`** file. You can add sub-pages to the newly created folder. Explore the **`_publication`** and **`_projects`** internal files to understand how to structure this.
10. Consider customizing your website further by modifying some of the content in the **`_config.yml`** file. You can change elements like the title, description, email, and more to make your website uniquely yours.
11. By following these steps, you can fully customize your website. Don't hesitate to explore and experiment on your own. You can also check out repositories of other users who have forked my template to compare and learn from their customizations.
12. After making changes, your website will update automatically within a minute or a few minutes.

## **Indexing**

- Over time, your site will be indexed by some search engines such as Bing, but not by others, especially Google. In other words, if you search for your site on Google, it may not appear in the results.
- To address this, one solution is to create a Google Console account.
- In your Google Console account, request Google Site Verification. This will provide you with a verification content. Open the **`_includes/head.html`** file in your repository and replace the existing content in **`<meta name="google-site-verification" content="ZnN8F90tUwuNWbMRaooBlPn_Kr_ES9WiHSL_KwHlEOE" />`** with the verification content.
- Next, go to your home directory in the repository and open up the **`sitemap.txt`** file. Add the URLs from your website that you want Google to index, and save the changes.
- Verify the sitemap in your Google Console account.
- After a few days, Google will index your website.
