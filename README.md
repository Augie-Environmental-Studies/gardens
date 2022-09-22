<br>

<p align="center">
  <a href="https://augie-environmental-studies.github.io/gardens/">
    <img alt="Logo" src="https://user-images.githubusercontent.com/19341857/190898818-e413ed07-4b0c-45bf-bcae-22513d20e7f2.png" width="350">
  </a>
</p>

<br>

<p align="center">
  <a href="https://www.instagram.com/augustana_garden/">
    <img alt="Instagram" src="https://user-images.githubusercontent.com/19341857/191081372-bc567def-d536-4daa-9243-c02362f96f3d.svg">
  </a>  
  &nbsp;
  <a href="https://www.facebook.com/augiesustain/">
    <img alt="Facebook" src="https://user-images.githubusercontent.com/19341857/191081605-ee573b37-610a-432e-8fac-a0759082ffba.svg">
  </a>
  &nbsp;
  <a href="https://twitter.com/augustanagarden">
    <img alt="Twitter" src="https://user-images.githubusercontent.com/19341857/191081683-e9bdeb25-7c0a-450f-a9e4-8626c21e25fa.svg">
  </a>
</p>

<br>

<p align="center">
  <b>
    Augie Gardens<br>
    [<a href="https://augie-environmental-studies.github.io/gardens/">Official Website</a>] 
  </b> 
</p>

<br>

> There are two spiritual dangers in not
> owning a farm. One is the danger of supposing
> that breakfast comes from the grocery, and
> the other that heat comes from the furnace.
>
> To avoid the first danger, one should plant
> a garden.
> 
> (Aldo Leopold, 1949, *A Sand County Almanac*)

<br>

# How to edit the website

> 1. Every project page has `Edit page on GitHub` button at the bottom.

<p align="center">
  <img alt="Click Edit page on GitHub" src="https://user-images.githubusercontent.com/19341857/191703710-12cd6e9b-220c-40b8-83fa-21ae045de26a.png" width="500">
</p>

<br>

> 2. Click `Edit this file` button.

<p align="center">
  <img alt="Click Edit this file" src="https://user-images.githubusercontent.com/19341857/191704678-64755128-8432-47e6-9934-a7b54b09be75.png" width="500">
</p>

<br>

> 3. Here's where we can edit the content.
> In addition, if you want, you can find advanced 
> formatting syntax on GitHub's 
> [MarkDown Guide](https://docs.github.com/en/get-started/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax).

<p align="center">
  <img alt="Make changes you want" src="https://user-images.githubusercontent.com/19341857/191704716-836443e2-30c5-4fcb-b00f-5baa3a268230.png" width="700">
</p>

<br>

> 4. Click `Propose changes`.
  
<p align="center">
  <img alt="Click Propose changes" src="https://user-images.githubusercontent.com/19341857/191704767-a716f922-b9fd-4352-ab8a-81cd83638b31.png" width="500">
</p>
  
<br>

> 5. Click `Create pull request`.
  
<p align="center">
  <img alt="Click Create pull request" src="https://user-images.githubusercontent.com/19341857/191704844-21c7492f-7457-4943-b291-368ca25632c8.png" width="500">
</p>

<br>

> 6. Briefly describe what kind of changes you made.
> Think of it as a summary. A good summary allows maintainers to
> easily understand what kind of changes you made.
> This will speed up the process of getting your pull request approved.
  
<p align="center">
  <img alt="Describe what kind of changes you made" src="https://user-images.githubusercontent.com/19341857/191704896-c62b9531-2515-443c-bdea-34a9bce6b613.png" width="650">
</p>

> 7. Click `Create pull request`. That's all!
> Maintainers will approve your pull request as soon as possible.
> Pull requests are usually approved within one week. If, however,
> there's no feedback for too long, then
> you can reach out to srho17@ole.augie.edu


<p align="center">
  <img alt="Finally, click Create pull requet" src="https://user-images.githubusercontent.com/19341857/191704937-b6a94636-18e9-4dbb-b9bc-292a38462a6c.png" width="500">
</p>  
  

<br>
<br>

# How the website was made

We wanted to make our website
as self-sustainable just like our gardens.
So, we decided to use open-source libraries called
[Hugo](https://github.com/gohugoio/hugo) and
[Doks](https://github.com/h-enk/doks).
These two libraries create the backbone
of our website. Then, we use
[GitHub Pages](https://pages.github.com/)
to host our website.

We thought about getting a dedicated Virtual Private Server
and then developing with
[Express](https://expressjs.com/)
or using a content management system like
[WordPress](https://github.com/WordPress/wordpress-develop).
We, however, decided against these because
we don't need the extra features
that come with them.
With Hugo, Doks, and GitHub Pages,
we were able to make our website
fast and free.

**How can I run a development server?**<br>
If you're a non-technical user, you don't need this part, 
but this will be useful if you'd like to tinker with
the general source code of our website.

```bash
# Install git
sudo dnf install -y git

# Install nvm; and then close and reopen the terminal
# in order for new paths to take effect.
curl -o- https://raw.githubusercontent.com/nvm-sh/nvm/v0.39.1/install.sh | bash

# Install Node.js
nvm install node

# Clone this repository
cd Downloads
git clone https://github.com/Augie-Environmental-Studies/gardens.git

# Install dependencies
cd gardens/src
npm install

# Start a developmental server
npm run start
```

<br>
<br>
<br>

<!--

**Create a new section**

```bash
cd gardens/src
npm run create docs/SECTIONNAME --kind docs
```



-->
