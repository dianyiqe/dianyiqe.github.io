---
layout: post
title:  "To build a awesome blog with Jekyll"
date:   2016-05-14 
categories: how to make the use of jekyll 
---
First creat a repository with name `usrname.github.io`,download the repository use command 

{% highlight bash %}
git clone https://github.com/usrname/usrname.github.io.git
{% endhighlight bash %}

Make sure your computer already setup gem before make install jekyll .

{% highlight bash %}
sudo gem install jekyll
jekyll new usrblog
cd new usrblog| jekyll serve
{% endhighlight bash %}

Then open the `http://localhost:4000 `you can see the new usrblog in browser

Last use the git command push the folder named of `usename.github.io`  to github

{% highlight bash %}
cd usename.github.io
git init
git commit -m "message"
git push origin master
{% endhighlight bash %}
