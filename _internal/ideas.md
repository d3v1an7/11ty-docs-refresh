# Layout/visual

- @rdela: a more [MDN](https://developer.mozilla.org/) style layout, moving our table of “Contents” outline and jump links from the top of the article to a sidebar on the right, if the screen is wide enough, that follows you down the page and highlights the section of your current scroll position. See for example: [&lt;details&gt;: The Details disclosure element](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/details)
  - Worth noting that [Tugboat](https://tugboat.11ty.dev/) has this already on the left sidebar via [table-of-contents.webc](https://github.com/11ty/tugboat/blob/main/_components/table-of-contents.webc)
- @rdela: One really long page can feel overwhelming, although it does allow one to use find on page, which can be super helpful to find all occurrences of a term.

# Content

- @rknightuk: (paraphrased) A collection of first-party tutorials that cover common needs (One for a blog, a marketing site, portfolio, one that pulls in external data to make posts/pages, maybe one that pulls all those concepts together.)
- @rdela: Our [Community](https://www.11ty.dev/docs/community/) page could probably improve by evaluating and incorporating good parts of [MDN’s Commuity Page](https://developer.mozilla.org/en-US/community), which links to their [Getting started with MDN Web Docs](https://developer.mozilla.org/en-US/docs/MDN/Community/Contributing/Getting_started) guide to contributing.

# Topics

### WebC

- @rdela: [WebC](https://www.11ty.dev/docs/languages/webc/) by itself seems expansive enough to have a whole section of docs, examples, and learning paths.
  - I like the [Recipes on 11ty ♥ WebC](https://11tywebcfun.netlify.app/recipes/) by [@darthmall](https://github.com/darthmall)
  - whose [Introduction to WebC](https://11ty.rocks/posts/introduction-webc/) also...*rocks!*
  - as does [Understanding WebC Features and Concepts](https://11ty.rocks/posts/understanding-webc-features-and-concepts/) by [@5t3ph](https://github.com/5t3ph) (particularly helped me [debugging errors](https://github.com/rdela/eleventeen/pull/40#issuecomment-2243329000)). The rest of 11ty Rocks! is also worth taking stock of, I hear it mentioned frequently as a learning resource.

### Getting started

- @rdela: Worth mining [11ty Bundle](https://11tybundle.dev/categories/getting-started/) by [@bobmonsour](https://github.com/bobmonsour), particularly the Getting Started section for learning paths
  - same for [@nhoizey](https://github.com/nhoizey)'s [Eleventy tag](https://nicolas-hoizey.com/tags/eleventy/)
  - plus [@rknightuk](https://github.com/rknightuk)'s [#Eleventy](https://rknight.me/blog/tags/eleventy/)
  - [Eleventy Starter Project Updates](https://css-irl.info/eleventy-starter-projects-updates/) by [@mbarker84](https://github.com/mbarker84)
  - [Going Lean](https://lea.verou.me/blog/2023/going-lean/) and follow-up [11ty: Index ALL the things!](https://lea.verou.me/blog/2023/11ty-indices/) by [@LeaVerou](https://github.com/LeaVerou), whose "Broken page" issue template link ("Something not working? Report broken page" in right sidebar) might inspire another link on docs pages like our "Edit this page" (which we could potentially make more prominent), maybe "Missing something?"
  - [Migrating my site from NextJS to Eleventy](https://sandroroth.com/blog/migrationl-to-eleventy/) by [@rothsandro](https://github.com/rothsandro)
  - which mentions [Organizing the Eleventy config file](https://www.lenesaile.com/en/blog/organizing-the-eleventy-config-file/) by [@madrilene](https://github.com/madrilene)
  - [Nested pagination with 11ty](https://benwhite.com.au/blog/nested-pagination/) by, wait for it, [@d3v1an7](https://github.com/d3v1an7)
  - [From Gatsby to Eleventy: Choosing a Static Site Generator for a Personal Site](https://css-irl.info/from-gatsby-to-eleventy/), a precursor to [Eleventy Starter Project Updates](https://css-irl.info/eleventy-starter-projects-updates/) above also by Michelle Barker, has this passage:
    > Learning Eleventy
    >
    > One area where I would say Eleventy is a little lacking is the documentation. It feels slightly harder to navigate than Gatsby's docs, in that you kind of need to have an idea of what you're looking for. The [Getting Started](https://www.11ty.dev/docs/getting-started/) tutorial assumes a certain level of knowledge, and in that regard it's not quite as beginner-friendly for someone who might not already be familiar with static site generators.
    >
    > However, there are a plenty of tutorials around to help you get started:
    >
    > -   [Build your own Blog from Scratch using Eleventy](https://www.filamentgroup.com/lab/build-a-blog/) by the Filament Group
    > -   [Learn Eleventy From Scratch](https://piccalil.li/course/learn-eleventy-from-scratch/) (paid course) -- a deep dive that goes beyond Eleventy alone, from Andy Bell
    > -   [Beginner's Guide to Eleventy](https://tatianamac.com/posts/beginner-eleventy-tutorial-parti/) by Tatiana Mac. This is great because it actually explains what a static site generator is, and the pros and cons.
  - Notably, [@Andy-set-studio](https://github.com/Andy-set-studio) writes:
    > The content of \[[Learn Eleventy From Scratch](https://learneleventyfromscratch.com/)\] was written in May 2020, so parts will be outdated. There's no immediate plan to do a full update, but this course is now open source, so if you see an issue, [please raise an issue](https://github.com/Andy-set-studio/learneleventyfromscratch.com).
    
    (See also [incomplete](https://github.com/uncenter/learn-eleventy/issues/3) [fork/“alternative version”](https://learn-eleventy.pages.dev/) by @uncenter, who is “pretty active in the Discord server's help forum,” “happy to help with this process,” and also started working on a [project scaffolding CLI](https://github.com/11ty/create/issues/1): “Never got too far with it but would love to see something similar adopted as an official solution!”)
  - [@tatianamac](https://github.com/tatianamac) followed up Part I with [Beginner's Guide to Eleventy \[Part II\]](https://www.tatianamac.com/posts/beginner-eleventy-tutorial-partii/), and I'd add to Michelle's thoughts that the illustrations (in Part I) are fantastic.
  - [Itsiest, Bitsiest Eleventy Tutorial](https://sia.codes/posts/itsiest-bitsiest-eleventy-tutorial/)
    Want to get started with Eleventy but feel overwhelmed? Try out this pared-down tutorial
  - 🔖 [Eleventy](https://sia.codes/tags/Eleventy/)
  - [Eleventy Beginner Tutorial Series](https://cloudcannon.com/tutorials/eleventy-beginner-tutorial/) Learn the basics of Eleventy by building a complete site with the help of this six-part series by @mneumegen
  - [Getting started with Eleventy](https://www.seanmcp.com/gardens/getting-started-with-eleventy/) by @seanmcp
    > Eleventy has [“Get Started” documentation](https://www.11ty.dev/docs/) that shows you how to get from a single markdown file to a built site. That is a nice “proof of idea”, but I haven’t found it to be a helpful way to actually get started with Eleventy. This garden aims to be a better guide for building a simple Eleventy site from scratch.
  - [Curso Eleventy (Spanish video)](https://www.youtube.com/watch?v=yCF9l4_E5rI) by @jonmircha
    > En este curso te enseño a trabajar con Eleventy, un generador de sitios estáticos rápido, accesible y minimalista.
    > 📦 RECURSOS:
    > 🦊 Mis Cursos - https://jonmircha.com/cursos
    > 🛢️ Repositorio de Códigos en GitHub - https://github.com/jonmircha/starter-project-eleventy-github-pages
    (has accompanying code repo linked above)
  - [Migrating to Eleventy](https://11tybundle.dev/categories/migrating-to-eleventy/) category on 11ty Bundle. Note a search for “Jekyll” turns up much more in Dates and Layouts categories as well.
  - @JackieGable: After trying 3 times before (in the past 2 years) to transition my website from Jekyll to Eleventy, I finally decided it was time to get serious about it. The Eleventy documentation was the problem for me each time I tried to make the move. Even though it's extensive, it's all-over-the-place and not beginner friendly. So, I began searching YouTube for tutorials on getting started with Eleventy, and I was disappointed. Zach teaches a few but he doesn't approach it from a beginner's point of view. […]  I'm planning on reaching out to Brad Traversy, (https://www.traversymedia.com) my favorite YouTube teacher, to see if he might be interested in teaching a beginner's course on Eleventy. Brad knows how to explain things in simple terms (teach me like I'm Five) and doesn't assume anything.
    I truly believe that more people would learn to use Eleventy if there was better documentation and video tutorials available. Since I am a beginner to Eleventy, I can certainly contribute the documentation that I write for myself once I learn a new concept.

# Other outcomes

- @rdela: Empower more people to contribute to and participate in documenting the 11ty ecosystem.
- @riewarden: (paraphrased) Ensure docs are written with non-technical people in mind.

# Entry points

@rdela: 

It’s interesting to think about entry points to the docs as something that could be improved. In order of discovery, points of first contact, we have: 

1. “Eleventy is a simpler static site generator”—An aside: whether or not “simpler” is accurate 😅, I switched to “award-winning open source site generator” on [eleventeen](https://eleventeen.blog/about/), which I got from [Zach’s site](https://www.zachleat.com/). I definitely think Eleventy is *elegant*, powerful, and performant, and [in the words of Dan Forsyth](https://rdela.tumblr.com/post/13699704519), “Elegance is power cloaked in simplicity.” Maybe this emphasis on simplicity instead of, say, elegance and power, makes people feel alienated that they didn’t immediately grasp, and become adept, or even expert at its “simpler” workflow.

2. Below that [Homepage Quick Start](https://www.11ty.dev/#quick-start) which links on to [Docs](https://www.11ty.dev/docs/), see below, and [6 minutes to Build a Blog from Scratch](https://www.youtube.com/watch?v=kzf9A9tkkl4) on YouTube, subtly. Further down on the homepage we get: 
   - Sponsors (&lt;sponsors-list&gt;) (maybe better further down the page?)
   - then [News from the Blog](https://www.11ty.dev/#news-from-the-blog) (useful, could come sooner in my opinion)
   - [Why should you use Eleventy?](https://www.11ty.dev/#why-should-you-use-eleventy) (ditto)
   - then [Open Collective Supporters](https://www.11ty.dev/#open-collective-supporters) &lt;facepile&gt; (why not next to sponsors? maybe further down the page?)
   - THEN GIANT DOCS BUTTON (literally &lt;giant-docs-button&gt;)
   - then [Built With Eleventy](https://www.11ty.dev/#built-with-eleventy) (which why not nearer to Why use &lt;logo-cloud&gt; ? Also this and everything below it gets covered by THE GIANT DOCS BUTTON, which while funny is not a great experience)
   - then author &lt;facepile&gt; (maybe further down the page? or on a separate page? facepile overkill?)
   - then [Don’t take my word for it 🌈](https://www.11ty.dev/#dont-take-my-word-for-it-%F0%9F%8C%88-rainbow) testimonial quotes
   - then [Alternatives](https://www.11ty.dev/#alternatives)
   - and then finally [Subscribe to the 11ty Newsletter](https://www.11ty.dev/#subscribe-to-the-11ty-newsletter) and the footer links—See [Edit Page/Missing something?](https://github.com/11ty/eleventy/issues/3388#issuecomment-2256675366) thoughts above, also thought “Improve these docs” might be good in conjunction with “Missing something?” or on its own—and is [Contributor Account](https://www.11ty.dev/docs/account/) still a thing?

3. [Docs > Get Started](https://www.11ty.dev/docs/#get-started)

4. Then kind of a buffet of of [Tutorials and Starter Projects](https://www.11ty.dev/docs/#tutorials-and-starter-projects) leading with Eleventy Base Blog and including some of the ones I added here without referencing this.

5. Then aforementioned [More From the Community](https://www.11ty.dev/docs/#more-from-the-community) that two links at the beginning of this comment came from.

6. Then puzzlingly, another [Getting Started:](https://www.11ty.dev/docs/#getting-started) with buttons labeled…

   - [Command Line Usage](https://www.11ty.dev/docs/usage/)
   - [Glossary](https://www.11ty.dev/docs/glossary/)
   - [Tutorials](https://www.11ty.dev/docs/tutorials/)
   - [Starter Projects](https://www.11ty.dev/docs/starter/)
   - [Performance](https://www.11ty.dev/docs/performance/)
   - [Programmatic API](https://www.11ty.dev/docs/programmatic/)
   - [Deployment & Hosting](https://www.11ty.dev/docs/deployment/)
   - [Using a CMS](https://www.11ty.dev/docs/cms/)

   Feels like this would be more aptly named “Keep Exploring,” “Keep Learning,” “Other Topics,” or similar.

7. [Subscribe to the 11ty Newsletter](https://www.11ty.dev/docs/#subscribe-to-the-11ty-newsletter)

8. [Sponsors](https://www.11ty.dev/docs/#gold-sponsors)

9. [Supporters](https://www.11ty.dev/docs/#supporters) facepile

10. Star Eleventy on GitHub!

11. Footer links

Another interesting thing to think about Jonathan MirCha’s Curso Eleventy brings up is internationalization. Whether 11ty is ready to take that on is the first conversation there I suppose.