<template>
<v-app>
    <v-main>
        <div class="pa-5" style=" background-color: #fbf7f4; ">
            <v-row>
                <v-col xs="12" sm="6" md="2">
                    <LeftSideBar />
                </v-col>
                <v-col xs="12" sm="6" md="4">
                    <TodayPlan />
                </v-col>
                <v-col xs="12" sm="6" md="4">
                    <MonthlyPinned />
                </v-col>
                <v-col xs="12" sm="6" md="2">
                    <RightSideBar />
                </v-col>
            </v-row>
        </div>

    </v-main>
</v-app>
</template>

<script>
import LeftSideBar from './components/LeftSideBar.vue';
import RightSideBar from './components/RightSideBar.vue';
import MonthlyPinned from './components/MonthlyPinned.vue'
import TodayPlan from './components/TodayPlan.vue'
export default {
    name: 'App',

    components: {
        LeftSideBar,
        TodayPlan,
        MonthlyPinned,
        RightSideBar,

    },

    data: () => ({
        //
    }),
};
</script>
