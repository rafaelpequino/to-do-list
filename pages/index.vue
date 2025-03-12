<template>
    <main id="container">
        <section>
            <div class="add-task">
                <h3>Adicionar tarefa</h3>
                <input type="text" placeholder="Digite a tarefa" id="inputTask" />
            </div>
            
            <div class="list list-pending">
                <div class="task">
                    <p>Fazer curso de vue</p>
                </div>
            </div>
            
            <div class="list list-check">
                <div class="task">
                    <p>Fazer curso de vue</p>
                </div>
            </div>
        </section>
    </main>
</template>

<style lang="css">

* {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
    color: #fff;
    text-align: center;
    font-family: sans-serif;
}

#container {
    width: 100%;
    min-height: 100vh;
    background-color: #172237;
    display: flex;
    align-items: center;
    justify-content: center;
}

.add-task {
    width: 100vw;
    max-width: 500px;
    padding: 30px;
}

#inputTask {
    display: block;
    width: 100%;
}

</style>