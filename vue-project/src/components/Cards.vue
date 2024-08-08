<template>
    <section>
        <h1 class="display-3">Principais Frameworks Front-End</h1>
    </section>

    <section>
        <div class="framework">
            <h4 class="display-6">MaterializeCSS</h4>
            <button class="btn btn-primary">Saiba mais</button>
        </div>
        <div class="framework">
            <h4 class="display-6">Bulma</h4>
            <button class="btn btn-secondary">Saiba mais</button>
        </div>
        <div class="framework">
            <h4 class="display-6">Tailwind CSS</h4>
            <button class="btn btn-success">Saiba mais</button>
        </div>
        <div class="framework">
            <h4 class="display-6">Bootstrap</h4>
            <button class="btn btn-danger">Saiba mais</button>
        </div>
        <div class="framework">
            <h4 class="display-6">Angular</h4>
            <button class="btn btn-warning">Saiba mais</button>
        </div>
        <div class="framework">
            <h4 class="display-6">Vue.js</h4>
            <button class="btn btn-info">Saiba mais</button>
        </div>
        <div class="framework">
            <h4 class="display-6">Ember</h4>
            <button class="btn btn-light">Saiba mais</button>
        </div>
        <div class="framework">
            <h4 class="display-6">Svelte</h4>
            <button class="btn btn-dark">Saiba mais</button>
        </div>
    </section>
</template>


<style scoped>
main section {
    padding: 30px 30px 15px;
    display: flex;
    justify-content: center;
    flex-wrap: wrap;
}

h1 {
    align-self: center;
}

.framework {
    width: 300px;
    margin: 10px;
    background-color: rgb(121, 63, 126);
    border-radius: 10px;
    display: flex;
    flex-direction: column;
}

h4 {
    color: white;
    align-self: center;
    padding: 20px 0px 50px;
}

button {
    max-width: 150px;
    align-self: center;
    margin-bottom: 20px;
}
</style>