---
# Essential Fields
title: "From Tool Search to App Development: My AI-Assisted Journey"
date: '2025-01-19T15:57:11Z'
draft: false

# SEO and Display
description: "How a search for image processing tools led to building a custom desktop app with AI assistance, demonstrating the potential of AI-assisted development for solving personal technical challenges."
summary: "An unexpected journey from seeking image processing tools to creating a custom desktop application with AI assistance."
keywords: [AI development, Electron app, image processing, ChatGPT, Claude, desktop application, web technologies, AI assistance]
slug: ai-assisted-app-development    

# Organization
tags: [AI development, Electron, image processing, GenAI, desktop apps, web development]
categories: [Technology, Development]
series: [AI-Assisted Development]

# Display Options
showToc: true
tocOpen: false
showBreadcrumbs: true

# Featured Image
cover:
  image: /images/AI-Assisted-image-creation_processed.webp
  alt: A digital network with nodes and lines, alongside a digital interface displaying images of a landscape and a building.
  caption: From Tool Search to App Development
  relative: false   # If true, image path is relative to page bundle

# Display Settings
showReadingTime: true
showWordCount: true

# PaperMod Specific
ShowReadingTime: true
ShowShareButtons: true
ShowPostNavLinks: true
ShowCodeCopyButtons: true
searchHidden: false
hideSummary: false
hideFooter: false

---

What started as a simple search for an image processing tool turned into an unexpected journey into app development, all thanks to AI.

I was working on improving my blog posts and wanted to add relevant images to enhance the reading experience. Rather than using generic stock photos or searching through royalty-free images from services like Unsplash or Pexels, I decided to explore AI image generation to create visuals that would hopefully match my content. After some research, I found a promising tool on [junia.ai](https://www.junia.ai/tools/blog-images) that produced decent results.

Using the blog's description, I generated my first AI image. However, I encountered a limitation - the image's ratio was fixed at 1:1, and I needed to optimize it for better loading speed and SEO. I quickly realised that my Mac lacked a suitable image processing tool for simple tasks like cropping, ratio adjustment, and optimisation for web. While macOS had some built-in options, I wanted to avoid heavy applications like Photoshop that felt like overkill for such basic tasks.

My search for alternatives online only led to bloated applications or paid solutions - neither of which I wanted. Frustrated, I turned to AI assistants like ChatGPT and Claude for recommendations. What happened next surprised me.

Instead of simply suggesting existing tools, Claude started coding - something could've been avoided had I put more specific instructions in the prompt. It wrote a small web application using Electron - a framework that allows developers to create cross-platform desktop applications with web technologies like HTML, CSS, and JavaScript. Though uncertain if this was what I wanted, I decided to give it a try. I copied the code into VS Code, initialized Git to track changes, and ran npm start. The coolest thing happened - without writing a single line of code myself, I had created a web application that actually solved my problem - all thanks to GenAI. While the initial version wasn't perfect, lacking features like aspect ratio control, image preview, and custom file naming, it successfully handled the core functionality: converting images to the web-optimised .webp format. All I needed to do was add some additional features. It felt like a Tony Stark moment - having an AI assistant help me build exactly what I needed.

After a few tweaks, I have a workable imaging processing app that has the following functions:
- Image preview for uploaded files
- Custom width and height settings
- 16:9 aspect ratio option
- Multiple output format choices
- Quality adjustment
- Custom output file naming

This experience opened my eyes to the potential of AI-assisted development. What began as a search for an image processing tool evolved into building my own solution, demonstrating how AI can empower users to create custom solutions for their specific needs.

You can find the project on [GitHub](https://github.com/dandange8005/image-processer) if you'd like to try it yourself.
