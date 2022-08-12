<template>
  <v-app id="home" :style="{ background: $vuetify.theme.themes.dark.background }">
    <NavBar />
    <v-container fluid>
      <v-row>
        <v-col cols="6">
          <v-img src="banner2.png" contain max-height="500"></v-img>
        </v-col>
        <v-col cols="6">
          <h5 class="yellow--text text-darken-4 top">Hello Im Gabriel</h5>
          <h1 class="white--text">Dev JR</h1>
          <p class="grey--text">Lorem ipsum dolor sit amet, consectetur adipiscing elit. Nam sit amet erat neque.
            Curabitur ut hendrerit libero. Vestibulum condimentum neque vitae porttitor tempus. Class aptent taciti
            sociosqu ad litora torquent per conubia nostra, per inceptos himenaeos.

          </p>
          <v-btn title color="#FAB005" dark>about me</v-btn>
        </v-col>
        <v-col cols="12" class="padd">
          <div class="first" id="projects">
            <v-row>
              <v-col cols="12">
                <div class="child bgColor1">
                  <v-icon color="#FAB005" x-large class="ml-3">
                    mdi-palette-swatch
                  </v-icon>
                  <h3 class="white--text ml-3 mt-4">UI Design</h3>
                  <p class="grey--text ml-3 mt-6">
                    Lorem ipsum dolor sit amet, <br />consectetur adipiscing elit.
                  </p>
                  <v-btn color="#FAB005" dark text>
                    Know More
                    <v-icon right>mdi-arrow-right</v-icon>
                  </v-btn>
                </div>
                <div class="child bgColor2">
                  <v-icon x-large class="ml-3" dark>mdi-shopping</v-icon>
                  <h3 class="white--text ml-3 mt-4">Product Design</h3>
                  <p class="dark--text ml-3 mt-6">Lorem ipsum dolor sit amet, <br />consectetur adipiscing elit.</p>
                  <v-btn dark text>
                    Know More
                    <v-icon right>mdi-arrow-right</v-icon>
                  </v-btn>
                </div>
                <div class="child bgColor1">
                  <v-icon color="#FAB005" x-large class="ml-3">mdi-book-open-page-variant</v-icon>
                  <h3 class="white--text ml-3 mt-4">Branding</h3>
                  <p class="grey--text ml-3 mt-6">
                    Lorem ipsum dolor sit amet, <br />consectetur adipiscing elit.
                  </p>
                  <v-btn color="#FAB005" dark text>
                    Know More
                    <v-icon right>mdi-arrow-right</v-icon>
                  </v-btn>
                </div>
              </v-col>
              <v-col cols="12" class="mt-10">
                <div class="child1">
                  <h1 class="yellow--text text--darken-4 mt-4 number">12</h1>
                  <h3 class="white--text mt-4">Years Experience</h3>
                </div>
                <div class="child2 mRight">
                  <v-row>
                    <v-col cols="12" class="childcol">
                      <div class="child2 mButton padding bgColor1">
                        <h1 class="yellow--text text--darken-4">60+</h1>
                        <p class="grey--text">Clients</p>
                      </div>
                    </v-col>
                    <v-col cols="12" class="childcol">
                      <div class="child2 padding bgColor1">
                        <h1 class="yellow--text text--darken-4">122+</h1>
                        <p class="grey--text">Completed Projects</p>
                      </div>
                    </v-col>
                  </v-row>
                </div>
                <div class="child2 ">
                  <v-row>
                    <v-col cols="12" class="childcol">
                      <div class="child2 mButton padding bgColor1">
                        <h1 class="yellow--text text--darken-4">08</h1>
                        <p class="grey--text">Years Experience</p>
                      </div>
                    </v-col>
                    <v-col cols="12" class="childcol">
                      <div class="child2 padding bgColor1">
                        <h1 class="yellow--text text--darken-4">10</h1>
                        <p class="grey--text">Achiements</p>
                      </div>
                    </v-col>
                  </v-row>
                </div>
              </v-col>
            </v-row>
          </div>
        </v-col>
        <v-col md="3" offset-md="3" id="about">
          <h4 class="white--text">FEATURED PROJECTS</h4>
          <p class="grey--text">Lorem ipsum dolor sit amet consectetur</p>
        </v-col>
        <v-col md="3" class="text-end">
          <v-btn title color="#FAB005" dark>View All</v-btn>
        </v-col>
        <v-col md="3" offset-md="3">
          <v-card class="pa-2 py-12" outlined tile height="300px" color="#1e1e1e">
            <v-img src="vue.png" contain></v-img>
          </v-card>
        </v-col>
        <v-col md="3">
          <v-card class="pa-2 py-12" outlined tile height="300px" color="#1e1e1e">
            <v-img src="java3.png" contain></v-img>
          </v-card>
        </v-col>
        <v-col md="3" offset-md="3">
          <v-btn color="white" dark text class="ml-n4">
            Vue JS
          </v-btn><br />
          <v-btn color="#FAB005" dark text class="ml-n4">
            Know More
            <v-icon right>mdi-arrow-right</v-icon>
          </v-btn>
        </v-col>
        <v-col md="3">
          <v-btn color="white" dark text class="ml-n4">
            Java
          </v-btn><br />
          <v-btn color="#FAB005" dark text class="ml-n4">
            Know More
            <v-icon right>mdi-arrow-right</v-icon>
          </v-btn>
        </v-col>
        <v-col md="3" offset-md="3">
          <v-card class="pa-2 py-12" outlined tile height="370px" color="#1e1e1e">
            <v-img src="js2.png" contain></v-img>
          </v-card>
        </v-col>
        <v-col md="3">
          <v-card class="pa-2 py-12" outlined tile height="370px" color="#1e1e1e">
            <v-img src="node.png" contain></v-img>
          </v-card>
        </v-col>
        <v-col md="3" offset-md="3">
          <v-btn color="white" dark text class="ml-n4">
            Java Script
          </v-btn><br />
          <v-btn color="#1e1e1e" dark text class="ml-n4">
            Know More
            <v-icon right>mdi-arrow-right</v-icon>
          </v-btn>
        </v-col>
        <v-col md="3">
          <v-btn color="white" dark text class="ml-n4">
            Node JS
          </v-btn><br />
          <v-btn color="#1e1e1e" dark text class="ml-n4">
            Know More
            <v-icon right>mdi-arrow-right</v-icon>
          </v-btn>
        </v-col>
        <v-col cols="12" class="padd topInverse">
          <div class="second">
            <div class="secondchild1" id="contact">
              <v-row>
                <v-col cols="7">
                  <h1 class="white--text">
                    Let's work together on <br /> your next project
                  </h1>
                  <p></p>
                  <p class="grey--text">Lorem ipsum dolor sit amet, consectetur adipiscing elit.
                    In egestas consequatauctor.<br />
                  </p>
                </v-col>
                <v-col cols="5">
                  <v-btn title-color="#FAB005" dark class="mt-16">
                    Contact
                  </v-btn>
                </v-col>
              </v-row>
            </div>
          </div>
          <v-toolbar class="topTolbar" color="#111111" dark flat>
            <div
              style="position: absolute; margin-left: auto; margin-right: auto; left: 0; right: 0; text-align: center;">
              <v-btn text>Home</v-btn>
              <v-btn text>Projects</v-btn>
              <v-btn text>About</v-btn>
              <v-btn text>Contact</v-btn>
            </div>
          </v-toolbar>
        </v-col>
      </v-row>
    </v-container>
    <FooterPage></FooterPage>
  </v-app>

</template>

<script>
import NavBar from '../components/NavBar'
import FooterPage from '../components/FooterPage.vue'

export default {
  name: 'HomeView',

  components: {
    NavBar,
    FooterPage
},
}
</script>

<style scoped>
.top {
  margin-top: 180px;
}

.topInverse {
  margin-top: -250px;
}

.topTolbar {
  margin-top: 100px;
  text-align: center;
}

.first {
  width: 100%;
  height: 610px;
  background: linear-gradient(to right,
      #181818,
      #181818 50%,
      #111111 50%,
      #111111 50%);
  text-align: center;
  padding: 2rem 2rem;
}

.second {
  width: 100%;
  height: 400px;
  background: #FAB005;
  text-align: center;
  padding: 2rem 2rem;
}

.secondchild1 {
  display: inline-block;
  background-color: #1e1e1e;
  padding: 2rem 1rem;
  vertical-align: middle;
  text-align: left;
  margin-top: 250px;
}

.child {
  display: inline-block;
  padding: 2rem 1rem;
  vertical-align: middle;
  text-align: left;
  margin-right: 8px;
}

.bgColor1 {
  background-color: #1e1e1e;
}

.bgColor2 {
  background-color: #f7c54f;
}

.child1 {
  display: inline-block;
  padding: 2rem 1rem;
  vertical-align: middle;
  margin-right: 5px;
  width: 240px;
}

.child2 {
  display: inline-block;
  width: 245px;
  vertical-align: middle;
}

.mRight {
  margin-right: 8px;
}

.mButton {
  margin-bottom: 8px;
}

.padding {
  padding: 8px 0;
}

.col-12.padd {
  padding: 12px 0 !important;
}

.col-12.childcol {
  padding: 0 !important;
}

h1.number {
  font-size: 50px;
  font-weight: bold;
}
</style>
