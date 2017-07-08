<template>
    <div id='app'>
        <h3>{{title}}</h3>
        <Character />
    </div>
</template>

<script>
import Character from './Component/Character.vue'

export default {
    name: 'app',
    data() {
        return {
            title: 'Generate Your Team'

        }
    },
    components: {
        Character
    }

}
</script>