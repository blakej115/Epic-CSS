<template>
  <div class="layout">
    <Header />
    <main class="main">
      <section class="section">
        <div class="container">
          <div class="content ta-center">
            <h2>Flex Grid</h2>
          </div>
          <div class="flex-grid total-12">
            <div class="span-4">
              <p>A child element of a flex grid.</p>
            </div>
            <div class="span-4">
              <p>A child element of a flex grid.</p>
            </div>
            <div class="span-4">
              <p>A child element of a flex grid.</p>
            </div>
            <div>
              <p>An "auto" child element of a flex grid.</p>
            </div>
            <div class="span-fill">
              <p>A "fill" child element of a flex grid.</p>
            </div>
          </div>
        </div>
      </section>
      <section class="section">
        <div class="container">
          <div class="content ta-center">
            <h2>CSS Grid</h2>
          </div>
          <div class="css-grid total-12">
            <div class="span-4">
              <p>A child element of a CSS grid.</p>
            </div>
            <div class="span-4">
              <p>A child element of a CSS grid.</p>
            </div>
            <div class="span-4">
              <p>A child element of a CSS grid.</p>
            </div>
            <div>
              <p>An "auto" or "fill" child element of a CSS grid.</p>
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
  name: 'ExamplesPage',
  components: {Footer, Header},
}
</script>
