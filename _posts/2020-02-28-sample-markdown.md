[//]: # (---)

[//]: # (layout: post)

[//]: # (title: Sample blog post to learn markdown tips)

[//]: # (subtitle: There's lots to learn!)

[//]: # (gh-repo: daattali/beautiful-jekyll)

[//]: # (gh-badge: [star, fork, follow])

[//]: # (tags: [test])

[//]: # (comments: true)

[//]: # (mathjax: true)

[//]: # (author: Bill Smith)

[//]: # (---)

[//]: # ()
[//]: # ({: .box-success})

[//]: # (This is a demo post to show you how to write blog posts with markdown.  I strongly encourage you to [take 5 minutes to learn how to write in markdown]&#40;https://markdowntutorial.com/&#41; - it'll teach you how to transform regular text into bold/italics/tables/etc.<br/>I also encourage you to look at the [code that created this post]&#40;https://raw.githubusercontent.com/daattali/beautiful-jekyll/master/_posts/2020-02-28-sample-markdown.md&#41; to learn some more advanced tips about using markdown in Beautiful Jekyll.)

[//]: # ()
[//]: # (**Here is some bold text**)

[//]: # ()
[//]: # (## Here is a secondary heading)

[//]: # ()
[//]: # ([This is a link to a different site]&#40;https://deanattali.com/&#41; and [this is a link to a section inside this page]&#40;#local-urls&#41;.)

[//]: # ()
[//]: # (Here's a table:)

[//]: # ()
[//]: # (| Number | Next number | Previous number |)

[//]: # (| :------ |:--- | :--- |)

[//]: # (| Five | Six | Four |)

[//]: # (| Ten | Eleven | Nine |)

[//]: # (| Seven | Eight | Six |)

[//]: # (| Two | Three | One |)

[//]: # ()
[//]: # (You can use [MathJax]&#40;https://www.mathjax.org/&#41; to write LaTeX expressions. For example:)

[//]: # (When \\&#40;a \ne 0\\&#41;, there are two solutions to \\&#40;ax^2 + bx + c = 0\\&#41; and they are $$x = {-b \pm \sqrt{b^2-4ac} \over 2a}.$$)

[//]: # ()
[//]: # (How about a yummy crepe?)

[//]: # ()
[//]: # (![Crepe]&#40;https://beautifuljekyll.com/assets/img/crepe.jpg&#41;)

[//]: # ()
[//]: # (It can also be centered!)

[//]: # ()
[//]: # (![Crepe]&#40;https://beautifuljekyll.com/assets/img/crepe.jpg&#41;{: .mx-auto.d-block :})

[//]: # ()
[//]: # (Here's a code chunk:)

[//]: # ()
[//]: # (~~~)

[//]: # (var foo = function&#40;x&#41; {)

[//]: # (  return&#40;x + 5&#41;;)

[//]: # (})

[//]: # (foo&#40;3&#41;)

[//]: # (~~~)

[//]: # ()
[//]: # (And here is the same code with syntax highlighting:)

[//]: # ()
[//]: # (```javascript)

[//]: # (var foo = function&#40;x&#41; {)

[//]: # (  return&#40;x + 5&#41;;)

[//]: # (})

[//]: # (foo&#40;3&#41;)

[//]: # (```)

[//]: # ()
[//]: # (And here is the same code yet again but with line numbers:)

[//]: # ()
[//]: # ({% highlight javascript linenos %})

[//]: # (var foo = function&#40;x&#41; {)

[//]: # (  return&#40;x + 5&#41;;)

[//]: # (})

[//]: # (foo&#40;3&#41;)

[//]: # ({% endhighlight %})

[//]: # ()
[//]: # (## Boxes)

[//]: # (You can add notification, warning and error boxes like this:)

[//]: # ()
[//]: # (### Notification)

[//]: # ()
[//]: # ({: .box-note})

[//]: # (**Note:** This is a notification box.)

[//]: # ()
[//]: # (### Warning)

[//]: # ()
[//]: # ({: .box-warning})

[//]: # (**Warning:** This is a warning box.)

[//]: # ()
[//]: # (### Error)

[//]: # ()
[//]: # ({: .box-error})

[//]: # (**Error:** This is an error box.)

[//]: # ()
[//]: # (## Local URLs in project sites {#local-urls})

[//]: # ()
[//]: # (When hosting a *project site* on GitHub Pages &#40;for example, `https://USERNAME.github.io/MyProject`&#41;, URLs that begin with `/` and refer to local files may not work correctly due to how the root URL &#40;`/`&#41; is interpreted by GitHub Pages. You can read more about it [in the FAQ]&#40;https://beautifuljekyll.com/faq/#links-in-project-page&#41;. To demonstrate the issue, the following local image will be broken **if your site is a project site:**)

[//]: # ()
[//]: # (![Crepe]&#40;/assets/img/crepe.jpg&#41;)

[//]: # ()
[//]: # (If the above image is broken, then you'll need to follow the instructions [in the FAQ]&#40;https://beautifuljekyll.com/faq/#links-in-project-page&#41;. Here is proof that it can be fixed:)

[//]: # ()
[//]: # (![Crepe]&#40;{{ '/assets/img/crepe.jpg' | relative_url }}&#41;)

[//]: # ()
[//]: # (<details markdown="1">)

[//]: # (<summary>Click here!</summary>)

[//]: # (Here you can see an **expandable** section)

[//]: # (</details>)
