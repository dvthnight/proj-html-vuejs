<template>
    <div class="quadratini">
        <div class="demos">
            <i class="fa-regular fa-window-restore"></i>
            <h5>Demos</h5>
        </div>
        <div class="sale">
            <i class="fa-solid fa-cart-shopping"></i>
            <h5>On sale</h5>
        </div>
    </div>
</template>

<script>
export default {
    
}
</script>

<style lang="scss" scoped>
    .quadratini{
        color: rgb(51, 71, 91);
        position: fixed;
        right: 20px;
        top: 10%;
        z-index: 99999;
        
        
        .demos, .sale{
            padding: 10px;
            background-color: white;
            border-radius: 5px;
            margin-bottom: 10px;
            display: flex;
            flex-direction: column;
            justify-content: center;
            align-items: center;
            gap: 5px;
            aspect-ratio: 1;
            box-shadow: 3px 2px 6px #78787a;

        }

    }
</style>