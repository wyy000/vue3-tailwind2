<template>
<svg :height="height" :width="width" viewBox="0 0 32 32" class="fill-current">
 <path d="M28,4H4A2,2,0,0,0,2,6V22a2,2,0,0,0,2,2h8v4H8v2H24V28H20V24h8a2,2,0,0,0,2-2V6A2,2,0,0,0,28,4ZM18,28H14V24h4Zm10-6H4V6H28Z"/></svg>
</template>
<script> 
export default
{ name:"IconScreen", 
 props:{ height: { type:  Number, default: 20, }, width: { type:  Number, default: 20, }, } 
}
</script>