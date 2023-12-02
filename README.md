# This is the origin of the htpa mesa website

There will be everything from the website here, but I have yet to make it an organization in github and add people for the maintenance of the website so far, once the contect and overall structure of the website is done, this will be archived and the organization will be made with the new repository to continue updating the website.

## How to upload to GitHub

To make a new repository, do this:

```bash
git init
```

once you have done this, if you are on windows you should press Ctrl + Shift + P, and if you are on mac you would press Command + Shift + P. then type this in at the top

```bash
@command:github.publish
```

once you have done this you can choose to make a private or public repository, and then you can type this in to update your repository

```bash
git add .
```

now write a local commit with a message:

```bash
git commit -m 'YOUR MESSAGE'
```

once this is finished, push your local commit:

```bash
git push
```

---

## How to remove the .DS_Store

add a .gitgnore file and put this in the file:

```bash
.DS_Store
```
