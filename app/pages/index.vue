<template>
    <v-container fluid>
        <v-row>
            <v-col cols="12">
                <v-row
                    align="center"
                    justify="center"
                    :style="{
                        height: '100%'
                    }"
                >
                    <v-card
                        max-width="400"
                    >
                        <v-img
                            class="white--text align-end"
                            height="200px"
                            src="https://cdn.vuetifyjs.com/images/cards/docks.jpg"
                        >
                            <v-card-title>Robert Groot</v-card-title>
                        </v-img>

                        <v-card-text class="text--primary">
                            <div>Full-stack developer</div>
                            <div>Working mainly with a Laravel + VueJS (Typescript) + MySQL + Redis stack.</div>
                        </v-card-text>

                        <v-card-actions>
                            <v-btn
                                text
                                icon
                                href="https://www.linkedin.com/in/robert-groot/"
                            >
                                <v-icon>$mdiAccount</v-icon>
                            </v-btn>

                            <v-btn
                                text
                                icon
                                href="mailto:info+website@rgroot.nl"
                            >
                                <v-icon>$mdiEmail</v-icon>
                            </v-btn>

                            <v-btn
                                text
                                icon
                                href="https://github.com/IAmRGroot"
                            >
                                <v-icon>$mdiGithub</v-icon>
                            </v-btn>
                        </v-card-actions>
                    </v-card>
                </v-row>
            </v-col>
        </v-row>
    </v-container>
</template>

<style lang="scss">
    @import '../node_modules/typeface-roboto/index.css';
</style>
