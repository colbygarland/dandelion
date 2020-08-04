<template>
    <div>

        <a href="#sign-up" class="text-white font-bold bg-primary py-3 block text-center hover:bg-secondary">Sign up now!</a>

        <header class="py-40 lg:py-64 text-center bg-cover shadow bg-no-repeat bg-center" :style="{ backgroundImage: `url(${dandelion})` }">
            <h1 class="text-white">
                <span class="font-script text-8xl block lg:text-10xl">Dandelion</span>
                <span class="text-4xl lg:text-6xl">on the Prairie</span>
            </h1>
        </header>

        <div class="px-4 lg:px-16 py-10 lg:py-20">
            <div class="container mx-auto">
                <h2 class="text-2xl lg:text-4xl mb-6 inline-block border-b-2"><strong class="text-primary">Canadian Made</strong> Subscription Boxes</h2>
                <p class="mb-3 leading-loose">Canada needs its own subscription box, and it needs to be filled with Canadian made, sustainably developed products.</p>
                <p class="text-xl font-bold text-primary mb-3">Meet Dandelion on the Prairie.</p>
                <p class="mb-6 leading-loose">Created by Brittany Dolen, Dandelion on the Prairie is a monthly, carefully curated subscription box. Each month, you will receive a box filled with <span class="text-primary">real</span> local goods, made by <span class="text-primary">real</span> Canadian business owners.</p>
                <a href="#sign-up" class="inline-block bg-primary text-white font-bold px-5 py-3 rounded hover:bg-secondary">Subscribe to our email list</a>
            </div>
        </div>

        <div class="block lg:flex relative">
            <div class="bg-gray-100 py-10 lg:py-20 lg:w-1/2">
                <div class="container mx-auto block px-4 lg:px-16">
                    <h2 class="text-2xl lg:text-4xl mb-6 inline-block border-b-2"><strong class="text-primary">Proudly</strong> Canadian 🇨🇦</h2>
                    <p class="mb-3 leading-loose">Dandelion on the Prairie is a company that curates <strong class="text-primary">Canadian made</strong> and <strong class="text-primary">sustainably sourced</strong> products. Here we believe that that we should support other Canadian companies who also have the same views.</p>
                    <p class="mb-3 leading-loose">Supporting Canadian businesses we can contribute back to our own economy and support each other. By choosing ethically & sustainably made products we can also support a better and healthier Earth for our kids, grandkids and future generations.</p>
                    <p class="mb-3 leading-loose">Helping you make small changes that can lead to bigger changes. By helping these Canadian businesses we also become aware as consumers about where our products come from and how they are made.</p>
                    <div class="lg:hidden">
                        <img class="block mx-auto" :src="field" alt="Field" />
                    </div>
                </div>
            </div>
            <div class="hidden lg:block w-1/2 relative">
                <div :style="{ backgroundImage: `url(${field})` }" class="bg-cover bg-no-repeat bg-center hidden lg:block absolute h-full w-full"></div>
            </div>
        </div>

        <div class="py-5 bg-primary text-center mb-3 lg:mb-10">
            <h3 class="text-white text-2xl lg:text-4xl">Sign up for updates!</h3>
        </div>

        <div class="container ml-auto mr-auto px-4 lg:px-16 mb-6 lg:mb-20" id="sign-up">
            <p class="mb-3 text-center text-xl">The first 100 people to submit their email will be entered for a chance to win 6 months subscription to Dandelion on the Prairie!</p>
            <!-- Begin Mailchimp Signup Form -->
            <link href="//cdn-images.mailchimp.com/embedcode/classic-10_7.css" rel="stylesheet" type="text/css">

            <div id="mc_embed_signup">
                <form action="https://gmail.us10.list-manage.com/subscribe/post?u=ba4015e3fea11713d4549488f&amp;id=ade56fb97d" method="post" id="mc-embedded-subscribe-form" name="mc-embedded-subscribe-form" class="validate" target="_blank" novalidate>
                    <div id="mc_embed_signup_scroll">
                        <h2 class="text-2xl lg:text-4xl mb-3">Sign up for a chance to win 6 months subscription!</h2>
                        <div class="indicates-required"><span class="asterisk">*</span> indicates required</div>
                        <div class="mc-field-group">
                            <label for="mce-EMAIL">Email Address  <span class="asterisk">*</span>
                            </label>
                            <input type="email" value="" name="EMAIL" class="required email" id="mce-EMAIL">
                        </div>
                        <div class="mc-field-group">
                            <label for="mce-FNAME">First Name </label>
                            <input type="text" value="" name="FNAME" class="" id="mce-FNAME">
                        </div>
                        <div id="mce-responses" class="clear">
                            <div class="response" id="mce-error-response" style="display:none"></div>
                            <div class="response" id="mce-success-response" style="display:none"></div>
                        </div>    <!-- real people should not fill this in and expect good things - do not remove this or risk form bot signups-->
                        <div style="position: absolute; left: -5000px;" aria-hidden="true"><input type="text" name="b_ba4015e3fea11713d4549488f_ade56fb97d" tabindex="-1" value=""></div>
                        <div class="clear"><input type="submit" value="Subscribe" name="subscribe" id="mc-embedded-subscribe" class="button"></div>
                    </div>
                </form>
            </div>
            <script type='text/javascript' src='//s3.amazonaws.com/downloads.mailchimp.com/js/mc-validate.js'></script><script type='text/javascript'>(function($) {window.fnames = new Array(); window.ftypes = new Array();fnames[0]='EMAIL';ftypes[0]='email';fnames[1]='FNAME';ftypes[1]='text';fnames[2]='LNAME';ftypes[2]='text';fnames[3]='ADDRESS';ftypes[3]='address';fnames[4]='PHONE';ftypes[4]='phone';fnames[5]='BIRTHDAY';ftypes[5]='birthday';}(jQuery));var $mcj = jQuery.noConflict(true);</script>
            <!--End mc_embed_signup-->
        </div>



        <div class="block lg:flex relative">
            <div class="hidden lg:block w-1/2 relative">
                <div :style="{ backgroundImage: `url(${brittany})` }" class="bg-cover bg-no-repeat bg-center hidden lg:block absolute h-full w-full"></div>
            </div>
            <div class="bg-gray-100 py-10 lg:py-20 lg:w-1/2">
                <div class="container mx-auto block px-4 lg:px-16">
                    <h2 class="text-2xl lg:text-4xl mb-6 inline-block border-b-2"><strong class="text-primary">About</strong> Dandelion on the Prairie</h2>
                    <p class="mb-3 leading-loose">I am a busy mother of four beautiful children. We live in a small, small, small, northern Alberta community. Both my husband and I, our parents, and our grandparents, call this home. My husband and I have known each other since grade two. We graduated together, along  with 10 other students in our class.</p>
                    <p class="mb-3 leading-loose">Moose, bear, fox, and other wildlife are constantly in our back yard and they love my chickens! Ah, life on the prairie! I've always loved wildflowers. The one, that is always in my yard, is the famous, bright yellow dandelion. My brother in-law has nicknamed me, Little House  on the Prairie,  for a number of valid reasons!</p>
                    <p class="mb-3 leading-loose">I recently had an idea! I believe that Canada needs its own subscription box, filled with Canadian made products! An idea was born and a name finally came to me; Dandelion on the Prairie. Here, I will try to source Canadian made products that are sustainable and ethically made or natural. Three to five items will be shipped to you monthly. Your wait time will be minimal!</p>
                    <p class="mb-3 leading-loose">I, along with my tech savvy brother in-law, Colby, would like to welcome you to the Dandelion on the Prairie family. Stayed tuned for our launch date!</p>
                    <p class="mb-3 lg:text-xl"><strong class="text-primary">- Brittany</strong></p>
                    <div class="lg:hidden">
                        <img class="block mx-auto" :src="brittany" alt="Brittany Dolen" />
                    </div>
                </div>
            </div>
        </div>

        <footer class="bg-primary h-6 block"></footer>
    </div>
</template>

<script>
    import backgroundUrl from '~/assets/images/dandelion.jpg';
    import field from '~/assets/images/field.jpg';
    import brittany from '~/assets/images/brittany.jpg';
    import dandelion from '~/assets/images/dandelion2.jpg';
    import ogImage from '~/assets/images/social-share.jpg';

    export default {
        data() {
            return {
                backgroundUrl,
                field,
                brittany,
                dandelion,
            }
        },
        head() {
            return {
                title: 'Dandelion on the Prairie',
                meta: [
                    {
                        hid: 'description',
                        name: 'description',
                        content: 'Dandelion on the Prairie is a company that curates Canadian made and sustainably sourced products. Here we believe that that we should support other Canadian companies who also have the same views.'
                    },
                ]
            }
        },
    }
</script>
