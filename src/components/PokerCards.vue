<template>
    <b-container class="poker-card-holder">
        <h1>{{ msg }}</h1>

        <b-row>
            <b-col>
                <PokerCard value="1" />
            </b-col>
            <b-col>
                <PokerCard value="2" />
            </b-col>
            <b-col>
                <PokerCard value="3" />
            </b-col>
        </b-row>

        <b-row>
            <b-col>
                <PokerCard value="5" />
            </b-col>
            <b-col>
                <PokerCard value="8" />
            </b-col>
            <b-col>
                <PokerCard value="13" />
            </b-col>
        </b-row>

    </b-container>
</template>

<script>

    import PokerCard from "./PokerCard";
    export default {
        name: 'PokerCards',
        components: {PokerCard},
        props: {
            msg: String
        }
    }
</script>