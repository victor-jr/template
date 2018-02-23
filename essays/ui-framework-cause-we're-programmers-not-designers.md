---
layout: essay
type: essay
title: UI Framework, Cause We're Programmers Not Designers
# All dates must be YYYY-MM-DD format!
date: 2018-02-22
labels:
  - UI Framework
  - Semantic UI
  - Bootstrap
---


## What is a UI Framework

<img class="ui tiny left circular floated image" src="../images/designer.jpeg">

A web User Interface (UI) framework is a tool used to develop visual interfaces for user interaction of your web application. The main benefit of a ui framework is the speed of scaling up a visual concept of your application without having to dive too much into the styling and layout. For coming up with a proof of concept these are excellent tools to work with. Eventually once your project gets more mature you would then tinker with your styles to make it more unique.

There is a learning curve to learning a ui framework but in my opinion it’s very minimal. Some people may argue why learn the ui framework when you could do the same thing with html and css. These people who say this are usually the same ones that argue against most frameworks whether it be bootstrap, semantic, react, angular, etc. To them I would say, if we are heading to the same destination sure you can choose to walk but I would rather take a car there. There’s nothing wrong with just using bare html and css but, for me personally, I like programming logic and functionality over visuals so I would rather spend more time on backend coding rather than frontend ui.  

## Bootstrap

<img class="ui tiny left circular floated image" src="../images/bootstrap-stack.png">

The first ui framework I used was Bootstrap and it was pretty great. I got my web applications up and running much quicker. If I wanted a button all I had to do was

```
<button class=”btn btn-default” style=”background:blue;”>Click me</button>
```
vs
```
<button class=”some-custom-class-i-made”>Click me</button>
```

That and Bootstrap’s grid system was all I needed to really get my development going. I no longer had to think too much about my page dimensions and most of all consideration of layout for mobile devices.

## Semantic

<img class="ui tiny left circular floated image" src="../images/semantic.png">

But then Semantic came out. Now rather than creating a button like before in Bootstrap now I can do the same but with

```
<button class=”blue ui button”>Click me</button>
```

Now looking at Bootstrap’s way vs Semantic’s we can see that semantic has a much more readable way of understanding their styling. This is very helpful when you’re not exactly sure of what styles you can apply but if you just write it as an english statement more than likely you’ll get it right.

Another reason why I choose to use semantic over bootstrap is its use of font awesome for their icons. When I used bootstrap I was bringing in font awesome for my icons rather than the glyphicons with bootstrap. This was pretty minor but when it was already in semantic it just helped push me to that framework.

There are other frameworks out there that I have not tried yet including Google’s Material UI and Bootstraps newer version Bootstrap 4 but for now Semantic is what I will be using.
