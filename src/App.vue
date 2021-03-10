<template>
    <Header />
    <Hero />
    <About />
    <Skills />
    <Portfolio />
    <Contact />
    <Footer />
</template>

<script>
import Header from './components/Header';
import Hero from './components/Hero';
import About from './components/About';
import Skills from './components/Skills';
import Portfolio from './components/Portfolio';
import Contact from './components/Contact';
import Footer from './components/Footer';

export default {
    name: 'App',
    components: {
        Header,
        Hero,
        About,
        Skills,
        Portfolio,
        Contact,
        Footer,
    },
};
</script>
