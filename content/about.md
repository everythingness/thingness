why pay obsidian $8 a month to publish some obsidian notes when you can use flowershow?

---------------------------------------------------------

well depends on whether paying $8 a month is a problem for you.
and whether or not you can be bothered to fuck around.

it involves github and a thing called vercel which i didn't know about.

it is all described in detail here


-----------------------------------------------------------------

and then you want to get rid of the branding
see here
https://flowershow.app/docs/config

const config = {
  title: "My Awesome Blog",
  description: "This is my awesome blog built with Flowershow",
  author: "John",
  logo: "/images/logo.svg",
  domain: "https://john.app/",
  // links to the pages you want to link to in the navbar and in the footer
  navLinks: [{ href: "/about", name: "About" }],
};

export default config;