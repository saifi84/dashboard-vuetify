<template>
<div class="mt-8 ml-4">
    <v-row justify="space-between">
        <p class="font-weight-black">
            Monthly Pinned
        </p>
        <p class="font-weight-light caption">
            View all
        </p>
    </v-row>
    <v-row>
        <template>
            <v-card width="100%" class="pa-0 mt-2 mx-auto" style="background-color:#fbf7f4" outlined>
                <v-card-actions class="ml-2" >
                    <v-card-text class="pa-0 ">Next-gen immuno</v-card-text>
                    <v-card-text class="pa-0 font-weight-light caption " style="margin-right: -330px;">5d</v-card-text>
                </v-card-actions>
                <v-card-title class="pa-0 ml-4" > Multispecific liquids analysis</v-card-title>
                <v-card-actions class="pa-0 ml-5" >
                    <v-badge color="#f9bf8e" content="1"></v-badge>
                    <v-card-subtitle class="mb-3 ml-3" >New feedback</v-card-subtitle>
                </v-card-actions>
            </v-card>
            <v-card width="100%" class="pa-0 mt-2 mx-auto" style="background-color:#fbf7f4" outlined>
                <v-card-actions class="ml-2" >
                    <v-card-text class="pa-0 ">Harmony</v-card-text>
                    <v-card-text class="pa-0 font-weight-light caption " style="margin-right: -330px;">1h</v-card-text>
                </v-card-actions>
                <v-card-title class="pa-0 ml-4" > Multispecific liquids analysis</v-card-title>
                <v-card-actions class="pa-0 ml-5" >
                    <v-badge color="grey" content="!"></v-badge>
                    <v-card-subtitle class="mb-3 ml-3" >Deadline is today</v-card-subtitle>
                </v-card-actions>
            </v-card>
            <v-card width="100%" class="pa-0 mt-2 mx-auto" style="background-color:#fbf7f4" outlined>
                <v-card-actions class="ml-2" >
                    <v-card-text class="pa-0 ">Pharm</v-card-text>
                    <v-card-text class="pa-0 font-weight-light caption " style="margin-right: -330px;">7h</v-card-text>
                </v-card-actions>
                <v-card-title class="pa-0 ml-4" > Qucik element dissolution</v-card-title>
                <v-card-actions class="pa-0 ml-5" >
                    <v-badge
          color="deep-purple accent-4" icon="mdi-check">
        </v-badge>
                    <v-card-subtitle class="mb-3 ml-3" >Accepted</v-card-subtitle>
                </v-card-actions>
            </v-card>
        </template>
    </v-row>
    <v-row justify="space-between" class="mt-7 ml-0">
        <p class="font-weight-black">
            My learnings
        </p>
        <v-icon class="pb-4">
            mdi-dots-horizontal
        </v-icon>
    </v-row>
    <div>
        <p class="pa-0 font-weight-light caption ">
            Your progress of medical lectures
        </p>
    </div>
    <v-row>
        <v-col>
            <div>
                <v-list-item>
                    <v-img src="../assets/viruses.png" max-height="50" max-width="50"></v-img>
                    <v-list-item-content class="pl-3">
                        <v-list-item-title class="font-weight-bold">Viruse</v-list-item-title>
                        <div class="font-weight-light caption">96% progress </div>
                    </v-list-item-content>

                </v-list-item>
            </div>
        </v-col>

        <v-col>
            <div>
                <v-list-item>
                    <v-img src="../assets/bet.png" max-height="50" max-width="50"></v-img>
                    <v-list-item-content class="pl-3">
                        <v-list-item-title class="font-weight-bold">Bacterial Cell</v-list-item-title>
                        <div class="font-weight-light caption">33% progress </div>
                    </v-list-item-content>

                </v-list-item>
            </div>
        </v-col>
    </v-row>
    <v-row>
        <v-col>
            <div>
                <v-list-item>
                    <v-img src="../assets/med.png" max-height="50" max-width="50"></v-img>
                    <v-list-item-content class="pl-3">
                        <v-list-item-title class="font-weight-bold">Med Scinece</v-list-item-title>
                        <div class="font-weight-light caption">7% progress </div>
                    </v-list-item-content>

                </v-list-item>
            </div>
        </v-col>

        <v-col>
            <div>
                <v-list-item>
                    <v-img src="../assets/human.png" max-height="50" max-width="50"></v-img>
                    <v-list-item-content class="pl-3">
                        <v-list-item-title class="font-weight-bold">Human gens</v-list-item-title>
                        <div class="font-weight-light caption">58% progress </div>
                    </v-list-item-content>

                </v-list-item>
            </div>
        </v-col>
    </v-row>

</div>
</template>

<script>
export default {
    name: 'MonthlyPinned',

    data: () => ({
       
    }),
}
</script>
