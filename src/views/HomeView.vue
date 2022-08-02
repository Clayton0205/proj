<template>
    <div id="page">
        <div class="container">
            <div class="row">
                <img src="../assets/PNP.jpg" id="logo">
            </div>
            <div class="row">
                <h1>“Inspired by you”</h1>
            </div>
        </div>
    </div>
    <footer id="footer">
        <p>color: rgb(182, 13, 74);</p>
    </footer>
</template>

<style scoped>
* {
    margin: 0;
    padding: 0;
}

#page {
    width: 100%;
    height: 728px;
    display: flex;
    justify-content: center;
    background-image: linear-gradient(to right, rgb(5, 52, 93), rgb(182, 13, 74));
    font-family: Lucida Console;
}

#logo {
    margin: auto;
    width: 800px;
    height: 500px;
}

.row {
    text-align: center;
    color: white;
}

#footer {
    background-image: linear-gradient(to right, rgb(5, 52, 93), rgb(182, 13, 74));
    color: white;
    text-align: center;
    font-family: Lucida Console;
}
</style>