<template>
    <div class="card-wrapper  | content-cc">
    <div class="faq-card">

        <div class="faq-ilustrations">
            <img class="mobile ilust" src="https://raw.githubusercontent.com/Romerof/FAQ-accordion-card/main/images/illustration-woman-online-mobile.svg"/>
            <!-- mobile -->
        </div>

        <!-- Project name -->
      <div
        class="px-4 space-y-1 sm:space-y-0 sm:grid sm:grid-cols-3 sm:gap-4 sm:px-6 sm:py-8"
      >
        <div>
          <label
            class="block text-sm font-medium text-second-color-600 sm:mt-px sm:pt-2"
            for="project-name"
          >
            {{ $t("Coupon Code") }}
          </label>
        </div>
        <div class="flex rounded-md sm:col-span-2" dir="ltr">
          <div class="flex relative flex-grow items-stretch focus-within:z-10">
            <input
              id="coupon"
              :placeholder="$t('COUPON')"
              :value="booking.coupon.code"
              class="block w-full rounded-none rounded-l-md border-gray-300 focus:ring-main-color-500 focus:border-main-color-500 sm:text-sm"
              name="coupon"
              type="text"
              @input="updateCoupon"
            />
          </div>
          <button
            class="inline-flex relative items-center px-4 py-2 -ml-px space-x-2 text-sm font-medium text-gray-700 bg-gray-50 rounded-r-md border border-gray-300 hover:bg-gray-100 focus:outline-none focus:ring-1 focus:ring-main-color-500 focus:border-main-color-500"
            type="button"
            @click="validateCoupon(booking)"
          >
            {{ $t("Apply") }}
          </button>
        </div>
      </div>
      <!--End Project name -->

        <main class="faq-content">
            <h1> Referral Program FAQS</h1>

            <div class="faq-articles">

                <article class="faq-accordion item-left">

                    <input type="checkbox" class="tgg-title" id="tgg-title-1">

                    <div class="faq-accordion-title">
                        <label for="tgg-title-1">
                                <h2>Tell me more about this referral program?</h2>
                                <span class="arrow-icon">
                                    <img src="https://raw.githubusercontent.com/Romerof/FAQ-accordion-card/main/images/icon-arrow-down.svg">
                                </span>
                            </label>
                    </div>

                    <div class="faq-accordion-content">

                        <p>You can invite up to 2 additional users on the Free plan. There is no limit on team members for the Premium plan.</p>
                    </div>

                </article>
                <!-- faq accordion -->

                <article class="faq-accordion item-right">

                    <input type="checkbox" class="tgg-title" id="tgg-title-2">

                    <div class="faq-accordion-title">
                        <label for="tgg-title-2">
                                <h2>
                                    How can I report to my friend?
                                </h2>
                                <span class="arrow-icon">
                                    <img
                                        src="https://raw.githubusercontent.com/Romerof/FAQ-accordion-card/main/images/icon-arrow-down.svg">
                                </span>
                            </label>
                    </div>

                    <div class="faq-accordion-content">
                        <p>No more than 2GB. All files in your account must fit your allotted storage space.</p>
                    </div>

                </article>
                <!-- faq accordion -->

                <article class="faq-accordion">

                    <input class="tgg-title" type="checkbox" id="tgg-title-3">

                    <div class="faq-accordion-title">
                        <label for="tgg-title-3">
                                <h2>
                                    What reward will I get after referring to my friends?
                                </h2>
                                <span class="arrow-icon">
                                    <img
                                        src="https://raw.githubusercontent.com/Romerof/FAQ-accordion-card/main/images/icon-arrow-down.svg">
                                </span>
                            </label>
                    </div>

                    <div class="faq-accordion-content">
                        <p>Click “Forgot password” from the login page or “Change password” from your profile page. A reset link will be emailed to you.</p>
                    </div>

                </article>
                <!-- faq accordion -->

                <article class="faq-accordion">

                    <input class="tgg-title" type="checkbox" id="tgg-title-4">

                    <div class="faq-accordion-title">
                        <label for="tgg-title-4">
                                <h2>
                                    How many friends can I refer to is there any line to it?
                                </h2>
                                <span class="arrow-icon">
                                    <img
                                        src="https://raw.githubusercontent.com/Romerof/FAQ-accordion-card/main/images/icon-arrow-down.svg">
                                </span>
                            </label>
                    </div>

                    <div class="faq-accordion-content">
                        <p>
                            Yes! Send us a message and we’ll process your request no questions asked.</p>
                    </div>

                </article>
                <!-- faq accordion -->

                <article class="faq-accordion">

                    <input class="tgg-title" type="checkbox" id="tgg-title-5">

                    <div class="faq-accordion-title">
                        <label for="tgg-title-5">
                                <h2>
                                    when will my ear reward expire?
                                </h2>
                                <span class="arrow-icon">
                                    <img
                                        src="https://raw.githubusercontent.com/Romerof/FAQ-accordion-card/main/images/icon-arrow-down.svg">
                                </span>
                            </label>
                    </div>

                    <div class="faq-accordion-content">
                        <p> Chat and email support is available 24/7. Phone lines are open during normal business hours.
                        </p>
                    </div>

                </article>
                <!-- faq accordion -->

                <article class="faq-accordion">

                    <input class="tgg-title" type="checkbox" id="tgg-title-6">

                    <div class="faq-accordion-title">
                        <label for="tgg-title-6">
                                <h2>
                                    I wish to sign up in choice using the refilling shared by my friend what is the step-by-step guide?
                                </h2>
                                <span class="arrow-icon">
                                    <img
                                        src="https://raw.githubusercontent.com/Romerof/FAQ-accordion-card/main/images/icon-arrow-down.svg">
                                </span>
                            </label>
                    </div>

                    <div class="faq-accordion-content">
                        <p> Chat and email support is available 24/7. Phone lines are open during normal business hours.
                        </p>
                    </div>

                </article>
                <!-- faq accordion -->

                <article class="faq-accordion">

                    <input class="tgg-title" type="checkbox" id="tgg-title-7">

                    <div class="faq-accordion-title">
                        <label for="tgg-title-7">
                                <h2>
                                    Tell me more about this referral program
                                    </h2>
                                <span class="arrow-icon">
                                    <img
                                        src="https://raw.githubusercontent.com/Romerof/FAQ-accordion-card/main/images/icon-arrow-down.svg">
                                </span>
                            </label>
                    </div>

                    <div class="faq-accordion-content">
                        <p> Chat and email support is available 24/7. Phone lines are open during normal business hours.
                        </p>
                    </div>

                </article>

                <!-- faq accordion -->

            </div>
            <!-- faq articles -->

        </main>
        <!-- faq -->

    </div>
    <!-- faq card -->

</div>
<!-- card wrapper -->
</template>


<script>

import "./referralstyle.css"

export default {
  components: {
  },
}
</script>

