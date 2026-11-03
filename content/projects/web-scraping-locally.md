+++
title = 'Web scraping locally'
date = 2024-07-21T21:11:28+07:00
draft = false
+++

This is particularly useful when you're using Selenium. Instead of having the code open the browser to access a link (very slow), having the code open a link from an existing browser is so much faster. But this, in my opinion, is just a side benefit of web scrapping locally. Where it really shines though is when you have a login page (e.g [the online database for Indonesia's M.C.G agency](https://dataonline.bmkg.go.id/dataonline-home) in my real-life scenario) and you do not want to go through the hassle of writing ten(s) lines of code just to do that (use this wisely)

# Steps

1. Have chrome installed in your computer. Make sure you know where it is installed. 

2. Run the following code on Command Prompt (or Powershell)

```
chrome.exe --remote-debugging-port=8989 --user-data-dir="C:\Users\[]\Documents\chrome\chromeprofile"
```

3. In your web scraping program, have this code as your opening line:

```
opt = Options()
opt.add_experimental_option("debuggerAddress", "localhost:8989")
driver = webdriver.Chrome(options=opt)
```

---

How I managed to do this without using AI cannot be explained. YouTube ftw.