# How to: Host your HTML/CSS site with GitHub

## General Information
**Tutorial:** https://pages.github.com/  
**Github Page Basics (very useful!):** https://help.github.com/categories/github-pages-basics/  
**Getting Started With Github Pages (video):** https://www.youtube.com/watch?v=4TrOCv5Kukk

## Setting up a custom domain
1. In the root of your project repo, create a `CNAME` file
2. add your domain to your cname file. _example: evan.com_
3. Go to your domain registrar (godaddy, name.com, hover, etc.)
4. Find the DNS settings
5. Create A name records that point to `192.30.252.154` and `192.30.252.153`
6. Create a CNAME record for www.[your domain].com
7. Wait for the new records to propogate
8. Your site is up! If you visit your custom domain, you should see your github page.
