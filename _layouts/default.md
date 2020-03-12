---
---
<!DOCTYPE html>
<html>
<head>
  <meta charset="utf-8">
  <meta name="viewport" content="width=device-width, initial-scale=1">
  <span style="display:inline-block; width: 100px;"></span>
  <title>{{ page.title }} - {{site.title}}</title>
</head>

<body>
<header>
    <nav>
        <ul>
            <a href="{{site.baseurl}}/">Home</a>
            <a href="{{site.baseurl}}/publications">Publications</a>
            <a href="{{site.baseurl}}/teaching">Teaching</a>
            <a href="{{site.baseurl}}/students">Students</a>
        </ul>
    </nav>
    <a class="title-a" href="{{site.baseurl}}/"><h1 class="title">{{site.title}}</h1></a>
</header>
      
  
  {{ content }}
