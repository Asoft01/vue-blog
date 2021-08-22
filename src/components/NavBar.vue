<template>
    <div>
        <v-app-bar
            color="deep-purple accent-4"
            dark
            scroll-target="#scrolling-techniques-6"
            >
            <v-app-bar-nav-icon></v-app-bar-nav-icon>  

            <v-spacer></v-spacer>
            <router-link to="/" id="nav-icon">
                <v-btn icon>
                    <v-icon>mdi-home</v-icon>
                </v-btn>
            </router-link>
        </v-app-bar>
        
            <!-- <v-main>
                <h3 style="color:red">Content Body</h3>
            </v-main> -->
    </div>
</template>

<script>
export default {
    name: "NavBar"
}
</script>

<style scoped>
    #nav-icon{
        text-decoration: none;
    }
</style>