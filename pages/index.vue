<template>
  <main>
    <Navigation />
    <Header :pageInfo="siteInfo" />
    <section class="flex flex-wrap m-10">
      <p class="m-10">
        In the last two weeks we as Web Development students, at SAIT (Southern
        Institute of Technology), we have been exposed to several features of
        these three frameworks. With all the new libraries and frameworks it is
        pretty hard to keep up with all of them, and that is if you can even
        decide which ones are worth spending time one. VueJS is gaining
        continuous popularity lately and considered as one of the best
        JavaScript (JS ) framework. For developers who have experience Vue.js
        and also for those who want to change areas, there are many
        opportunities with **Vue.js, Tailwindcss and Nuxt.js.** To put it into
        context, we have to make it clear that this article is not about the
        perfect choice that will work for all cases without exception, even why
        this tool has yet to be created. We will be presented here a short
        overview about the ones of the most treding and robust solutions used
        for creating websites and that, for sure, can be the solution to some of
        your current pains.
      </p>

      <h3 class="text-3xl bg-black text-white p-1">
        Here some impressions from this unique team:
      </h3>
      <div class="p-5">
        <cite class="text-2xl">~Evan</cite>
        <blockquote>
          "Enjoyed learning Nuxt for the most part, I think because of the
          amount of time we had to learn it in class I’m still a little unsure
          of all the ins and outs. I enjoy doing Vue and working with components
          and the pages they load to. Tailwind seems interesting, I’m not sure
          if I enjoy using it but I guess we’ll see after this project! Maybe
          this site will look nice, maybe it’ll be a disgusting mess."
        </blockquote>
      </div>
      <div class="p-5">
        <cite class="text-2xl">~Fesal</cite>
        <blockquote>
          "I enjoyed working with Nuxt and I can see how it could save me time,
          like doing multiple pages and then just simply calling them from the
          components. I enjoyed working with both v-for and mustache syntaxes, I
          did work with v-html/v-text but in future, I don't see any benefit of
          using v-html/v-text over the mustache? also, one thing I did not like
          about the v-for is that it's not as simple as the regular for loop
          just like in JS, don't get me wrong, it's easy once you do it and you
          get it to work but I still prefer the regular for loop."
        </blockquote>
      </div>
      <div class="p-5">
        <cite class="text-2xl">~Mysia</cite>
        <blockquote>
          "What I've like most about this Vue.js was the usability of the
          components and how they work together. Tailwindcss it's seemed to be
          complicated at the first sight but it gets easier to use as it has a
          very long and easy documentation, however it certainly will help you
          to save some time in large projects design. About Nuxt.js one thing
          that let me down was you can't find many manual configurations to be
          done, instead the documentation guides you to follow the directory
          structure that is automatically generated when creating a new
          project."
        </blockquote>
      </div>
      <div class="p-5">
        <cite class="text-2xl">~Jean-Marc</cite>
        <blockquote>
          "We hope this brief article can help you to spend less time on setup
          and more time on what really matters: solving problems and building
          great apps with Vue JS, Nuxt.js and Tailwind CSS. In our Gallery you
          will find some of our projects using those three frameworks."
        </blockquote>
      </div>
    </section>
    <Footer :pageInfo="siteInfo" />
  </main>
</template>

<script>
export default {
  data() {
    return {
      siteInfo: {
        pageName: "Home",
        author: "FastVue",
      },
    };
  },
};
</script>