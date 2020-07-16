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
            <!-- Begin Mailchimp Signup Form -->
            <link href="//cdn-images.mailchimp.com/embedcode/classic-10_7.css" rel="stylesheet" type="text/css">
            <style type="text/css">
                #mc_embed_signup{background:#fff; clear:left; font:14px Helvetica,Arial,sans-serif; }
                /* Add your own Mailchimp form style overrides in your site stylesheet or in this style block.
                   We recommend moving this block and the preceding CSS link to the HEAD of your HTML file. */
            </style>
            <div id="mc_embed_signup">
                <form action="https://gmail.us10.list-manage.com/subscribe/post?u=ba4015e3fea11713d4549488f&amp;id=ade56fb97d" method="post" id="mc-embedded-subscribe-form" name="mc-embedded-subscribe-form" class="validate" target="_blank" novalidate>
                    <div id="mc_embed_signup_scroll">
                        <h2>Sign up for a chance to win 6 month subscription!</h2>
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
        <div class="container ml-auto mr-auto px-4 lg:px-16 mb-3 lg:mb-10">
            <h2 class="text-2xl lg:text-4xl mb-3">About Dandelion on the Prairie</h2>
            <p class="mb-3">I am a busy mother of four beautiful children. We live in a small, small, small, northern Alberta community. Both my husband and I, our parents, and our grandparents, call this home. My husband and I have known each other since grade two. We graduated together, along  with 10 other students in our class.</p>
            <p class="mb-3">Moose, bear, fox, and other wildlife are constantly in our back yard and they love my chickens! Ah, life on the prairie! I've always loved wildflowers. The one, that is always in my yard, is the famous, bright yellow dandelion. My brother in-law has nicknamed me, Little House  on the Prairie,  for a number of valid reasons!</p>
            <p class="mb-3">I recently had an idea! I believe that Canada needs its own subscription box, filled with Canadian made products! An idea was born and a name finally came to me; Dandelion on the Prairie. Here, I will try to source Canadian made products that are sustainable and ethically made or natural. Four to six items will be shipped to you monthly. Your wait time will be minimal!</p>
            <p class="mb-3">I, along with my tech savvy brother in-law, Colby, would like to welcome you to the Dandelion on the Prairie family. Stayed tuned for our launch date!</p>
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
