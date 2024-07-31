# Layout/visual

- @rdela: a more [MDN](https://developer.mozilla.org/) style layout, moving our table of “Contents” outline and jump links from the top of the article to a sidebar on the right, if the screen is wide enough, that follows you down the page and highlights the section of your current scroll position. See for example: [<details>: The Details disclosure element](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/details)
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
  - [@tatianamac](https://github.com/tatianamac) followed up Part I with [Beginner's Guide to Eleventy \[Part II\]](https://www.tatianamac.com/posts/beginner-eleventy-tutorial-partii/), and I'd add to Michelle's thoughts that the illustrations (in Part I) are fantastic.
  - [Itsiest, Bitsiest Eleventy Tutorial](https://sia.codes/posts/itsiest-bitsiest-eleventy-tutorial/)
    Want to get started with Eleventy but feel overwhelmed? Try out this pared-down tutorial
  - 🔖 [Eleventy](https://sia.codes/tags/Eleventy/)

# Other outcomes

- @rdela: Empower more people to contribute to and participate in documenting the 11ty ecosystem.
- @riewarden: (paraphrased) Ensure docs are written with non-technical people in mind.
