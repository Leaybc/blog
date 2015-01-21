---
layout: post
title:  "Hello World"
date:   2015-02-09 10:45:32
categories: jekyll update
---

#### print "hello world" in various language ###

{% highlight java %}
public Class PrintHello{
  public void sayHello(){
    System.out.println("Hello Wolrd");
  }

  public static void main(String[] args){
    PrintHello hello = new PrintHello();
    hello.sayHello();
  }
}
{% endhighlight %}