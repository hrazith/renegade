<template>
    <ul>
        <li v-for="distribution in distributions" >
            <span :class="distribution.type" v-on:click="reverseMessage">{{ distribution.name }}</span>
            <ul>
                <li v-for="child in distribution.children" :class="child.type"> {{ child.name }} </li>
            </ul>

        </li>
    </ul>
</template>
<script>
    export default {
        name: 'DistributionTree',
        props: ['distributions'],
        methods: {
            reverseMessage: function () {
                alert(this.distributions.length);
            }
        }
    }
</script>
