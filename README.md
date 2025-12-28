# AetherData Vietnam Blog
Welcome to the official repository of AetherData Vietnam. This is a specialized technical blog platform dedicated to researching and sharing knowledge in Data Engineering, Artificial Intelligence, and Modern Technology Stack.

Built with the power of Astro and a cosmic-inspired technical aesthetic, this blog serves as the knowledge hub for our community.

## 🛠️ Project Structure
```
├── public/             # Static assets
├── src/
│   ├── assets/         # Images and other assets
│   ├── config/         # Site configuration
│   ├── content/        # Content collections (blog posts, authors, etc.)
│   │     ├── authors   # List Authors 
│   │     └── posts     # List Posts 
│   ├── layouts/        # Layout components
│   ├── pages/          # Page components and routes
│   ├── styles/         # Global styles
│   └── utils/          # Utility functions
├── astro.config.mjs    # Astro configuration
├── package.json        # Dependencies and scripts
```

## Contribution Guide (Workflow)
We welcome all members to contribute their research. To maintain a clean repository, please follow these rules:

1. Creating New Content
To write a new post, create a .md or .mdx file in src/content/posts/ with the following format:

````markdown
---
title: "Your Technical Article Title"
description: "A brief summary of your research"
date: 2025-12-28
image: "../../assets/images/your-banner.jpg"
authors: ["your-author-id"]
categories: ["Data Engineering"]
tags: ["AI", "Python", "AetherData"]
---
Your deep-dive content starts here...
````
* **title**: Tiêu đề hiển thị của bài viết.
* **description**: Câu tóm tắt nội dung bài viết để hiển thị trên Google (SEO).
* **date**: Ngày xuất bản bài viết theo định dạng YYYY-MM-DD.
* **image**: Đường dẫn đến ảnh bìa của bài viết, lưu trong thư mục `src/assets/images/`.
* **authors**: ID của tác giả (phải khớp với file tên tác giả trong `src/content/authors/`).
* **categories/tags**: Dùng để phân loại bài viết giúp độc giả dễ tìm kiếm.

2. Branch Naming Convention
Before starting your work, create a new branch from main.

* Rule: The branch name must be your Author Name.

* Command: git checkout -b your-name

3. Pull Request (PR) Rules
When you are ready to submit your article for review:

* PR Title Format: [Author Name] + [Article Title]

* Example: AlexNguyen + Building Scalable Data Pipelines with Astro

## 🚀 Getting Started
1. Clone the repository:
```bash
git clone https://github.com/your-username/aetherdata-vn.io.git
cd aetherdata-vn.io
```
2. Install dependencies:
```bash
npm install
```
3. Run local dev
```bash
npm run dev
```
Let access your local site at http://localhost:4321/blog.

## 🛰️ Deployment
The blog is automatically deployed to GitHub Pages via GitHub Actions whenever a PR is merged into the main branch.

Link blog is: https://aetherdata-vn.github.io/blog

## 📜 License
This project is licensed under the MIT License.

## 🙏 Acknowledgments
A special thanks to BitDoze for providing the foundational Astro Blog Theme, which served as the core engine for implementing this blog.

AetherData Vietnam - Decoding the Universe of Data.
