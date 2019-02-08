<template>
    <ul>
        <li v-for="distribution in distributions">
            <div :class="distribution.type">{{ distribution.name }}
                <select>
                    <option value="volvo">Volvo</option>
                    <option value="saab">Saab</option>
                    <option value="mercedes">Mercedes</option>
                    <option value="audi">Audi</option>
                </select>
            </div>
                <ul>
                    <li v-for="child in distribution.children" :class="child.type"> {{ child.name }} </li>
                </ul>
        </li>
    </ul>
</template>
<script>
    export default {
        name: 'DistributionDetail',
        props: ['distributions']
    }
</script>
