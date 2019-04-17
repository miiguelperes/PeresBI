<template>
  <div class="hello">
    <v-content >
      <div id="top"></div>
        <section class="top-one">
          <v-parallax src="static/BG.gif" height="660">
            <v-layout column align-center justify-center class="white--text">
              <div style="margin-top:-50px;z-index:2;">
                <a href="#" v-scroll-to="'#sobre'">
                  <img src="static/peresW.svg" alt="Vuetify.js" class="logo-main" height="100">
                </a>
              </div>
              <div class="particles-box">
                <vue-particles
                  color="#fff"
                  :particleOpacity="0.5"
                  :particlesNumber="90"
                  shapeType="polygon"
                  :particleSize="4"
                  linesColor="#dedede"
                  :linesWidth="1"
                  :lineLinked="true"
                  :lineOpacity="0.4"
                  :linesDistance="130"
                  :moveSpeed="3"
                  :hoverEffect="true"
                  hoverMode="grab"
                  :clickEffect="true"
                  clickMode="push"
                  style="height:100%"
                ></vue-particles>
              </div>
              <div class="shadow"></div>
            </v-layout>
          </v-parallax>
        </section>
      
      <section id="sobre">
        <v-layout column wrap class="my-5" align-center>
          <v-flex xs12 sm4 class="my-3">
            <div class="text-xs-center" style="margin-top: 65px">
              <h2 class="headline">The best way to start developing</h2>
              <span class="subheading">Cras facilisis mi vitae nunc</span>
            </div>
          </v-flex>
          <v-flex xs12>
            <v-container grid-list-xl>
              <v-layout row wrap align-center>
                <v-flex xs12 md4>
                  <v-card class="elevation-0 transparent">
                    <v-card-text class="text-xs-center">
                      <v-icon x-large class="color-icon">color_lens</v-icon>
                    </v-card-text>
                    <v-card-title primary-title class="layout justify-center">
                      <div class="headline text-xs-center">Material Design</div>
                    </v-card-title>
                    <v-card-text>
                      Cras facilisis mi vitae nunc lobortis pharetra. Nulla volutpat tincidunt ornare.
                      Pellentesque habitant morbi tristique senectus et netus et malesuada fames ac turpis egestas.
                      Nullam in aliquet odio. Aliquam eu est vitae tellus bibendum tincidunt. Suspendisse potenti.
                    </v-card-text>
                  </v-card>
                </v-flex>
                <v-flex xs12 md4>
                  <v-card class="elevation-0 transparent">
                    <v-card-text class="text-xs-center">
                      <v-icon x-large class="color-icon">flash_on</v-icon>
                    </v-card-text>
                    <v-card-title primary-title class="layout justify-center">
                      <div class="headline">Fast development</div>
                    </v-card-title>
                    <v-card-text>
                      Cras facilisis mi vitae nunc lobortis pharetra. Nulla volutpat tincidunt ornare.
                      Pellentesque habitant morbi tristique senectus et netus et malesuada fames ac turpis egestas.
                      Nullam in aliquet odio. Aliquam eu est vitae tellus bibendum tincidunt. Suspendisse potenti.
                    </v-card-text>
                  </v-card>
                </v-flex>
                <v-flex xs12 md4>
                  <v-card class="elevation-0 transparent">
                    <v-card-text class="text-xs-center">
                      <v-icon x-large class="color-icon">build</v-icon>
                    </v-card-text>
                    <v-card-title primary-title class="layout justify-center">
                      <div class="headline text-xs-center">Completely Open Sourced</div>
                    </v-card-title>
                    <v-card-text>
                      Cras facilisis mi vitae nunc lobortis pharetra. Nulla volutpat tincidunt ornare.
                      Pellentesque habitant morbi tristique senectus et netus et malesuada fames ac turpis egestas.
                      Nullam in aliquet odio. Aliquam eu est vitae tellus bibendum tincidunt. Suspendisse potenti.
                    </v-card-text>
                  </v-card>
                </v-flex>
              </v-layout>
            </v-container>
          </v-flex>
        </v-layout>
      </section>

      <section class="one">
        <v-parallax src="static/nw.jpg" height="490">
          <v-layout align-center justify-center>
            <v-flex xs12 sm12 md7>
              <div class="headline white--text mb-3 text-xs-center">
                <h4>Uma empresa construída em torno de entender melhor o que as empresas realmente querem e precisam</h4>
              </div>
              <em>
                <p>A pesquisa aprofundada sustenta o desenvolvimento de todos os produtos, resultando em informações e agendas de eventos altamente focadas e cuidadosamente selecionadas.</p>
                <p>Como pioneiros no uso de conteúdo para desenvolvimento e marketing da comunidade, fomentamos o contato durante todo o ano com nossos clientes. A qualidade e o valor das informações que geramos atraem lealdade e sustentam por que nossas marcas são consideradas líderes em seus respectivos mercados.</p>
              </em>
              <div class="shadow"></div>
            </v-flex>
          </v-layout>
        </v-parallax>
      </section>

      <section>
        <v-container grid-list-xl>
          <v-layout row wrap justify-center class="my-5">
            <v-flex xs12 sm4>
              <v-card class="elevation-0 transparent">
                <v-card-title primary-title class="layout justify-center">
                  <div class="headline">Company info</div>
                </v-card-title>
                <v-card-text>
                  Cras facilisis mi vitae nunc lobortis pharetra. Nulla volutpat tincidunt ornare.
                  Pellentesque habitant morbi tristique senectus et netus et malesuada fames ac turpis egestas.
                  Nullam in aliquet odio. Aliquam eu est vitae tellus bibendum tincidunt. Suspendisse potenti.
                </v-card-text>
              </v-card>
            </v-flex>
            <v-flex xs12 sm4 offset-sm1>
              <v-card class="elevation-0 transparent">
                <v-card-title primary-title class="layout justify-center">
                  <div class="headline">Contact us</div>
                </v-card-title>
                <v-card-text>Cras facilisis mi vitae nunc lobortis pharetra. Nulla volutpat tincidunt ornare.</v-card-text>
                <v-list class="transparent">
                  <v-list-tile>
                    <v-list-tile-action>
                      <v-icon class="color-icon">phone</v-icon>
                    </v-list-tile-action>
                    <v-list-tile-content>
                      <v-list-tile-title>777-867-5309</v-list-tile-title>
                    </v-list-tile-content>
                  </v-list-tile>
                  <v-list-tile>
                    <v-list-tile-action>
                      <v-icon class="color-icon">place</v-icon>
                    </v-list-tile-action>
                    <v-list-tile-content>
                      <v-list-tile-title>Chicago, US</v-list-tile-title>
                    </v-list-tile-content>
                  </v-list-tile>
                  <v-list-tile>
                    <v-list-tile-action>
                      <v-icon class="color-icon">email</v-icon>
                    </v-list-tile-action>
                    <v-list-tile-content>
                      <v-list-tile-title>john@vuetifyjs.com</v-list-tile-title>
                    </v-list-tile-content>
                  </v-list-tile>
                </v-list>
              </v-card>
            </v-flex>
          </v-layout>
        </v-container>
      </section>

      <v-footer class="blue darken-2">
        <v-layout row wrap align-center>
          <v-flex xs12>
            <div class="white--text ml-3">
              Feito com
              <v-icon class="red--text">favorite</v-icon>by
              <a class="white--text" href="#" target="_blank">Peres</a>
            </div>
          </v-flex>
        </v-layout>
      </v-footer>
    </v-content>
  </div>
</template>

<script>
export default {
  name: "HelloWorld",
  data() {
    return {
      msg: "Welcome to Your Vue.js App"
    };
  }
};
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
h1,
h2 {
  font-weight: normal;
}
ul {
  list-style-type: none;
  padding: 0;
}
li {
  display: inline-block;
  margin: 0 10px;
}
a {
  color: #42b983;
}
.particles-box {
  z-index: 1;
  position: fixed;
  width: 100%;
  top: 0;
  height: 100%;
  left: 0;
}
.logo-main path {
  fill: #fff;
}
.shadow {
  background: rgba(0, 0, 0, 0.6);
  width: 100%;
  height: 100%;
  top: 0px;
  z-index: -1;
  left: 0px;
  position: absolute;
}
.color-icon {
  color: #0a406d !important;
  caret-color: #0a406d !important;
}
</style>
