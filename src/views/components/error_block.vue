<style>
#error-block {
    background-color: #f23a3a;
    color: white;
    text-align: center;
    border-radius: 10px;
    padding-top: 15px;
    padding-bottom: 15px;
    margin-top: 5px;
}
</style>

<template>

<div id="error-block">
    <p>Error: {{error_message}}</p>
</div>

</template>

<script>
export default {
    name: "ErrorBlock",
    props: ["error_message"]
};
</script>
