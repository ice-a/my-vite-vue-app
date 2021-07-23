<template>
    <input type="" placeholder='world'/>
</template>

<script>
import { defineComponent, ref} from '@vue/composition-api'

export default defineComponent({
    setup() {
        const world = ref('111')
        return {
            world
        }
    },
})
</script>
