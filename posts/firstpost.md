---
title:  First Post - Hello World! and 11ty
description: This is a post on My Blog about 11ty.
date: 2022-04-27
tags:
  - another tag
layout: layouts/post.njk
---
## What is 11ty
11ty is a static site generator that can build sites using HTML and CSS. 11ty takes complex markdown files and JSON files and condenses them resulting in an API for us to leverage content and build templates with.

## Starting with 11ty
1. First ensure you have the latest versions of NPM and NODE installed on your PC. Simply type npm -v or node -v in your terminal to see the version of npm and node you currently have.

2. Create a folder, preferably named 11ty, and open it using the Visual Studio code editor. While in Visual Studio code editor under the 11ty folder, create a .gitignore file. What this does is ignores any file that ends with the extension after the asterisk (*)

3. Add a .eleventy.js file under the 11ty folder you created. This file will empower your 11ty site to produce the final output.

4. Add dependencies to your 11ty site. Now we will install a package.json file. This allows npm to handle the project's dependencies properly. In your 11ty folder run 'npm init -y' in your terminal. This will allow npm to generate the package.json file for you. 

5. With all of those steps complete, now it's time to install eleventy. Run the command 'npm install @11ty/eleventy' in your terminal. 

6. Create a folder and label it 'src'.  Under this folder create a file named index.md. For this blog post, I will simply be typing Hello World! in the index.md file. Save all your scripts in VS code editor and type 'npx eleventy --serve' in your terminal and click on the Local URL. 
