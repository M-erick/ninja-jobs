<template>
    <div>
        
 
    </div>
</template>
<script>
export default {
    name :'Home',
    setup() {
        let name = 'erick'
        let age = 30
        const handleClick = () => {
            console.log('you clicked me')
        }
        const p = ref(null)


        return{name,age,handleClick}
        
    }
   
    
}
</script>
<style >
    
</style>