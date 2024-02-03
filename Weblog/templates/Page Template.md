---
Title: Page Template
Type: Template
---

<!DOCTYPE html>
<html lang="en">
<head>
<title>{post-title}{separator}{weblog-title}</title>
<meta charset="utf-8">
<link rel="icon" type="image/x-icon" href="https://raw.githubusercontent.com/george-probably/prami.partners/main/Images/PramiPartners.svg">
<meta name="viewport" content="width=device-width, initial-scale=1">
<meta name="theme-color" content="#C8A2C8">
<meta name="apple-mobile-web-app-status-bar-style" content="#C8A2C8">
<link rel="stylesheet" type="text/css" href="/style.css">
<link rel="me" href="https://social.lol/@pramipartners">
<style>
@import url('https://static.omg.lol/type/font-honey.css');
@import url('https://static.omg.lol/type/fontawesome-free/css/all.css');
@import url('https://fonts.bunny.net/css?family=open-sans:500,800&display=swap');
:root {
    --foreground: #eee;
    --background: #C8A2C8;
    --link: #eee;
    --unimportant: #ebebeb;
    --articleBG: #BB8BBB;
    --articleBorder: #9A5B9A;
}

@media (prefers-color-scheme: dark){
    :root {
    --foreground: #eee;
    --background: #9A5B9A;
    --link: #eee;
    --unimportant: #ebebeb;
    --articleBG: #BB8BBB;
    --articleBorder: #C8A2C8;
    }
}
</style>
</head>

<body>

<header><h1 class="weblog-title"><a style="text-decoration:none; border-bottom:0px" href="{base-path}"> <img src="https://raw.githubusercontent.com/george-probably/probably.blog/main/Images/PramiPartners.svg" style="height:1em;width:1em;" alt="Prami Partners Logo">{weblog-title}</a></h1></header>

<main>

<div class="flex-column">

<div class="nav-box"> {navigation} </div>

<div class="box">
{body}
</div>
</div>

</main>
<footer>
<p><a href="https://omg.lol">omg.lol</a> × <a href="https://george.chachanidze.com/">George, Probably</a><br> kindness binds us</p>
</footer>
</body>
</html>