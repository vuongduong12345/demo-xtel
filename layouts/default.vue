<template>
  <v-app dark>
    <v-app-bar fixed app class="blue-grey lighten-5">
      <v-container class="py-0">
        <v-row align="center">
          <div class="logo"><v-img src="/logo.png" width="100%"></v-img></div>
          <v-spacer></v-spacer>
          <client-only>
            <div v-if="breakpoint === 'desktop'">
              <v-hover v-slot:default="{ hover }">
                <v-btn
                  :class="
                    (hover && 'primary--text') + ' text-none no-background'
                  "
                  text
                  active-class="primary--text"
                  to="/"
                  >Home</v-btn
                >
              </v-hover>
              <v-hover v-slot:default="{ hover }">
                <v-btn
                  :class="
                    (hover && 'primary--text') + ' text-none no-background'
                  "
                  text
                  active-class="primary--text"
                  to="/service"
                  >Services</v-btn
                >
              </v-hover>
              <v-hover v-slot:default="{ hover }">
                <v-btn
                  :class="
                    (hover && 'primary--text') + ' text-none no-background'
                  "
                  text
                  active-class="primary--text"
                  to="/about-us"
                  >About Us</v-btn
                >
              </v-hover>
              <v-hover v-slot:default="{ hover }">
                <v-btn
                  :class="
                    (hover && 'primary--text') + ' text-none no-background'
                  "
                  text
                  active-class="primary--text"
                  to="/news"
                  >News</v-btn
                >
              </v-hover>
              <v-hover v-slot:default="{ hover }">
                <v-btn
                  :class="
                    (hover && 'primary--text') + ' text-none no-background'
                  "
                  text
                  active-class="primary--text"
                  to="/careers"
                  >Careers</v-btn
                >
              </v-hover>
              <v-hover v-slot:default="{ hover }">
                <v-btn
                  :class="
                    (hover && 'primary--text') + ' text-none no-background'
                  "
                  text
                  active-class="primary--text"
                  to="/contact"
                  >Contact</v-btn
                >
              </v-hover>
            </div>
            <div v-else>
              <v-app-bar-nav-icon
                @click="drawer = !drawer"
              ></v-app-bar-nav-icon>
            </div>
          </client-only>
        </v-row>
      </v-container>
    </v-app-bar>
    <v-navigation-drawer v-model="drawer" temporary app>
      <v-divider></v-divider>

      <v-list dense nav>
        <v-list-item v-for="item in items" :key="item.title" :to="item.path">
          <v-list-item-icon>
            <v-icon>{{ item.icon }}</v-icon>
          </v-list-item-icon>

          <v-list-item-content>
            <v-list-item-title>{{ item.title }}</v-list-item-title>
          </v-list-item-content>
        </v-list-item>
      </v-list>
    </v-navigation-drawer>
    <!-- <v-navigation-drawer v-model="drawer" absolute temporary>
            <v-divider></v-divider>

            <v-list dense>
              <v-list-item v-for="item in items" :key="item.title" link>
                <v-list-item-icon>
                  <v-icon>{{ item.icon }}</v-icon>
                </v-list-item-icon>

                <v-list-item-content>
                  <v-list-item-title>{{ item.title }}</v-list-item-title>
                </v-list-item-content>
              </v-list-item>
            </v-list>
    </v-navigation-drawer> -->
    <v-content>
      <v-container fluid class="pa-0">
        <nuxt />
      </v-container>
    </v-content>
    <!-- <v-footer dark class="pt-0">
      <div class="container">
        <div>
          <v-row>
            <v-col :class="breakpoint==='mobile'&&'image'" cols="6" md="6">
              <v-img src="/logo2.png" width="170"></v-img>
            </v-col>
            <v-col cols="12" md="6">
              <div align="center">
                5th floor, A-D Building, No 15, Lane 82 Dich Vong Hau, Cau Giay,
                Ha Noi
              </div>
              <div align="center">Phone: (+84)24 3200 3138</div>
              <div align="center">Email: contact@xtel.vn</div>
            </v-col>
          </v-row>
          <v-divider class="white"></v-divider>
          <div>
            <div>
              <v-btn icon href="https://www.facebook.com/">
                <v-icon>mdi-facebook</v-icon>
              </v-btn>
              <v-btn icon href="https://twitter.com/login?lang=vi">
                <v-icon>mdi-twitter-box</v-icon></v-btn
              >
            </div>
            <div align="right">
              Copyright © 2019 XTEL,.JSC. All Rights Reserved.
            </div>
          </div>
        </div>
      </div>
    </v-footer> -->
    <v-footer dark class="pt-0">
      <div class="container">
        <div>
          <v-row>
            <v-col cols="12" sm="3" align="center">
              <v-img src="/logo2.png" max-width="170"></v-img>
            </v-col>
            <v-col cols="12" sm="9">
              <div align="center">
                5th floor, A-D Building, No 15, Lane 82 Dich Vong Hau, Cau Giay,
                Ha Noi
              </div>
              <div align="center">Phone: (+84)24 3200 3138</div>
              <div align="center">Email: contact@xtel.vn</div>
            </v-col>
          </v-row>
          <v-divider class="white"></v-divider>
          <v-row justify="space-between">
            <v-col
              cols="12"
              sm="3"
              class="d-flex align-center pt-0 justify-sm-start justify-center"
            >
              <v-btn icon href="https://www.facebook.com">
                <v-icon>mdi-facebook</v-icon>
              </v-btn>
              <v-btn icon href="https://twitter.com/?lang=vi">
                <v-icon>mdi-twitter</v-icon>
              </v-btn>
            </v-col>

            <v-col
              cols="12"
              sm="9"
              class="d-flex align-center pt-0 text-center justify-sm-end"
              >Copyright © 2019 XTEL,.JSC. All Rights Reserved.</v-col
            >
          </v-row>
        </div>
      </div>
    </v-footer>
  </v-app>
</template>

<script>
export default {
  data() {
    return {
      drawer: null,
      items: [
        { title: "Home", icon: "mdi-home", path: "/" },
        { title: "Service", icon: "mdi-book-open", path: "/Service" },
        {
          title: "About us",
          icon: "mdi-information-variant",
          path: "/About-us"
        },
        { title: "New", icon: "mdi-new-box", path: "/News" },
        { title: "Careers", icon: "mdi-help-box", path: "/Careers" },
        { title: "Contact", icon: "mdi-contact-mail", path: "/Contact" }
      ]
    };
  },
  computed: {
    breakpoint() {
      switch (this.$vuetify.breakpoint.name) {
        case "xs":
          return "mobile";
        case "sm":
          return "mobile";
        case "md":
          return "desktop";
        case "lg":
          return "desktop";
        case "xl":
          return "desktop";
        default:
          return "desktop";
      }
    }
  }
};
</script>
<style lang="scss" scoped>
.no-background:before {
  background-color: unset;
}
</style>
