<template>
    <div class="log-form">
        <form action="#" class="eiei-form">

            <div class="item">
                <label for="username">Username</label> &nbsp;
                <input type="text" placeholder="input UserName">
            </div>

            <div class="item">
                <label for="password">Password</label> &nbsp;
                <input type="password" placeholder="input Password">
            </div>
            
            <button type="submit">login</button>
        </form>
    </div>
    
</template>
<script>
export default {
    
}
</script>
<style scoped>

.log-form{
    width: 500px;
    background-color: antiquewhite;padding: 15px;
    border-radius: 20px;
    left: 30%;
    position:relative;
}

.eiei-form{
    padding: 15px;
    
}

    
</style>