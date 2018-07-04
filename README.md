
## Blog listing page (Full content or Teaser)
For showing full content or teaser on blog listing page there is an option for setting in "/hrocket/src/content/blogs_list/blogs.Rmd"<br />
teaser: "full"  (For full content) <br />
teaser: "half"  (For content as teaser)

## Path Settings
For resolving relative path issue user can adjust some configuration variables in config.toml as follow<br />
1) for a domain setup <br />
publishDir = ""<br />
logoLink = "/"<br />
[[mainMenu]]<br />
  name = "Home"<br />
  url = "/"<br />
[[mainMenu]]<br />
  name = "About"<br />
  url = "/content/pages/about"<br />
[[mainMenu]]<br />
  name = "Blogs"<br />
  url = "/content/pages/blogs"<br />

2) for github pages (when user's github page repo is "testhrocket")<br />
publishDir = "/testhrocket"<br />
logoLink = "/testhrocket"<br />
[[mainMenu]]<br />
  name = "Home"<br />
  url = "/testhrocket"<br />
[[mainMenu]]<br />
  name = "About"<br />
  url = "/testhrocket/content/pages/about"<br />
[[mainMenu]]<br />
  name = "Blogs"<br />
  url = "/testhrocket/content/pages/blogs"<br />

