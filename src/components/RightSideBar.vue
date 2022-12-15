<template>
<div class="mt-8 ml-2">
    <v-row class="ml-0 pl-0">
        <v-col cols="1">
           <v-divider vertical></v-divider>
        </v-col>
        <v-col cols="1" class="pl-8">
            <div class="d-flex flex-column align-center">
                <v-badge class="ml-4" bordered top color="green accent-4" dot offset-x="10" offset-y="15">
            <v-avatar size="50">
                <v-img src="https://cdn.vuetifyjs.com/images/lists/2.jpg"></v-img>
            </v-avatar>
            </v-badge>
           
            <p class="font-weight-bold ml-6 mt-2"> Dr.Saif</p>
            
                <v-col style="margin-top: 440px;">
                    <v-icon dark color="black" class="mt-4">
                    mdi-lead-pencil
                </v-icon>
                <v-icon dark color="black" class="mt-4">
                    mdi-message-processing
                </v-icon>
                <v-btn class="mt-4 " fab dark small>
                <v-icon dark >
                    mdi-plus
                </v-icon>
            </v-btn>
                </v-col>
            
            
            </div>
           
            <!-- <v-badge class="ml-4" bordered top color="green accent-4" dot offset-x="30" offset-y="15">
            <v-avatar size="50">
                <v-img src="https://cdn.vuetifyjs.com/images/lists/2.jpg"></v-img>
            </v-avatar>
            <p>saif</p>
            <p>Scientist</p> -->
            
                <!-- <v-btn class="mx-2 mb-0 mt-2" fab dark small color="primary">
                    <v-icon dark>
                        mdi-minus
                    </v-icon>
                </v-btn>
                <v-btn class="mx-2 mb-0 mt-2" fab dark small color="primary">
                    <v-icon dark>
                        mdi-minus
                    </v-icon>
                </v-btn>
                <v-btn class="mx-2 mb-0 mt-2" fab dark small color="primary">
                    <v-icon dark>
                        mdi-minus
                    </v-icon>
                </v-btn> -->
    
        <!-- </v-badge> -->
        </v-col>
    </v-row>

       
</div>
</template>

<script>
export default {
    name: 'RightSideBar',

    data: () => ({
        //    alignments: [
        //        'start',
        //        'center',
        //        'end',
        //    ],
        // admins: [
        //     ['Management', 'mdi-account-multiple-outline'],
        //     ['Settings', 'mdi-cog-outline'],
        // ],
        // cruds: [
        //     ['Create', 'mdi-plus-outline'],
        //     ['Read', 'mdi-file-outline'],
        //     ['Update', 'mdi-update'],
        //     ['Delete', 'mdi-delete'],
        // ],
    }),
}
</script>
<style scoped>
.vl {
  border-left: 1px solid green;
  height: 500px;
}
</style>