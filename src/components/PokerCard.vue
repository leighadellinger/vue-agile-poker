<template>
    <div class="poker-card" @click="onSelectCard" v-bind:class="{selected:selected}">
        <p class="card-text">
            {{ value }}
        </p>
    </div>
</template>

<script>
    export default {
        name: 'PokerCard',
        props: {
            value: String
        },
        data() {
            return {
                selected: false
            }
        },
        methods: {
            onSelectCard () {
                this.selected = !this.selected
            }
        }
    }
</script>