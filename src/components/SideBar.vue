<template>
    <div>
        <v-card flat id="themeBackground">
            <v-img
                height="150"
                src="../assets/images/profile.png"
                >
                <v-card-title class="align-end fill-height">Hello World</v-card-title>
            </v-img>
            <v-card-text class="white--text body-2 px-0">
                Hi, I am Adeleke Hammed 
            </v-card-text>
            <v-card-actions>
                <a class="twitter-follow-button" href="https://twitter.com/lekhad19" data-size="large">
                    Follow @A-Soft
                </a>
            </v-card-actions>

            <v-divider></v-divider>
            <v-card-title class="align-end white--text font-weight-bold">
                Free Dev-Books
            </v-card-title>
            <div>
                <v-btn class="mr-1 font-weight-bold" text color="white">
                    <v-icon left color="cyan lighten-3">mdi react</v-icon>
                </v-btn>
            </div>
            <div>
                <v-btn class="mr-1 font-weight-bold" text color="white">
                    <v-icon left color="cyan lighten-3">Angular</v-icon>
                </v-btn>
            </div>
            <div>
                <v-btn class="mr-1 font-weight-bold" text color="white">
                    <v-icon left color="cyan lighten-3">Node JS</v-icon>
                </v-btn>
            </div>
            <v-divider></v-divider>
            <!-- <v-chip :color="getColor(category)" @click="getCategoryPosts(category)" v-for="category in categories" :key="category.id" label small class="md-1">
                {{ category.name }}
            </v-chip> -->

            <v-chip color="red accent-2" label small class="md-1">
                Vue
            </v-chip>
             <v-chip color="yellow accent-2" label small class="md-1">
                Javascript
            </v-chip> <v-chip color="green accent-2" label small class="md-1">
                Node
            </v-chip> <v-chip color="red accent-2" label small class="md-1">
                Vue
            </v-chip>
        </v-card>
    </div>
</template>

<style>
    #themeBackground{
        background-color: #1E2227;
    }
</style>