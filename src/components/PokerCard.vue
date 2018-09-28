<template>
    <div class="poker-card">
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
        }
    }
</script>