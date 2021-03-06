+++
title = "How to say hello"
outputs = ["Reveal"]
+++

# Hugo - Revealjs 

---

## Download the hugo binary from 
https://github.com/gohugoio/hugo/releases

copy to the env path

---

###### Install a revealjs hugo theme to the themes folder

```
 git clone https://github.com/dzello/reveal-hugo.git .\themes\reveal-hugo\
```

###### can sometimes cause issues : copy the zip file and extract contents to the themes folder

---

## add the themes to the config.toml file

```
theme = "reveal-hugo"

[outputFormats.Reveal]
baseName = "index"
mediaType = "text/html"
isHTML = true
```
---

## add a file _index.md under contents folder 
```
+++
title = "How to say hello"
outputs = ["Reveal"]
+++
```
---

###### server the site using 'hugo server'
```
hugo server
```

---

###### Create a git repository and push the contents

```
git init
git add .
git commit -m "first commit"
git remote add origin https://github.com/srk553/HugoRevealjs.git
git push origin master

```

---

###### Create a netlify site and push the contents from git

![Step 1](/1.png)

---

###### Create a netlify site and push the contents from git

![Step 2](/2.png)

---

###### Create a netlify site and push the contents from git

![Step 3](/3.png)

---

###### Create a netlify site and push the contents from git

![Step 4](/4.png)

---

###### Create a netlify site and push the contents from git

![Step 5](/5.png)

---
###### Create a netlify site and push the contents from git

![Step 6](/6.png)

---

###### Create a netlify site and push the contents from git

![Step 7](/7.png)

---
###### Create a netlify site and push the contents from git

![Step 8](/8.png)

---
###### Create a netlify site and push the contents from git

![Step 9](/9.png)