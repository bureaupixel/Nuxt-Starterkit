<!-- the template section contains the content of your page -->
<template>
    <div>
        <h1 class="title par2">Homepage</h1>
        <h2>What is in this repository?</h2>
        <p id="par1">This repository shows you the basics of building a Nuxt app with 2 pages and a navigation:</p>
        <p>The <strong>index.vue</strong> (located in the pages directory) file contains the classic structure with traditional CSS and serves as a hompepage.
        The <strong>example.vue</strong> (located in the pages directory) file demonstrates the structure using Tailwind.
        The <strong>navigation.vue</strong> file (located in the components directory) contains Nuxtlinks to those pages. </p>
        <h3 class="par2">What is the difference between the index.vue file and the example.vue?</h3>
        <p>The <strong>index.vue</strong> file is build with <strong>classic HTML and CSS</strong> using <strong>id's & classes</strong>. The html snippet of the title looks like:</p>
        <!-- HTML Code displayed inside <code> tag -->
        <code>
            &lt;h1 class="title"&gt;
            Homepage
            &lt;/h1&gt;
        </code>
        <!-- -->
        <p class="description">This code is classic HTML of an element that has the class named "title".</p>
        <p>The <strong>Example.vue</strong> file is build with <strong>Tailwind CSS</strong> and uses <strong>utility classes</strong>. The html snippet of the title rewritten with Tailwind looks like:</p>
        <!-- HTML Code displayed inside <code> tag -->
        <code>
            &lt;h1 class="text-6xl font-bold"&gt;
            Homepage
            &lt;/h1&gt;
        </code>
        <!-- -->
        <p class="description">This code is HTML of an element that has 2 Tailwind utility classes "text-6xl" and "font-bold".</p>
        <p><a href="https://bpedu2425.netlify.app/folders/frontenddesign/page8" target="_blank">Click here for more info on Tailwind from the coursebook.</a></p>
        <p><a href="https://tailwindcss.com/docs" target="_blank">Click here for more info on Tailwind and its utility classes.</a></p>
        <h2 class="par2">How to create new pages in your app?</h2>
        <p class="par3">Step 1: Copy the example.vue file to add new pages on your application.</p>
        <p>For instance: copy the example.vue file and name it example2.vue. Change the content of this new page using Tailwind utility classes.</p>
        <p class="par3"> Step 2: Create a new link in the navigation.vue file for each new page to make it accessible.</p>
        <!-- HTML Code displayed inside <code> tag -->
        <code>
            &lt;NuxtLink to="/example2"&gt;Link text shown in the navigation&lt;/NuxtLink&gt;
        </code>
        <!-- -->
        <p class="description">This code is HTML of a link to a file called "example2" and should be added in <strong>navigation.vue</strong>.</p>
        <h2 class="par2">How to setup and publish this repository?</h2>
        <p class="par3">This repository should be installed using the same procedure as we have installed other repositories for this course. For publication: create a new repository on Github, link the repo to a Netlify site and change the build settings and url.</p>   
        <p><a href="https://bpedu2425.netlify.app/folders/startguide/page2" target="_blank">Click here for more info on publishing with Github and Netlify.</a></p>
    </div>
</template>

<!-- the style section contains the design of your page -->
<!-- Here we use some classic stylesheets that refer to id's and classes-->
<style scoped>
h1{ 
    font-size: 4em;
    font-weight: bold;
}
h2{ 
    font-size: 1.5em;
    font-weight: bold;
    opacity: .5; 
}
h3{ 
    font-size: 1.2em;
    font-weight: bold;
    opacity: .5; 
}
.title{ 
    font-size: 1.5em;
    opacity: .8; 
}
#par1 { 
    font-weight: bold;
    font-size: larger;
}
.par2{ 
    font-weight: bold;
    margin-top: 2em;
}
.par3{ 
    font-weight: bold;
}
code{
    /* background-color: rgba(228, 88, 46, .4);*/
    background-color: rgb(177, 177, 177);
    border-radius: rounded;
    border-radius: 0.25rem;
    padding: 1em;
    margin-top: 1em;
    display: block;
}
.description{
    opacity: .5;
    font-size: .7em;
}
a{
    font-weight: bold;
    font-style: italic ;
}
</style>
