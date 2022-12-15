<template>
<v-app id="inspire">
    <div style=" padding: 20px; background-color: #fbf7f4; ">
        <v-row>
            <!-- <v-col cols="3">
                <div class="d-flex flex-column align-center mb-6">
                    <v-img src="../assets/logo1.png" max-height="50" max-width="50"></v-img>
                 <p>SOLARIUS</p>
                </div>
                <v-list style="background-color: #fbf7f4;">
                    <v-list-item>
                        <v-list-item-icon>
                            <v-icon>mdi-poll</v-icon>
                        </v-list-item-icon>

                        <v-list-item-title>Dashboard</v-list-item-title>
                    </v-list-item>
                    <v-list-item>
                        <v-list-item-icon>
                            <v-icon>mdi-google-circles-extended</v-icon>
                        </v-list-item-icon>

                        <v-list-item-title>Education</v-list-item-title>
                    </v-list-item>

                    <v-list-group :value="true" prepend-icon="mdi-book">
                        <template v-slot:activator>
                            <v-list-item-title>Resources</v-list-item-title>
                        </template>
                        
                        <v-list-item style="margin-left: 40px;">
                        <v-list-item-icon>
                            <v-icon small style="color: #e8c0c6;">mdi-checkbox-blank</v-icon>
                        </v-list-item-icon>

                        <v-list-item-title>Genetics 101</v-list-item-title>
                    </v-list-item>
                    <v-list-item style="margin-left: 40px;">
                        <v-list-item-icon>
                            <v-icon small style="color: #f9bf8e;">mdi-checkbox-blank</v-icon>
                        </v-list-item-icon>

                        <v-list-item-title>DNA </v-list-item-title>
                    </v-list-item>
                    <v-list-item style="margin-left: 40px;">
                        <v-list-item-icon>
                            <v-icon small style="color: #465f87;">mdi-checkbox-blank</v-icon>
                        </v-list-item-icon>

                        <v-list-item-title>Events</v-list-item-title>
                    </v-list-item>
                    
                    </v-list-group>
                    <v-list-item>
                        <v-list-item-icon>
                            <v-icon>mdi-cog</v-icon>
                        </v-list-item-icon>

                        <v-list-item-title>Settings</v-list-item-title>
                    </v-list-item>
                </v-list>
                <div  class="d-flex align-end flex-column">
                    <v-row >
                    <v-btn class="mx-2" fab dark small color="primary">
                        <v-icon dark>
                            mdi-minus
                        </v-icon>
                    </v-btn>
                    <p class="font-weight-black">
                        Log Out
                    </p>
                </v-row>
                </div>
                

            </v-col> -->
            <v-col cols="4">
                <v-card>
                    One of three columns
                </v-card>
            </v-col>
            <v-col cols="4">
                <v-row justify="space-between">
                    <p class="font-weight-black">
                        Monthly Pinned
                    </p>
                    <p class="font-weight-black">
                        View all
                    </p>
                </v-row>
                <v-row>
                    <template>
                        <v-card width="100%" class="pa-0 mx-auto" style="margin-top:10px; background-color:#fbf7f4" outlined>
                            <v-card-actions style="margin-left: 5px">
                                <v-card-text class="pa-0 ">Next-gen immuno</v-card-text>
                                <v-card-text class="pa-0 " style="margin-right: -330px;">5d</v-card-text>
                            </v-card-actions>
                            <v-card-title class="pa-0" style="margin-left: 10px"> Multispecific liquids analysis</v-card-title>
                            <v-card-actions class="pa-0 " style=" margin-left: 15px">
                                <v-badge color="green" content="1"></v-badge>
                                <v-card-subtitle style="margin-bottom: 10px; margin-left: 10px;">New feedback</v-card-subtitle>
                            </v-card-actions>
                        </v-card>
                        <v-spacer></v-spacer>
                        <v-card width="100%" class="pa-0 mx-auto" style="margin-top:10px;background-color:#fbf7f4" outlined>
                            <v-card-actions style="margin-left: 5px">
                                <v-card-text class="pa-0 ">Next-gen immuno</v-card-text>
                                <v-card-text class="pa-0 " style="
    margin-right: -330px;
">5d</v-card-text>
                            </v-card-actions>
                            <v-card-title class="pa-0" style="margin-left: 10px"> Multispecific liquids analysis</v-card-title>
                            <v-card-actions class="pa-0 " style=" margin-left: 15px">
                                <v-badge color="green" content="1"></v-badge>
                                <v-card-subtitle style="margin-bottom: 10px; margin-left: 10px;">New feedback</v-card-subtitle>
                            </v-card-actions>
                        </v-card>
                        <v-card width="100%" class="pa-0 mx-auto" style="margin-top:10px;background-color:#fbf7f4" outlined>
                            <v-card-actions style="margin-left: 5px">
                                <v-card-text class="pa-0 ">Next-gen immuno</v-card-text>
                                <v-card-text class="pa-0 " style="
    margin-right: -330px;
">5d</v-card-text>
                            </v-card-actions>
                            <v-card-title class="pa-0" style="margin-left: 10px"> Multispecific liquids analysis</v-card-title>
                            <v-card-actions class="pa-0 " style=" margin-left: 15px">
                                <v-badge color="green" content="1"></v-badge>
                                <v-card-subtitle style="margin-bottom: 10px; margin-left: 10px;">New feedback</v-card-subtitle>
                            </v-card-actions>
                        </v-card>

                    </template>
                </v-row>
                <v-row justify="space-between" style="margin-top: 30px;">
                    <p class="font-weight-black">
                        My learnings
                    </p>
                    <v-icon style="padding-bottom: 15px;">
                        mdi-dots-horizontal
                    </v-icon>
                </v-row>
                <div>
                    <p>
                        Your progress of medical lectures
                    </p>
                </div>
                <v-row>
                    <v-col>
                        <div>
                            <v-list-item>
                                <v-img src="../assets/viruses.png" max-height="50" max-width="50"></v-img>
                                <v-list-item-content style="padding-left: 10px;">
                                    <v-list-item-title style="font-weight: bold;">Viruse</v-list-item-title>
                                    <div>33% prog </div>
                                </v-list-item-content>

                            </v-list-item>
                        </div>
                    </v-col>

                    <v-col>
                        <div>
                            <v-list-item>
                                <v-img src="../assets/bet.png" max-height="50" max-width="50"></v-img>
                                <v-list-item-content style="padding-left: 10px;">
                                    <v-list-item-title style="font-weight: bold;">Cell</v-list-item-title>
                                    <div>33% prog </div>
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
                                <v-list-item-content style="padding-left: 10px;">
                                    <v-list-item-title style="font-weight: bold;">Med</v-list-item-title>
                                    <div>7% prog</div>
                                </v-list-item-content>

                            </v-list-item>
                        </div>
                    </v-col>

                    <v-col>
                        <div>
                            <v-list-item>
                                <v-img src="../assets/human.png" max-height="50" max-width="50"></v-img>
                                <v-list-item-content style="padding-left: 10px;">
                                    <v-list-item-title style="font-weight: bold;">Human</v-list-item-title>
                                    <div>58% prog</div>
                                </v-list-item-content>

                            </v-list-item>
                        </div>
                    </v-col>
                </v-row>

            </v-col>
            <v-col cols="1">
                <v-badge
        bordered
        top
        color="green accent-4"
        dot
        offset-x="10"
        offset-y="10"
      >
        <v-avatar size="40">
          <v-img src="https://cdn.vuetifyjs.com/images/lists/2.jpg"></v-img>
        </v-avatar>
      </v-badge>
            </v-col>
        </v-row>
    </div>
</v-app>
</template>

<script>
export default {
    name: 'HelloWorld',

    data: () => ({
        alignments: [
            'start',
            'center',
            'end',
        ],
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
