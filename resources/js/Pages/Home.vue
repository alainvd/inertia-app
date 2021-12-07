<template>
    <h1> Hello superb {{ name }} with docker ! </h1>

    <div>Frameworks</div>
    <ol>
        <li v-for="framework of frameworks" v-text="framework"></li>
    </ol>

</template>


<script>
export default {

    props: {
        name: String,
        frameworks: Array
    }
};


</script>
