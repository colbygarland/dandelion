<template>
    <div>
        <header class="py-40 text-center bg-cover shadow" :style="{ backgroundImage: `url(${backgroundUrl})` }">
            <h1 class="text-white">
                <span class="font-script text-6xl block lg:text-6xl">Dandelion</span>
                <span class="text-4xl lg:text-5xl">on the Prairie</span>
            </h1>
        </header>
        <div class="py-5 bg-orange-400 text-center mb-3 lg:mb-10">
            <h3 class="text-white text-2xl lg:text-4xl">Sign up for updates!</h3>
        </div>
        <div class="container ml-auto mr-auto px-4 lg:px-16 mb-6 lg:mb-20">
            <p class="mb-3 text-center">The first 100 people to submit their email will be entered for a chance to win 6 months subscription to Dandelion on the Prairie!</p>
            <form name="emailsignup" netlify netlify-honeypot="bot-field" class="lg:max-w-lg lg:ml-auto lg:mr-auto" action="/thanks" method="post">
                <input type="hidden" name="form-name" value="emailsignup" />
                <p class="hidden">
                    <label>Don’t fill this out if you're human: <input name="bot-field" /></label>
                </p>

                <div class="py-2">
                    <label class="block text-gray-700 text-sm font-bold mb-2">Email</label>
                    <input type="email" name="email" required="required" class="shadow appearance-none border rounded w-full py-2 px-3 text-gray-700 leading-tight focus:outline-none focus:shadow-outline">
                </div>
                <div class="py-2">
                    <button type="submit" class="px-8 py-2 bg-orange-400 text-white hover:bg-orange-500 font-bold rounded-lg ease-in-out duration-500 focus:outline-none">Submit</button>
                </div>
            </form>
        </div>
        <div class="container ml-auto mr-auto px-4 lg:px-16 mb-3 lg:mb-10">
            <h2 class="text-2xl lg:text-4xl mb-3">About Dandelion on the Prairie</h2>
            <p class="mb-3">I'm a busy mother of four beautiful children. We live in a small, small, small northern Alberta community. Both my husband and I, and our parents, and our grandparents grew up here. We've known each other since grade 2 and graduated with 12 students in our class.</p>
            <p class="mb-3">Moose, bears, foxes, and other wildlife are constantly in our back yard and they love my chickens... Ah, life on the prairie. I've always loved wildflowers, one thats always in my yard is the famous bright yellow dandelion. My brother in-law has nicknamed me little house on the prairie for multiple reasons!</p>
            <p class="mb-3">I recently had an idea, Canada needs their own subscription box with Canadian made products, or at least as many as possible. So an idea was born and a name finally came to me, Dandelion on the Prairie. Here I try to find Canadian made products that are sustainable, ethically made or natural. 4-6 items shipped to you monthly so you don't have to wait too long!</p>
            <p class="mb-3">So along with my tech savvy brother in-law, Colby, welcome to the Dandelion on the prairie family. Stayed tuned for our launch date!</p>
            <p class="mb-3"><strong>- Brittany</strong></p>
        </div>
        <footer class="bg-orange-400 h-6 block"></footer>
    </div>
</template>

<script>
    import backgroundUrl from '~/assets/images/dandelion.jpg'
    export default {
        data() {
            return { backgroundUrl }
        }
    }
</script>
