<template>
  <div id="background">
    <NavBar/>
    <v-content>
      <v-container fill-height>
        <v-row>
          <v-col md="3">
            <div>
              <SideBar/>
            </div>
          </v-col>
          <v-col md="9">
              <!-- <h3>Content</h3> -->
              <router-view></router-view>
          </v-col>
        </v-row>
      </v-container>
    </v-content>
  </div>
</template>

<script>
import NavBar from '../components/NavBar'
import SideBar from '../components/SideBar';
export default {
  name: "Home",
  components: {
    NavBar,
    SideBar
  }
}
</script>

<style scoped>
    #background{
      background-color: #1E2227;
    }
</style>