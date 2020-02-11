# BeCode: Newsletter

> ⚙ A simple blog for marketing - hosting newsletters articles

* * *

Using [hexo](//hexo.io).

## Add/edit a post

In [source/_post](./source/_post) folder, **create** a new file.    
Then, give it a name, without space and at the end, give it an extension. *For example: newsletter-june2020.md*    
Do not forget to add the three first line on the top of the file. It's about the title of the post.

**To modify**, just click on the file you wanna modify and then click on [edit].    
You want to **preview** your modification before commiting? Click on [preview changes] on the top of the edition area.

You don't remember how to use markdown? [Your cheat sheet is here!](https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet)

There's templates in [scaffolds](./scaffolds).

Follow Hexo's [documentation](//hexo.io/docs/writing) for writing.

### Add an image to a post

Simply add the image file into [source/images](./source/images) folder, then add the image in your markdown with the `/images` prefix.  
> For instance, if you add the file `best-gif-ever.gif` in the `source/images` folder, to use it, type the following code in your markdown: `![image description](/images/best-gif-ever.gif)`.

## Deploy

You don't need to do anything. There's a [workflow](./.github/workflows/deploy.yml) configured to build & deploy the blog _on each commit_. You can see the progress of the deploy workflow on the [Actions](//github.com/becodeorg/nyooz/actions) tab of the repository.

> 👉 **NOTE:** there's a small _cache TTL_ on GitHub Pages - you may need to wait up to ten minutes to see your changes online.

* * *
