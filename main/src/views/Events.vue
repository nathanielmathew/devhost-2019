<template>
<div class="Events">
    <h1 id="head">Events</h1><h1 id="colon">:</h1><br /><br />
    <div class ="DayHead">
        <h2 class="Day">Day</h2><h2 class="number"> 1</h2>
    </div>
        <p class="Day1">Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua.
         Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat.
         quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat.</p>
    <div class ="DayHead">
        <h2 class="Day">Day</h2><h2 class="number"> 2</h2>
    </div>
        <p class="Day2">Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua.
         Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat.
         quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat.</p>
    <div class ="DayHead">
        <h2 class="Day">Day</h2><h2 class="number"> 3</h2>
    </div>
        <p class="Day3">Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua.
         Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat.
         quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat.</p>
</div>
</template>
<script>
export default{
    
}
</script>
<style>
#head{
    font-size: 40px;
}
.DayHead{
    text-align: center;
}
.Events{
    background: transparent;
}
.number{
    color: #50fd51;
    font-family: monospace;
    font-size: 40px;
}
#colon{
    color: #50fd51;
    font-size: 40px;
}
#head,#colon
{
    display:inline;
}
.Day,.number
{
    display:inline;
}
</style>