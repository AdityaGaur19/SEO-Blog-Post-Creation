# ✨ SEO Blog Post Creation 🚀

## 🔍 Project Overview

**SEO-Blog-Post-Creation** is an intelligent tool designed to scrape trending product data from e-commerce platforms (like **eBay Deals**) and automatically generate SEO-optimized promotional blog posts. This project seamlessly combines web scraping with powerful NLP models to produce marketing content that enhances discoverability and boosts engagement. Whether you're a digital marketer, e-commerce entrepreneur, or content strategist, this tool can help you automate high-quality content creation for trending products in just a few clicks.

---

## 🖼️ Notebook Preview

> Here’s a quick look at what the final output and flow inside the notebook looks like:

![SEO Blog Post Creation Notebook Preview](preview.png)

> 📸 This preview shows product scraping, keyword generation, and blog post writing happening inside Google Colab.

---

## ⚙️ Tech Stack & Tools

This project leverages the following technologies and libraries:

- **Python** 🐍  
- **Google Colab** 📓 (for seamless, ready-to-run cloud execution)  
- **requests & BeautifulSoup** 🌐 (for scraping live product listings)  
- **transformers (HuggingFace)** 🤗  
  - `bart-large-cnn`: used for summarization and keyword generation  
  - `gpt2-medium`: used for generating coherent blog content  
- **OpenAI** 🔑 (for optional integration of your own API key)
- **os** (to handle file creation and markdown generation)

---

## 📥 Input & 📤 Output Description

### 👀 Input:
- You don’t manually input any product titles or topics.
- The tool scrapes **trending products** from the `eBay Deals` section.
- You only need to provide your **OpenAI API Key** (though the actual NLP tasks are handled via HuggingFace).

### 🧾 Output:
- A separate markdown (`.md`) file for **each product** is created.
- Each `.md` file includes:
  - ✅ The **product name** as the blog title  
  - ✍️ An AI-generated **promotional blog post**  
  - 🔑 A list of **SEO keywords** for higher search visibility  
  - 🔗 A **"Buy Now"** link redirecting users to the product's page  

All generated files are stored in a directory named `blogs`.

---

## 🚀 How to Use This Project

1. Open the provided notebook in **Google Colab**  
2. Install required libraries and dependencies (already scripted)  
3. Paste your **OpenAI API Key** in the indicated code cells  
   - Cells: `xGJsa7Gv3K6p` and `aPNWUh7R4xnA`  
4. Run the notebook sequentially
5. After execution, the `blogs` folder will contain `.md` files – one for each product scraped and processed

> 💡 Note: Though the OpenAI API key is set, this project primarily runs on **HuggingFace** models, so usage limits or tokens won’t be consumed unless modified.

---

## 🔍 Sample Output

A sample blog post was generated for:

**Product Name:** `iRobot Braava Jet M6 (6110) Ultimate Robot Mop – Wi-Fi Connected, Precision Jet`

**Generated Blog Snippet (from Cell Lrh2yu8w6ZhX):**


📌 _Note: Some outputs may seem more instructional than descriptive – this is due to GPT2's prompt interpretation and can be improved by tweaking the generation parameters._

---

## 📁 Key File Summary

- **Main Notebook**: This Colab `.ipynb` contains the full pipeline:
  - Installations
  - API Key integration
  - Web scraping logic
  - AI model calls
  - Blog and SEO keyword generation
  - Markdown file writing

> You can access the preview of the `.ipynb` via this raw GitHub link:
> [🔗 View Notebook (raw)](https://raw.githubusercontent.com/AdityaGaur19/SEO-Blog-Post-Creation/main/SEO_Blog_Post_Creation.ipynb)

---

## 👤 Author Info

**GitHub Username:** [AdityaGaur19](https://github.com/AdityaGaur19)

---

## 🌟 Features Highlight

- ✅ No need to manually input content topics  
- ✅ Fully automated blog + keyword generation  
- ✅ Google Colab ready  
- ✅ Product scraping + blog creation in one go  
- ✅ Markdown output for direct publishing  

---

## 💡 Future Improvements (Optional Ideas)

- Add GUI support via Gradio or Streamlit  
- Expand to other e-commerce platforms (Amazon, Flipkart, etc.)  
- Fine-tune models for more persuasive and human-like outputs  
- Include product images in blog posts using scraped media URLs  
- Schedule blog generation periodically using a cron-based Colab setup

---

## 📝 License

This project is open-source and available under the [MIT License](LICENSE).  
Feel free to fork, modify, and use it in your personal or commercial workflows.

---
