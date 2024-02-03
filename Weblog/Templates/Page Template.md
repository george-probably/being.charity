---
Title: Page Template
Type: Template
---

<!DOCTYPE html>
<html lang="en">
<head>
<title>{post-title}{separator}{weblog-title}</title>
<meta charset="utf-8">
<link rel="icon" type="image/x-icon" href="https://raw.githubusercontent.com/george-probably/being.charity/main/Images/favicon.png">
<meta name="viewport" content="width=device-width, initial-scale=1">
<meta name="theme-color" content="#288cf0">
<meta name="apple-mobile-web-app-status-bar-style" content="#288cf0">
<link rel="stylesheet" type="text/css" href="/style.css">
<style>
@import url('https://static.omg.lol/type/font-honey.css');
@import url('https://static.omg.lol/type/fontawesome-free/css/all.css');
@import url('https://fonts.bunny.net/css?family=open-sans:500,800&display=swap');
:root {
    --foreground: #000;
    --background: #e9ebf0;
    --link: #d92b45;
    --unimportant: #000;
    --articleBG: #1c62a8;
    --articleBorder: #083e73;
}

@media (prefers-color-scheme: dark){
    :root {
    --foreground: #000;
    --background: #e9ebf0;
    --link: #d92b45;
    --unimportant: #000;
    --articleBG: #1c62a8;
    --articleBorder: #288cf0;
    }
}
</style>
</head>

<body>

<header><h1 class="weblog-title"><a style="text-decoration:none; border-bottom:0px" href="{base-path}"><i class="fa-solid fa-heart"></i> {weblog-title}</a></h1><div class="nav-box"> {navigation} </div></header>

<main>

<div class="flex-column">

<div class="box">
{body}
</div>
</div>

</main>

</main>
<footer>
<p>kindness binds us</p>
</footer>
</body>
</html>