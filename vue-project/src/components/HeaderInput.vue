<template>
    <section id="login-area">
        <div id="user-area" class="input-group mb-1">
            <span class="input-group-text" id="user-id">Usuário</span>
            <input type="text" class="form-control" aria-describedby="user-id">
        </div>

        <div id="pswd-area" class="input-group mb-1">
            <span class="input-group-text" id="pswd-id">Senha</span>
            <input type="password" class="form-control" aria-describedby="pswd-id">
        </div>
    </section>
</template>

<style scoped>
#login-area {
    width: 30%;
    display: flex;
    justify-content: flex-end;
    align-items: center;
}

#pswd-id {
    margin-left: 10px;
}
</style>