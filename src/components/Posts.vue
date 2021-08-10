<template>
    <div style="max-height: 100vh">
        <v-card class="my-1" flat id="theme">
            <div class="d-flex justify-between">
                <div>
                    <v-card-title class="textTitle white--text">
                        Authentication with Passport
                    </v-card-title>
                    <v-card-text class="subTitle white--text mt-2">
                        A one to one polymorphic relation similar to a simple one to one relation; however, the target model can belong to more 
                        than one type of model on a single association.
                    </v-card-text>
                    <v-card-actions>
                        <v-icon class="mr-1" color="cyan lighten-3" small> mdi-eye</v-icon>
                        <span class="body-2 mr-2 white--text">23</span>
                        <span class="mr-1">-</span>
                        <v-icon class="mr-2" color="blue-grey lighten-5">mdi-timer</v-icon>
                        <span class="body-2 white--text">4 minutes ago</span>
                        <v-spacer></v-spacer>
                    </v-card-actions>
                </div>
                
                <div class="flex-grow-1 flex-shrink-0">
                    <v-card-title class="white--text">
                        15th August 2021
                    </v-card-title>
                    <div class="text-center mt-3">
                        <v-chip color="yellow">
                            Javascript
                        </v-chip>
                    </div>
                </div>
            </div>
        </v-card>
    </div>
</template>

<style scoped>
    #theme{
        background-color: #1E2227;
        font-family: 'Monterrot', ;
    }
    #theme:hover{
        background: #282C34;
        cursor: pointer;
    }
</style>