<template>
<div class="mt-8 ml-2">
    <div class="d-flex flex-column align-center mb-6">
        <v-img src="../assets/logo1.png" max-height="50" max-width="50"></v-img>
        <p class="text-h5 font-weight-bold">SOLARIUS</p>
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

            <v-list-item class="ml-4">
                <v-list-item-icon>
                    <v-icon small style="color: #e8c0c6;">mdi-checkbox-blank</v-icon>
                </v-list-item-icon>

                <v-list-item-title>Genetics</v-list-item-title>
            </v-list-item>
            <v-list-item class="ml-4">
                <v-list-item-icon>
                    <v-icon small style="color: #f9bf8e;">mdi-checkbox-blank</v-icon>
                </v-list-item-icon>

                <v-list-item-title>DNA </v-list-item-title>
            </v-list-item>
            <v-list-item class="ml-4">
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
    <div class="d-flex align-end ml-2">
        <v-row style="
    margin-top: 190px;
">
            <v-btn class="mx-2 " fab dark small>
                <v-icon dark>
                    mdi-logout
                </v-icon>
            </v-btn>
            <p class="font-weight-black ml-2 mt-2">
                Log Out
            </p>
        </v-row>
    </div>
</div>
</template>

<script>
export default {
    name: 'LeftSideBar',

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
