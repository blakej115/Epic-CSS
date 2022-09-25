<template>
  <div class="layout">
    <Header />
    <main class="main">
      <section class="section billboard">
        <div class="container max-width-sm">
          <div class="content text-align-center">
            <h1>Epic CSS</h1>
            <p>Epic CSS is a lightweight SASS boilerplate and CSS framework that is intended to be edited directly.</p>
            <p>Epic CSS is intended to be a jumpstart to building user interfaces that would otherwise be written custom from scratch.</p>
            <p>Copy the <code>assets/epic</code> folder into your project, edit the boilerplate/framework directly, and compile from scss to css.</p>
            <p>Epic CSS is in it's very early stages. More features and documentation are coming soon.</p>
            <div class="buttons jc-center">
              <a class="button-primary" href="https://github.com/blakej115/Epic-CSS" target="_blank">Git Repo</a>
              <a class="button-secondary" href="https://github.com/blakej115/Epic-CSS/archive/refs/heads/main.zip" target="_blank">Download Zip</a>
            </div>
          </div>
        </div>
      </section>
    </main>
    <Footer />
  </div>
</template>

<script>
import Header from "../components/Header";
import Footer from "../components/Footer";
export default {
  name: 'IndexPage',
  components: {Footer, Header},
}
</script>
