## Research & Project approval (Part 2)

## Concepts
- Maze project
- [3 Ways to Make a Portfolio Project Great](https://intranet.alxswe.com/concepts/135)

```
This concept is written with many examples of internet applications because URLs are easiest to share, but these suggestions are helpful to keep in mind for all types of software you might develop for your Portfolio Project.

1. The Logged Out Experience
Anyone you show your project to will likely have only a few minutes to take a look. The worst way to spend these few minutes is to throw up a log in screen. Clearly a log in is helpful for tailoring an experience and providing a persistent experience. Let take a quick tour to see how other websites behave.
```
### Logged out experience examples
> Many of the most heavily trafficked web sites greet strangers with a locked-out landing page. If you want to experience this, open an anonymous browser and check out [Facebook](https://web.facebook.com/?_rdc=1&_rdr), [Pinterest](https://www.pinterest.com/), and [Github](https://github.com/). These power brands can rely on users flocking to their site with the intention of signing up because they already know they want to use the product being offered.
> 
- Other sites are not as well known, and must rely on passive traffic where users come to the site to explore functionality and evaluate whether the experience is for them. Some have a logged out experience, but more clearly demonstrate how their product can be used. 
- [Asana](https://asana.com/) and [Trello](https://trello.com/) are examples of this. Both landing pages have a demo and helpful information to inform browsers how their productivity might be positively impacted.
- ![img](https://s3.amazonaws.com/alx-intranet.hbtn.io/uploads/medias/2019/7/0254b5ad94ac07a84269.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Credential=AKIARDDGGGOUSBVO6H7D%2F20230521%2Fus-east-1%2Fs3%2Faws4_request&X-Amz-Date=20230521T174739Z&X-Amz-Expires=86400&X-Amz-SignedHeaders=host&X-Amz-Signature=d52e4f0a12ac8694ad4157eaeb5b589f05ba385bbb36b0f52b7531d71b5f44e8)

- Another path is for websites to completely expose their functionality with no requirement to login. Some sites do this because the experience would be no different whether the user was logged in or out, and the author is not interested in the inherent risk of storing credentials. Others do this because the anonymous experience is core to their functionality (like [Craigslist!](https://sfbay.craigslist.org/))
>
### The “Quake Tracker” App is a great logged out example:
 - The app provides a visualization of earthquake events around the world across time. There is no need to log in because there is no additional information the user could provide to alter the experience.

### The “Savings” App is another great example:
- This app allows you to return to your work in progress by creating a uniquely identified URL. Since the developers chose not to present and capture any identifying information, it becomes perfectly okay to expose savings calculations. Of course, they do not account for an interloper editing your page, but the purpose of this app seems to be as a demonstration of the developer’s engineering abilities (see [ToMakeOrNotToMake](https://tomakeornottomake.com/) ) rather than an actual app where your personal savings information should be stored.
-
- Think about ways you can expose the core experience (the “fun”) without requiring a login.

2. A Data-Rich Experience
```
We want to avoid the experience where an employer or ally might stumble upon your final project, take the time to login and find that they are greeted with emptiness. Take the time to think through how you might populate some presets into your software, or ingest data to populate your experience. Many apps go to great lengths to ensure the logged-in experience feels warm and inviting.

Example: Airtable
Airtable is a relatively complex application (compared to a to-do list) where there may be a learning curve to use the application. The team behind Airtable has added some sample ‘bases’, a default workspace, and pops up a personal message with a tutorial video upon logging in.
```
- ![im](https://s3.amazonaws.com/alx-intranet.hbtn.io/uploads/medias/2019/7/533600168a5efdaddbda.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Credential=AKIARDDGGGOUSBVO6H7D%2F20230521%2Fus-east-1%2Fs3%2Faws4_request&X-Amz-Date=20230521T174739Z&X-Amz-Expires=86400&X-Amz-SignedHeaders=host&X-Amz-Signature=5641f854a9d1051b70fb17fad021d3f623c2a96b7fdccaec165e7a7253c6b533)

> This might be a strategy you want to use for your app. You may want to create some default data, or a tutorial to bring your app to life upon logging in.

- example: The [Findacar]() app is a portfolio project piece created by Diana Lozano. She has created a single page app to search rental cars by date, time and location. She has sourced the data from the Hotwire API and this has resulted in a fantastic data-rich (and logged out) experience!
- ![ex](https://s3.amazonaws.com/alx-intranet.hbtn.io/uploads/medias/2019/7/41f95c992d17c94f1d2c.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Credential=AKIARDDGGGOUSBVO6H7D%2F20230521%2Fus-east-1%2Fs3%2Faws4_request&X-Amz-Date=20230521T174739Z&X-Amz-Expires=86400&X-Amz-SignedHeaders=host&X-Amz-Signature=bc24b3dfe0915bcb4ee7448d8351af8ee687400768fa6e76288371c4b1a56bd9)

- Finally, if you don’t have a web-focused final project, that doesn’t mean you can’t have a rich experience. take a look at [Moro](https://github.com/getmoro/moro)
- ![uo](https://s3.amazonaws.com/alx-intranet.hbtn.io/uploads/medias/2019/7/277bbc8d0d3025e9bde6.gif?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Credential=AKIARDDGGGOUSBVO6H7D%2F20230521%2Fus-east-1%2Fs3%2Faws4_request&X-Amz-Date=20230521T174739Z&X-Amz-Expires=86400&X-Amz-SignedHeaders=host&X-Amz-Signature=d8bdc5996bbe8905613f8afaa55f8bd4c4f2dd29f7c7efe5a5a0e34d64226341)
- It’s clear there is extra effort to creating some extra text for formatting sake. The documentation is also extensive with rich examples.

3. Showcase yourself

```
It’s not enough that your Portfolio Project is an interesting and engaging experience. It’s necessary that the viewer of your app understands you created this app as a demo of your amazing skillset. Somewhere on your app’s page, you’ll want to link to the source code for this final project’s Github, or your personal web site. Here are some examples:

Little corner banner
This banner could say “Hire Me” or be more subtle, like this GitHub Octocat in the top-right which links to the source code of this project. 

Subtle footer mention
Another obvious place to link to your final project’s github is the footer of the project page. Here’s an example: 

Call out in a section, with a photo!
Be proud of your work and put your face on it with an invitation for people to learn more or connect with you through Twitter, LinkedIn, etc. 
```

- 



