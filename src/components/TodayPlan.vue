<template>
<div>
    <div class="pa-6" style="background-color:white">
        <v-row>
            <v-col>
                <v-list-item-content>
                    <v-list-item-title class="font-weight-bold">
                        Today's Plan
                    </v-list-item-title>
                    <v-list-item-subtitle class="font-weight-light caption">June 14th, 2022</v-list-item-subtitle>
                </v-list-item-content>
                <!-- <p class="font-weight-bold" >Today's Plan</p>
                <p class="font-weight-light caption pb-2">June 14th, 2022</p> -->
            </v-col>
            <v-btn fab dark small class="mt-5">
                <v-icon dark>
                    mdi-plus
                </v-icon>
            </v-btn>
        </v-row>
        <p class="font-weight-bold" style=" font-size: 20px;">Sustainable development goals and health innovation</p>

        <div class="avatars ">
            <v-row justify="space-between">
                <div class="pt-4">
                    <span class="avatar">
                    <img src="../assets/p1.jpg" width="40" height="40" />
                </span>
                <span class="avatar">
                    <img src="../assets/p2.jpg" width="40" height="40" />
                </span>
                <span class="avatar">
                    <img src="../assets/p3.jpg" width="40" height="40" />
                </span>
                <span class="avatar">
                    <v-btn class="plus5" fab small  color="#f9bf8e">
                        <v-icon dark>
                    mdi-plus
                </v-icon>
            </v-btn>
                </span>
                </div>
                <v-col>
                    <v-row>
                        <v-divider class="ml-16 pl-16 mb-4 mt-3" vertical></v-divider>
                        <v-list-item-content class="ml-2">
                        <v-list-item-title class="subtitle-2">
                            Medi Team Meating
                        </v-list-item-title>
                        <v-list-item-subtitle class="font-weight-light caption">13:30 - 14:00</v-list-item-subtitle>
                    </v-list-item-content>
                    </v-row>
                    
                    <!-- <p class="font-weight-bold">Medi Team Meating</p>
                <p class="font-weight-light caption pb-2">13:30 - 14:00</p> -->
                </v-col>
            </v-row>

            <!-- Variable amount more avatars -->
        </div>
        <v-card class="mx-auto pa-1 mt-6" max-width="365" outlined>
            <v-list-item three-line>
                <v-list-item-content>
                    <v-list-item-title class="text-h5 mb-1">
                        Weekly Report
                    </v-list-item-title>
                    <v-list-item-subtitle>Track your perfomance</v-list-item-subtitle>
                </v-list-item-content>
            </v-list-item>
            <v-spacer></v-spacer>
            <v-card-actions class="mt-8">
                <v-btn outlined text>
                    View Report
                </v-btn>
            </v-card-actions>
        </v-card>
        <v-row class="mt-4">
            <v-card class="mx-auto" max-width="170" height="270" outlined>
                <v-list-item three-line>
                    <v-list-item-content>
                        <v-list-item-title class="text-h5 mb-1">
                            Study
                        </v-list-item-title>
                        
                        <v-list-item-subtitle>In progress</v-list-item-subtitle>
                    </v-list-item-content>
                </v-list-item>

            </v-card>
            <v-card class="mx-auto" max-width="170" height="270" outlined>
                <v-list-item three-line>
                    <v-list-item-content>
                        <v-list-item-title class="text-h5 mb-1">
                            Analyses
                        </v-list-item-title>
                        <v-list-item-subtitle>Completed</v-list-item-subtitle>
                    </v-list-item-content>
                </v-list-item>

            </v-card>
        </v-row>

    </div>
</div>
</template>

<script>
export default {
    name: 'TodayPlan',

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
.avatar img {
    border-radius: 50%;
    position: relative;
    left: -5px;
    margin-left: -20px;
    z-index: 1;
}
.plus5{
    border-radius: 50%;
    position: relative;
    left: -5px;
    margin-left: -20px;
    z-index: 1;
    margin-bottom: 30px;
}

.avatars {
    direction: ltr;
    /* This is to get the stack with left on top */
    text-align: left;
    /* Now need to explitly align left */
    padding-left: 35px;
    /* Same value as the negative margin */
}
</style>
