<template>
    <div id="container">
        <div id="head">
            <h2>Enter a GitHub Username</h2>
            <i class="fa fa-github fa-3x"></i>
        </div>
        <form id="form_control">
            <input type="text" name="" id="input" placeholder="Enter a GitHub username" required>
            <input type="submit" value="Check">
        </form>
    </div>
</template>
<script>
export default {
    name: "Input"
}
</script>
<style scoped>
#container{
    display: flex;
    justify-content: center;
    flex-direction: column;
    color: teal;
}
#head{
    display: flex;
    justify-content: space-around;
    align-items: center;
}
#form_control{
    display: flex;

}
#form_control input[type="text"]::placeholder{
    text-indent: 10px;
    color: white;
}
#form_control input[type="text"],
#form_control input[type="submit"]{
    flex: 10;
    /* width: 200px; */
    height: 50px;
    border-radius: 5px;
    border: none;
    outline: none;
    color: white;
    background: turquoise;
    text-indent: 10px;
}
#form_control input[type="submit"]{
    flex: 2;
    cursor: pointer;
    margin-left: 5px;
    background: rgb(12, 114, 114);
    
}
</style>>
    
