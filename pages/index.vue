<template>
  <div class="pt-6 pb-2 bg-gray-100">
    <div class="max-w-screen-xl mx-auto px-4 sm:px-6 lg:px-8">
      <div class="lg:text-center flex flex-col justify-center">
        <div class="flex justify-center">
          <img src="/vrehm-picture-resized.jpg" class="rounded-lg h-48" />
        </div>
        <p
          class="text-xl leading-6 text-teal-600 font-semibold tracking-wide uppercase py-4 text-center"
        >
          Vincent REHM
        </p>
        <div class="my-2">
          <div class="max-w-screen-xl mx-auto px-4 sm:px-6 lg:px-8">
            <div class="grid grid-cols-2 gap-4">
              <div
                class="col-span-1 flex justify-end md:col-span-2 lg:col-span-1"
              >
                <a
                  target="_blank"
                  class="link"
                  href="https://linkedin.com/in/vincentrehm/"
                  data-tippy-content="@linkedin_handle"
                  ><svg
                    class="h-6 fill-current text-gray-600 hover:text-teal-600"
                    role="img"
                    xmlns="http://www.w3.org/2000/svg"
                    viewBox="0 0 24 24"
                  >
                    <title>Linkedin</title>
                    <path
                      d="M19 0h-14c-2.761 0-5 2.239-5 5v14c0 2.761 2.239 5 5 5h14c2.762 0 5-2.239 5-5v-14c0-2.761-2.238-5-5-5zm-11 19h-3v-11h3v11zm-1.5-12.268c-.966 0-1.75-.79-1.75-1.764s.784-1.764 1.75-1.764 1.75.79 1.75 1.764-.783 1.764-1.75 1.764zm13.5 12.268h-3v-5.604c0-3.368-4-3.113-4 0v5.604h-3v-11h3v1.765c1.396-2.586 7-2.777 7 2.476v6.759z"
                    /></svg
                ></a>
              </div>
              <div
                class="col-span-1 flex justify-start md:col-span-2 lg:col-span-1"
              >
                <a
                  target="_blank"
                  class="link"
                  href="https://github.com/vrehm"
                  data-tippy-content="@github_handle"
                  ><svg
                    class="h-6 fill-current text-gray-600 hover:text-teal-600"
                    role="img"
                    viewBox="0 0 24 24"
                    xmlns="http://www.w3.org/2000/svg"
                  >
                    <title>GitHub</title>
                    <path
                      d="M12 .297c-6.63 0-12 5.373-12 12 0 5.303 3.438 9.8 8.205 11.385.6.113.82-.258.82-.577 0-.285-.01-1.04-.015-2.04-3.338.724-4.042-1.61-4.042-1.61C4.422 18.07 3.633 17.7 3.633 17.7c-1.087-.744.084-.729.084-.729 1.205.084 1.838 1.236 1.838 1.236 1.07 1.835 2.809 1.305 3.495.998.108-.776.417-1.305.76-1.605-2.665-.3-5.466-1.332-5.466-5.93 0-1.31.465-2.38 1.235-3.22-.135-.303-.54-1.523.105-3.176 0 0 1.005-.322 3.3 1.23.96-.267 1.98-.399 3-.405 1.02.006 2.04.138 3 .405 2.28-1.552 3.285-1.23 3.285-1.23.645 1.653.24 2.873.12 3.176.765.84 1.23 1.91 1.23 3.22 0 4.61-2.805 5.625-5.475 5.92.42.36.81 1.096.81 2.22 0 1.606-.015 2.896-.015 3.286 0 .315.21.69.825.57C20.565 22.092 24 17.592 24 12.297c0-6.627-5.373-12-12-12"
                    /></svg
                ></a>
              </div>
            </div>
          </div>
        </div>
        <div class="mt-2 mb-4 max-w-screen-xl mx-auto px-4 sm:px-6 lg:px-8">
          <button
            class="bg-teal-500 hover:bg-teal-600 text-white font-bold py-2 px-4 rounded-full"
          >
            <Mailto
              :mail="email"
              subject="Prise de contact - projet pour NOM DE L'ENTREPRISE"
              title="Me contacter par email"
              >Me contacter par email</Mailto
            >
          </button>
        </div>
        <h3
          class="mt-2 text-3xl leading-8 font-extrabold tracking-tight text-gray-900 sm:text-4xl sm:leading-10"
        >
          Entrepreneur, CTO et freelance web
        </h3>
        <p class="mt-4 max-w-2xl text-xl leading-7 text-gray-500 lg:mx-auto">
          Entrepreneur depuis 4 ans, je vous fais bénéficier de mon expérience
          pour optimiser l'efficience de vos activités métier grâce au
          numérique.
        </p>
      </div>

      <div class="mt-10">
        <ul class="md:grid md:grid-cols-2 md:col-gap-8 md:row-gap-10">
          <li>
            <div class="flex">
              <div class="flex-shrink-0">
                <div
                  class="flex items-center justify-center h-12 w-12 rounded-md bg-teal-500 text-white"
                >
                  <svg
                    class="h-6 w-6"
                    stroke="currentColor"
                    fill="none"
                    viewBox="0 0 24 24"
                  >
                    <path
                      stroke-linecap="round"
                      stroke-linejoin="round"
                      stroke-width="2"
                      d="M21 12a9 9 0 01-9 9m9-9a9 9 0 00-9-9m9 9H3m9 9a9 9 0 01-9-9m9 9c1.657 0 3-4.03 3-9s-1.343-9-3-9m0 18c-1.657 0-3-4.03-3-9s1.343-9 3-9m-9 9a9 9 0 019-9"
                    />
                  </svg>
                </div>
              </div>
              <div class="ml-4">
                <h5 class="text-lg leading-6 font-medium text-gray-900">
                  Culture numérique
                </h5>
                <p class="mt-2 text-base leading-6 text-gray-500">
                  Vous apporter un état de l’art des meilleures pratiques du web
                  et des startups sur vos sujets business critiques.
                </p>
              </div>
            </div>
          </li>
          <li class="mt-10 md:mt-0">
            <div class="flex">
              <div class="flex-shrink-0">
                <div
                  class="flex items-center justify-center h-12 w-12 rounded-md bg-teal-500 text-white"
                >
                  <svg
                    class="h-6 w-6"
                    stroke="currentColor"
                    fill="none"
                    viewBox="0 0 24 24"
                  >
                    <path
                      d="M19 21V5C19 3.89543 18.1046 3 17 3H7C5.89543 3 5 3.89543 5 5V21M19 21L21 21M19 21H14M5 21L3 21M5 21H10M9 6.99998H10M9 11H10M14 6.99998H15M14 11H15M10 21V16C10 15.4477 10.4477 15 11 15H13C13.5523 15 14 15.4477 14 16V21M10 21H14"
                      stroke-linecap="round"
                      stroke-linejoin="round"
                      stroke-width="2"
                    />
                  </svg>
                </div>
              </div>
              <div class="ml-4">
                <h5 class="text-lg leading-6 font-medium text-gray-900">
                  Accompagnement entrepreneurial
                </h5>
                <p class="mt-2 text-base leading-6 text-gray-500">
                  Vous faire bénéficier de mon expérience entrepreneuriale pour
                  accélérer le lancement de votre entreprise.
                </p>
              </div>
            </div>
          </li>
          <li class="mt-10 md:mt-0">
            <div class="flex">
              <div class="flex-shrink-0">
                <div
                  class="flex items-center justify-center h-12 w-12 rounded-md bg-teal-500 text-white"
                >
                  <svg
                    class="h-6 w-6"
                    stroke="currentColor"
                    fill="none"
                    viewBox="0 0 24 24"
                  >
                    <path
                      stroke-linecap="round"
                      stroke-linejoin="round"
                      stroke-width="2"
                      d="M13 10V3L4 14h7v7l9-11h-7z"
                    />
                  </svg>
                </div>
              </div>
              <div class="ml-4">
                <h5 class="text-lg leading-6 font-medium text-gray-900">
                  Technique
                </h5>
                <p class="mt-2 text-base leading-6 text-gray-500">
                  Coder et déployer les meilleures technologies correspondant à
                  vos besoins business.
                </p>
              </div>
            </div>
          </li>
          <li class="mt-10 md:mt-0">
            <div class="flex">
              <div class="flex-shrink-0">
                <div
                  class="flex items-center justify-center h-12 w-12 rounded-md bg-teal-500 text-white"
                >
                  <svg
                    class="h-6 w-6"
                    stroke="currentColor"
                    fill="none"
                    viewBox="0 0 24 24"
                  >
                    <path
                      stroke-linecap="round"
                      stroke-linejoin="round"
                      stroke-width="2"
                      d="M7 8h10M7 12h4m1 8l-4-4H5a2 2 0 01-2-2V6a2 2 0 012-2h14a2 2 0 012 2v8a2 2 0 01-2 2h-3l-4 4z"
                    />
                  </svg>
                </div>
              </div>
              <div class="ml-4">
                <h5 class="text-lg leading-6 font-medium text-gray-900">
                  Produit et marketing
                </h5>
                <p class="mt-2 text-base leading-6 text-gray-500">
                  Penser et implémenter de façon agile les fonctionnalités
                  permettant de parvenir à vos objectifs business.
                </p>
              </div>
            </div>
          </li>
        </ul>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  data() {
    return {
      email: process.env.email
    }
  }
}
</script>

<style></style>
