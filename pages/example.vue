<template>
    <div>
        <p class="text-6xl font-bold">
            Tailwind example
        </p>
        <!-- The follwoing code sets the text in a font size of 3xl and the font-weight to bold -->
        <p class="text-3xl font-bold">
            Duis imperdiet mi augue. Vestibulum ante ipsum primis in faucibus orci luctus et ultrices posuere cubilia curae; Duis convallis justo vitae lorem consequat consequat. Praesent aliquam neque lorem, sed rhoncus ex fermentum non. In tincidunt facilisis justo sit amet commodo. Donec convallis dolor neque, non ultricies nisi maximus vitae. Proin vel elit nisi.
        </p>
        <p class="font-bold">
            <a href="https://tailwindcss.com/docs/font-size" target="_blank">Click here for more info on Tailwind and Typography.</a>
        </p>
        <hr>
        <!-- -->
        <!-- The following code sets a text in a box with padding 5 and a background color that changes when the darkmode is activated-->
        <p class="p-5 bg-slate-50 dark:bg-zinc-900">
            Duis imperdiet mi augue. Vestibulum ante ipsum primis in faucibus orci luctus et ultrices posuere cubilia curae; Duis convallis justo vitae lorem consequat consequat. Praesent aliquam neque lorem, sed rhoncus ex fermentum non. In tincidunt facilisis justo sit amet commodo. Donec convallis dolor neque, non ultricies nisi maximus vitae. Proin vel elit nisi.
        </p>
        <p class="font-bold">
            <a href="https://tailwindcss.com/docs/background-color" target="_blank">Click here for more info on Tailwind and Background colors.</a>
        </p>
        <hr>
        <!-- -->
        <p>
            <!-- The following line shows how to include an image that is stored in public/images -->
            <NuxtImg src="images/image1.jpg" fit="cover" />
            <p class="font-bold">
                <a href="https://image.nuxt.com" target="_blank">Click here for more info on Nuxt images.</a>
            </p>
            <!-- -->
            <p class="pt-5 pb-10 montserrat-bold">
            Duis imperdiet mi augue. Vestibulum ante ipsum primis in faucibus orci luctus et ultrices posuere cubilia curae; Duis convallis justo vitae lorem consequat consequat. Praesent aliquam neque lorem, sed rhoncus ex fermentum non. In tincidunt facilisis justo sit amet commodo. Donec convallis dolor neque, non ultricies nisi maximus vitae. Proin vel elit nisi.
            </p>    
        </p>
        <hr>
        <!-- The following lines show the usage of a flexbox with 2 columns--> 
        <div class="flex gap-4 responsive-flex pt-5 pb-10">
            <div class="flex-col">
                Column 1 - Duis imperdiet mi augue. Vestibulum ante ipsum primis in faucibus orci luctus et ultrices posuere cubilia curae; Duis convallis justo vitae lorem consequat consequat. Praesent aliquam neque lorem, sed rhoncus ex fermentum non. In tincidunt facilisis justo sit amet commodo. Donec convallis dolor neque, non ultricies nisi maximus vitae. Proin vel elit nisi.
            </div>
            <div class="flex-col">
                Column 2 - Duis imperdiet mi augue. Vestibulum ante ipsum primis in faucibus orci luctus et ultrices posuere cubilia curae; Duis convallis justo vitae lorem consequat consequat. Praesent aliquam neque lorem, sed rhoncus ex fermentum non. In tincidunt facilisis justo sit amet commodo. Donec convallis dolor neque, non ultricies nisi maximus vitae. Proin vel elit nisi.
            </div>
        </div>
        <p class="font-bold">
            <a href="https://tailwindcss.com/docs/flex-basis" target="_blank">Click here for more info on Tailwind and Flexboxes.</a>
        </p>
        <!-- -->
        <hr>
         <!-- The following lines show the usage of a flexbox with 2 columns--> 
         <div class="flex gap-4 responsive-flex pt-5 pb-10">
            <div class="flex-col">
                Column 1 - Duis imperdiet mi augue. Vestibulum ante ipsum primis in faucibus orci luctus et ultrices posuere cubilia curae; Duis convallis justo vitae lorem consequat consequat. Praesent aliquam neque lorem, sed rhoncus ex fermentum non. In tincidunt facilisis justo sit amet commodo. Donec convallis dolor neque, non ultricies nisi maximus vitae. Proin vel elit nisi.
            </div>
            <div class="flex-col">
                Column 2 - Duis imperdiet mi augue. Vestibulum ante ipsum primis in faucibus orci luctus et ultrices posuere cubilia curae; Duis convallis justo vitae lorem consequat consequat. Praesent aliquam neque lorem, sed rhoncus ex fermentum non. In tincidunt facilisis justo sit amet commodo. Donec convallis dolor neque, non ultricies nisi maximus vitae. Proin vel elit nisi.
            </div>
            <div class="flex-col">
                Column 3 - Duis imperdiet mi augue. Vestibulum ante ipsum primis in faucibus orci luctus et ultrices posuere cubilia curae; Duis convallis justo vitae lorem consequat consequat. Praesent aliquam neque lorem, sed rhoncus ex fermentum non. In tincidunt facilisis justo sit amet commodo. Donec convallis dolor neque, non ultricies nisi maximus vitae. Proin vel elit nisi.
            </div>
        </div>
        <!-- -->
    </div>
</template>

<!-- the style section contains the design of your page -->
<style>
/* The flex direction is standard set to rows */
.responsive-flex {
    display: flex;
    flex-direction: row;
}
/* The following style makes the flexbox responsive */
/* The flex direction is set to columns when it's not bigger then 768 px */
@media (max-width: 768px) {
    .responsive-flex {
        flex-direction: column;
    }
}
</style>
