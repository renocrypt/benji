# 🦁 Benji Peng's Hugo-Powered Links Page

Welcome to the digital den of Dr. Benji Peng, where biophysics meets the web! 🧬💻

## 🚀 What's This All About?

This project is a sleek, minimalist links page powered by the awesome [Lynx theme](https://github.com/jpanther/lynx) for Hugo. It's where I, Dr. Benji Peng (aka Dr. Honeycutt 🍯), showcase my professional and social media presence in one stylish spot.

## ✨ Features

- 🌓 Dark mode support (because science happens day and night)
- 📱 Fully responsive design (looks great on everything from smartphones to electron microscopes)
- 🎨 Customized link styles (each link is as unique as a protein fold)
- 🚀 Fast loading times (quicker than a quantum leap)
- 🔍 SEO-friendly (so you can find me easier than a needle in a haystack)

## 🔗 Quick Links

- 🧪 [More About My Research](https://benji-scientist.renocrypt.com/)
- 🎨 [Designed by Benji](https://benji-design.renocrypt.com)
- 📝 [Blog On Science / ML](https://www.renocrypt.com)

## 🛠 Tech Stack

- [Hugo](https://gohugo.io/): The world's fastest framework for building websites
- [Lynx Theme](https://github.com/jpanther/lynx): A simple links theme for Hugo
- [Tailwind CSS](https://tailwindcss.com/): For utility-first styling

## 🚀 Getting Started

1. Clone this repo
2. Install Hugo
3. Run `hugo server` in the project directory
4. Visit `http://localhost:1313` to see the magic happen!

## 📝 License

This project is open source and available under the [MIT License](LICENSE).

## 🤝 Connect with Me

Feel free to reach out on any of the platforms linked on the main page. Whether you want to discuss biophysics, web design, or the best honey varieties, I'm all ears! 🐝

## Swapping a Git Submodule

To swap your Git submodule from the current repository to another one (in this case, from `themes/lynx` to `https://github.com/benjipeng/hugo-simpcard.git`), follow these steps:

### 1. Remove the existing submodule

First, you need to remove the current submodule. Run the following commands:

```bash
bash
git submodule deinit -f themes/lynx
git rm -f themes/lynx
rm -rf .git/modules/themes/lynx
```


### 2. Add the new submodule

Now, you can add the new submodule pointing to the desired repository:


### 3. Initialize and update the submodule

After adding the new submodule, initialize and update it:

```bash
bash
git submodule update --init --recursive
```

### 4. Commit the changes

Finally, commit the changes to your repository:

```bash
bash
git commit -m "Swapped submodule from themes/lynx to hugo-simpcard"
```


---

Built with ❤️ and ☕ by Benji Peng, Ph.D. © 2024 RenoCrypt