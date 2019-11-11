<template>
  <div class="about">
    <br />
    <div class="container">
      <div class="accordion" id="accordionExample">
        <!-- About -->
        <div class="card text-white bg-dark">
          <div class="card-header" id="headingOne">
            <h5 class="mb-0">
              <button
                class="btn btn-link"
                style="color:white;"
                type="button"
                data-toggle="collapse"
                data-target="#collapseOne"
                aria-expanded="true"
                aria-controls="collapseOne"
              >About Me!</button>
            </h5>
          </div>

          <div
            id="collapseOne"
            class="collapse show"
            aria-labelledby="headingOne"
            data-parent="#accordionExample"
          >
            <div class="card-body">
              <p>I currently live in the Fort Lauderdale area but am originally from Atlanta, GA.</p>
              <p>When I'm not developing awesome web apps or reading up on new languages/frameworks, I like to spend my time practicing MMA or eating.</p>
            </div>
          </div>
        </div>
        <!-- Journey -->
        <div class="card text-white bg-secondary">
          <div class="card-header" id="headingTwo">
            <h5 class="mb-0">
              <button
                class="btn btn-link collapsed"
                type="button"
                style="color:white;"
                data-toggle="collapse"
                data-target="#collapseTwo"
                aria-expanded="false"
                aria-controls="collapseTwo"
              >My Journey</button>
            </h5>
          </div>
          <div
            id="collapseTwo"
            class="collapse"
            aria-labelledby="headingTwo"
            data-parent="#accordionExample"
          >
            <div class="card-body">
              <p>My journey began when I wrote my first Javascript script out of curiosity in high school. Development has always been something I was curious about whether it be the systematic steps involved in development to the 'soft-skill' side of development, such as working with other developers or prioritizing features of an application.</p>
              <p>A big spark for me was during my undergraduate studies, when I was writing a capstone for my political science class, essentially I needed a way to compile multiple data entries and present it in a meaningful manner, sure I could have done it manually and thrown together a powerpoint presentation with rudimentary graphs that may or may not have been accurate for my grade. Instead, I decided to bring my development skills to the table and put together a simple algorithm that compiled my data for me and used the data as input to a function.</p>
              <p>Since then, I have taught myself a handful of languages such as Ruby, Python, and PHP via online courses as well as in professional environments. I found many similarities as well as differences amongst the languages and found that once a general grasp of the language is secured, that is where the real learning starts. This is where self-learning or seeking help comes into play and with the right amount of eagerness to learn, I found that picking up new languages wasn't as hard as I made it out to be!</p>
            </div>
          </div>
        </div>
        <!-- Skills -->
        <div class="card text-white bg-dark">
          <div class="card-header" id="headingThree">
            <h5 class="mb-0">
              <button
                class="btn btn-link collapsed"
                type="button"
                style="color: white;"
                data-toggle="collapse"
                data-target="#collapseThree"
                aria-expanded="false"
                aria-controls="collapseThree"
              >My Skills</button>
            </h5>
          </div>
          <div
            id="collapseThree"
            class="collapse"
            aria-labelledby="headingThree"
            data-parent="#accordionExample"
          >
            <div class="card-body">
              Here are the languages/frameworks/tools that I have discovered and learned so far!
              <div class="languages">
                <h4>Languages</h4>
                <ul>
                  <div class="row">
                    <li class="col-sm-4">Javascript</li>
                    <li class="col-sm-4">HTML5/CSS3</li>
                  </div>
                  <div class="row">
                    <li class="col-sm-4">Ruby</li>
                    <li class="col-sm-4">SQL</li>
                  </div>
                  <div class="row">
                    <li class="col-sm-4">Python</li>
                    <li class="col-sm-4">PHP</li>
                  </div>
                </ul>
              </div>
              <div class="frameworks">
                <h4>Frameworks</h4>
                <ul>
                  <div class="row">
                    <li class="col-sm-4">Vue.Js</li>
                    <li class="col-sm-4">React.Js</li>
                  </div>
                  <div class="row">
                    <li class="col-sm-4">Ruby on Rails</li>
                    <li class="col-sm-4">Sinatra</li>
                  </div>
                  <div class="row">
                    <li class="col-sm-4">Laravel</li>
                  </div>
                </ul>
              </div>
              <div class="tools">
                <h4>Tools</h4>
                <ul>
                  <div class="row">
                    <li class="col-sm-4">NPM</li>
                    <li class="col-sm-4">Webpack</li>
                  </div>
                  <div class="row">
                    <li class="col-sm-4">ESLint</li>
                    <li class="col-sm-4">Jest</li>
                  </div>
                  <div class="row">
                    <li class="col-sm-4">RSpec</li>
                    <li class="col-sm-4">Faker</li>
                  </div>
                </ul>
              </div>
            </div>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>

<style>
</style>

<script>
export default {
  name: "about",
  data: function() {
    return {};
  },
  created: function() {},
  methods: {}
};
</script>