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

## Table of Contents
[1.](#how-to-edit-the-website) How to edit the website<br>
[2.](#temp) How the website was made

<br>

# How to edit the website


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

**How can I run a development server?**<br>
If you're a non-technical user, you don't need this part, 
but this will be useful if you'd like to improve 
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
:
```

<br>
<br>
<br>
