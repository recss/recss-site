<template>
  <div class="_about">
    <section id="intro">
        <!-- <img :src="require(`./assets/jacqui-icon.png`)"> -->
        <!-- <div id="icon" :style="{'background-image': `url('./assets/jacqui-icon.png')`}">&nbsp;</div> -->
        <p>
            Hello, I’m <b>Kevin K. Johnson, II</b>.
        </p>
        <p>
            These days, I’m a <b>front-end web designer and developer</b> working at the U.S. Cellular headquarters in Chicago. Over the years, I’ve partnered with individuals, start-ups, a non-profit organization, and a couple Fortune 500 companies. My roles have included tasks as varied as:
        </p>
    </section>

    <section id="skills">
        <div id="skills-design">
            <h3>Designer</h3>
            <ul>
                <li>User Interface (UI)</li>
                <li>User Experience (UX)</li>
                <li>Information Architecture (IA)</li>
                <li>Responsive Design
                    <br><small>Flexbox, and CSS Grid</small>
                </li>
                <li>Email Marketing</li>
                <li>Animated Banner Ads</li>
            </ul>
        </div>

        <div id="skills-development">
            <h3>Developer</h3>
            <ul>
                <li>JavaScript Frameworks
                    <br><small>Vue.js Preferred</small>
                </li>
                <li>Content-Management Systems
                    <br><small>Traditional, and Headless</small>
                </li>
                <li>Static Sites</li>
                <li>Functional Programming</li>
                <li>Fierce Googling</li>
                <li>“Have you tried turning it off, then on?”</li>
            </ul>
        </div>

        <div id="skills-empathy">
            <h3>Empath</h3>
            <ul>
                <li>Data Synthesis</li>
                <li>Mind-Melding</li>
                <li>Turning Unbridled Imaginations Into Organized Code
                    <br><small>Nothing is Impossible&hellip; Until I Say It Is</small>
                </li>
                <li>Other Empath Stuff, Presumably</li>
            </ul>
        </div>
    </section>
  </div>
</template>

<script>
export default {
  name: 'About',
  props: {
    msg: String
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
._about {
    max-width: 1500px;
    margin: 1em auto;
    line-height: 1.5;
    display: grid;
        grid: auto-flow / repeat(12, 1fr);
}
h3 {
  margin: 1em 0 0.5em;
}
ul {
    padding: 0;
}
li {
    padding-bottom: 0.5em;
    list-style-type: none;
}
#intro,
#skills {
    padding: 0.5em 0;
    grid-column: span 12;
}
#intro p {
    max-width: 50em;
    margin: 1em auto;
}
#skills {
    width: 100%;
    text-align: left;
    display: flex;
        flex-flow: row wrap;
        justify-content: space-around;
        align-items: flex-start;
}

@media (max-width: 970px) {
    #intro p {
        max-width: 36em;
    }
    #skills {
        text-align: center;
        justify-content: center;
    }
    #skills-design,
    #skills-development,
    #skills-empathy {
        width: 100%;
    }
}
</style>
