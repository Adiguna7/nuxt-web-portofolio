<template>
  <div class="bg-all">
    <v-container id="hero" fluid>
      <v-row
        class="d-flex align-center justify-center flex-column"
        style="height: 100%"
      >
        <vue-typed-js
          :strings="['Suryo Adiguna', '_tender']"
          :typeSpeed="100"
          :startDelay="100"
          :backSpeed="100"
          :loop="true"
        >
          <div class="white--text text-sm-h4 text-h5 text-center">
            Hello, I'm
            <span class="typing" style="color: #e31b6d"></span>
          </div>
        </vue-typed-js>
        <div class="white--text text-sm-h4 text-h5 text-center mt-7 mt-md-0">
          Undergraduate Student at Computer Engineering ITS
        </div>
      </v-row>
    </v-container>
    <!-- <v-card dark class="pl-md-16" flat>
      <v-tabs dark color="#e31b6d">
        <v-tab class="font-weight-bold">About</v-tab>
        <v-tab class="font-weight-bold">Education</v-tab>
        <v-tab class="font-weight-bold">Resume</v-tab>
        <v-tab class="font-weight-bold">Portofolio</v-tab>
        <v-tab class="font-weight-bold">Contact Me</v-tab>
      </v-tabs>
    </v-card> -->
    <v-container style="margin-top: 100px" class="bg--grey c-home">
      <v-row class="flex-column-reverse flex-md-row">
        <v-col md="7" class="d-flex flex-column justify-center mt-13 mt-md-0">
          <div
            class="font-weight-bold text-h5 color--red text-center text-md-left"
          >
            About
          </div>
          <div class="font-weight-bold text-h6 mt-3 text-center text-md-left">
            Student Who Interest in web developer, robotic and machine learning
          </div>
          <div class="mt-3 text-center text-md-left">
            Study at computer engineering topics give me amazing knowledge about
            how technology works. Thats why i want to learn more and more.
            <br />
            <br />
            TL;DR. Love problem solving, Digital electronics and Linux.
          </div>
        </v-col>
        <v-col md="5" class="d-flex justify-center">
          <div class="l__imagediamond">
            <div class="l__imagesource"></div>
          </div>
        </v-col>
      </v-row>
    </v-container>
    <v-container class="c-home bg--grey mt-16">
      <v-row>
        <v-col cols="12">
          <div class="color--red font-weight-bold text-h5 text-center">
            My Resume
          </div>
        </v-col>
      </v-row>
      <v-row>
        <v-col cols="12" md="4" class="d-flex flex-column mt-9 mt-md-0">
          <div class="font-weight-bold text-h6 text-center text-md-left">
            Experience
          </div>
          <div class="mt-3 text-h6 text-center text-md-left">
            Involved in some project as web developer, and robotic programmer
            with
          </div>
          <div
            class="color--red text-h4 mt-3 font-weight-bold text-center text-md-left"
          >
            Amazing Peoples
          </div>
        </v-col>
        <v-col cols="12" md="8" class="mt-13 mt-md-0">
          <v-timeline dark>
            <v-timeline-item small color="#e31b6d" fill-dot>
              <v-row>
                <div class="color--red font-weight-bold">JMMI ITS</div>
                <div class="mt-2 text-subtitle-2">
                  Staff of Web Development Division part of Islamic Press
                </div>
              </v-row>
            </v-timeline-item>
            <v-timeline-item
              small
              color="#e31b6d"
              fill-dot
              class="mt-3 flex-row flex-md-row-reverse"
            >
              <v-row>
                <div class="color--red font-weight-bold">
                  Multimedia and Game Event 5 [MAGE 5]
                </div>
                <div class="mt-2 text-subtitle-2">
                  Annual event of Computer Engineering Departement ITS. (Staff
                  of Web Development Division)
                </div>
              </v-row>
            </v-timeline-item>
            <v-timeline-item small color="#e31b6d" fill-dot class="mt-3">
              <v-row>
                <div class="color--red font-weight-bold">
                  Event of Electrical Faculty [EVOLTY 2020]
                </div>
                <div class="mt-2 text-subtitle-2">
                  Annual event of Electrical Faculty ITS Consist of Some Event.
                  (Staff of Web Development Division)
                </div>
              </v-row>
            </v-timeline-item>
            <v-timeline-item
              small
              color="#e31b6d"
              fill-dot
              class="mt-3 flex-row flex-md-row-reverse"
            >
              <v-row>
                <div class="color--red font-weight-bold">
                  ITS Robot with Intelligent System [IRIS Team]
                </div>
                <div class="mt-2 text-subtitle-2">Programmer Division</div>
              </v-row>
            </v-timeline-item>
            <v-timeline-item small color="#e31b6d" fill-dot class="mt-3">
              <v-row>
                <div class="color--red font-weight-bold">
                  B201 Telematics Laboratory
                </div>
                <div class="mt-2 text-subtitle-2">
                  Laboratory assistant, doing research on network security
                  topics
                </div>
              </v-row>
            </v-timeline-item>
            <v-timeline-item
              small
              color="#e31b6d"
              fill-dot
              class="mt-3 flex-row flex-md-row-reverse"
            >
              <v-row>
                <div class="color--red font-weight-bold">
                  Multimedia and Game Event 6 [MAGE 6]
                </div>
                <div class="mt-2 text-subtitle-2">
                  Annual event of Computer Engineering Departement ITS. (Lead of
                  Website and IT Development Division, Supervised and help team
                  to build olympiad system based on fun game).
                </div>
              </v-row>
            </v-timeline-item>
          </v-timeline>
        </v-col>
      </v-row>
    </v-container>
    <v-container class="c-home bg--grey mt-16">
      <v-row>
        <v-col cols="12">
          <div class="color--red font-weight-bold text-h5 text-center">
            Education
          </div>
        </v-col>
      </v-row>
      <v-row class="mt-9">
        <v-col cols="12">
          <div class="text-center text-h5 font-weight-bold">
            <span class="color--red">"</span> No wealth like education and no
            poverty like ignorance <span class="color--red">"</span>
          </div>
          <div class="text-center color--red font-weight-bold">
            - Ali Ibn Abi Talib
          </div>
        </v-col>
      </v-row>
      <v-row class="mt-9">
        <v-col cols="12">
          <v-timeline dark>
            <v-timeline-item
              small
              color="#e31b6d"
              fill-dot
              class="mt-3 text-left"
            >
              <v-row>
                <v-col cols="12">
                  <div class="color--red font-weight-bold d-block">
                    SMP Negeri 1 Surabaya
                  </div>
                  <div class="mt-2 text-subtitle-2">2012 - 2015</div>
                </v-col>
              </v-row>
            </v-timeline-item>
            <v-timeline-item
              small
              color="#e31b6d"
              fill-dot
              class="mt-3 text-right"
            >
              <v-row>
                <v-col cols="12">
                  <div class="color--red font-weight-bold d-block">
                    SMA Negeri 2 Surabaya
                  </div>
                  <div class="mt-2 text-subtitle-2">2015 - 2018</div>
                </v-col>
              </v-row>
            </v-timeline-item>
            <v-timeline-item
              small
              color="#e31b6d"
              fill-dot
              class="mt-3 text-left"
            >
              <v-row>
                <v-col cols="12">
                  <div class="color--red font-weight-bold d-block">
                    Computer Engineering ITS Surabaya
                  </div>
                  <div class="mt-2 text-subtitle-2">2018 - Now</div>
                </v-col>
              </v-row>
            </v-timeline-item>
          </v-timeline>
        </v-col>
      </v-row>
    </v-container>
    <v-container class="c-home bg--grey mt-16">
      <v-row>
        <v-col cols="12">
          <div class="color--red font-weight-bold text-h5 text-center">
            Portofolio
          </div>
        </v-col>
      </v-row>
      <v-row>
        <v-col cols="12 d-flex justify-center">
          <v-btn
            text
            class="white--text font-weight-bold"
            @click="imagePortofolio('all')"
          >
            All
          </v-btn>
          <v-btn
            text
            class="white--text font-weight-bold"
            @click="imagePortofolio('js')"
          >
            Javascript / Php
          </v-btn>
          <v-btn
            text
            class="white--text font-weight-bold"
            @click="imagePortofolio('vue')"
          >
            Vue / Php
          </v-btn>
        </v-col>
      </v-row>
      <v-row class="mt-9 justify-center">
        <v-col v-for="img in portofolio" :key="img.id" cols="12" sm="4">
          <v-img
            :src="require('~/assets/img/' + img.link)"
            transition="scale-transition"
          ></v-img>
        </v-col>
      </v-row>
    </v-container>
    <v-container id="footer" fluid class="mt-16">
      <v-row
        class="d-flex align-center justify-center flex-column"
        style="height: 100%"
      >
        <div class="white--text text-sm-h4 text-h5 text-center">
          Feel free to contact
          <span style="color: #e31b6d">me</span>
          at
        </div>
        <div class="mt-9">
          <v-btn icon href="https://github.com" text class="px-7">
            <v-icon class="text-h3 color--icon"> mdi-linkedin </v-icon>
          </v-btn>
          <v-btn icon href="https://github.com" text class="px-7">
            <v-icon class="text-h3 color--icon"> mdi-instagram </v-icon>
          </v-btn>
          <v-btn icon href="https://github.com" text class="px-7">
            <v-icon class="text-h3 color--icon"> mdi-discord </v-icon>
          </v-btn>
        </div>
      </v-row>
    </v-container>
  </div>
</template>

<script>
// import Logo from '~/components/Logo.vue'
// import VuetifyLogo from '~/components/VuetifyLogo.vue'

export default {
  components: {},
  data() {
    return {
      test: 'test',
      portofolio: [
        { id: 1, link: 'esport.png' },
        { id: 2, link: 'evolty.png' },
        { id: 3, link: 'gamerstore.png' },
        { id: 4, link: 'jmmiits.png' },
        { id: 5, link: 'olim.png' },
        { id: 6, link: 'sewaaja.png' },
        { id: 7, link: 'mage6.png' },
        { id: 8, link: 'b201rent.png' },
        { id: 9, link: 'digdaya.png' },
      ],
      image: [
        { id: 1, link: 'esport.png' },
        { id: 2, link: 'evolty.png' },
        { id: 3, link: 'gamerstore.png' },
        { id: 4, link: 'jmmiits.png' },
        { id: 5, link: 'olim.png' },
        { id: 6, link: 'sewaaja.png' },
        { id: 7, link: 'mage6.png' },
        { id: 8, link: 'b201rent.png' },
        { id: 9, link: 'digdaya.png' },
      ],
    }
  },
  mounted() {
    this.$ga.page(this.$router)
    // eslint-disable-next-line no-console
    console.log('bismillah')
  },
  methods: {
    imagePortofolio(data) {
      // eslint-disable-next-line no-console
      // console.log(this.portofolio)
      switch (data) {
        case 'js':
          this.portofolio.splice(0, this.portofolio.length)
          this.portofolio = this.image.slice()
          this.portofolio.splice(6, 1)
          break
        case 'vue':
          this.portofolio.splice(0, this.portofolio.length)
          this.portofolio = this.image.slice(6, 7)
          break
        case 'all':
          this.portofolio.splice(0, this.portofolio.length)
          this.portofolio = this.image.slice()
          break
      }
    },
  },
}
</script>

<style lang="scss" scoped>
* {
  color: white;
  padding: 0;
  margin: 0;
  box-sizing: border-box;
}

#hero {
  height: 100vh !important;
  width: 100vw !important;
  background-color: #252934;
}
#footer {
  height: 100vh !important;
  width: 100vw !important;
  background-color: #252934;
}
.bg--grey {
  background-color: #252934;
}

.color--red {
  color: #e31b6d;
}

.l {
  &__imagediamond {
    width: 175px;
    height: 175px;
    background-color: white;
    transform: rotate(45deg);
    overflow: hidden;
  }
  &__imagesource {
    transform: rotate(-45deg) scale(1.42) translate(-1.5%, 7%);
    width: 100%;
    height: 100%;
    background: url('~assets/img/fotononformal4.png');
    background-size: cover;
  }
}

.c-home {
  padding: 5em 3em 5em 3em;
}

.bg-all {
  background-color: #1c1f27;
}

.pos-fixed {
  position: fixed !important;
}

.color--icon {
  color: white !important;
  &:hover {
    color: #e31b6d !important;
  }
}
</style>
