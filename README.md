# My DevOps Blog

A sample Jekyll blog website powered by the **Minima** theme and automated with a CI/CD pipeline.  
This blog is designed for easy publishing using [Jekyll](https://jekyllrb.com/) and [GitHub Pages](https://pages.github.com/).

## 🚀 Features

- **Powered by Jekyll** (static site generator)
- **Minima theme** for clean and simple design
- **Write posts in Markdown**
- **Automated build and deploy** with GitHub Actions
- **Ready for free hosting on GitHub Pages**

## 📁 Folder Structure

```
.
├── _config.yml
├── _posts/
│   └── YYYY-MM-DD-title.md
├── Gemfile
├── index.md
└── README.md
```

## 🛠️ Local Setup

### 1. **Clone the Repository**
```sh
git clone https://github.com//.git
cd 
```

### 2. **Install Dependencies**
Make sure you have [Ruby](https://www.ruby-lang.org/en/downloads/) and [Bundler](https://bundler.io/) installed.

```sh
bundle install
```

### 3. **Run Locally**
```sh
bundle exec jekyll serve
```
Visit [http://localhost:4000](http://localhost:4000) to preview your site.

## ✍️ Writing a New Post

1. Go to the `_posts` folder.
2. Create a new file named `YYYY-MM-DD-title.md`.
3. Add the following front matter and content:
    ```markdown
    ---
    layout: post
    title: "Your Post Title"
    date: YYYY-MM-DD HH:MM:SS +0530
    categories: devops
    ---

    Your post content goes here.
    ```
4. Save the file and commit your changes.

## 🚢 Deploying to GitHub Pages

1. Push your changes to the `main` branch.
2. In your repository settings, enable GitHub Pages and select the `gh-pages` branch (if using a deploy workflow) or the `main` branch (if using default Pages build).
3. Your site will be live at:  
   `https://.github.io//`

## 📝 Customization

- Edit `_config.yml` to change site settings.
- Add new posts in `_posts/`.
- Customize the theme by editing the Gemfile or adding custom CSS.

## 📄 License

This project is open source and available under the [MIT License](LICENSE).

**Happy blogging!**

> _Replace `` and `` with your actual GitHub username and repository name._  
> _You can further customize this README to fit your project’s needs!_
