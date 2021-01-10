<template>
    <div class="game">
        <h1>Game 2048 will be here</h1>

        <section class="game__section">
            <div class="game__row">
                <div class="game__ceil">2</div>
                <div class="game__ceil">4</div>
                <div class="game__ceil">8</div>
                <div class="game__ceil">16</div>
            </div>
            <div class="game__row">
                <div class="game__ceil"></div>
                <div class="game__ceil"></div>
                <div class="game__ceil"></div>
                <div class="game__ceil"></div>
            </div>
            <div class="game__row">
                <div class="game__ceil"></div>
                <div class="game__ceil"></div>
                <div class="game__ceil"></div>
                <div class="game__ceil"></div>
            </div>
            <div class="game__row">
                <div class="game__ceil"></div>
                <div class="game__ceil"></div>
                <div class="game__ceil"></div>
                <div class="game__ceil"></div>
            </div>

        </section>
    </div>
</template>

<style lang="scss">
    .game{
        margin: 0 auto;
        &__section{
            padding: 15px;
            background-color: #BBADA0;
            display: grid;
            grid-gap: 15px;
            grid-template-rows: 1fr 1fr 1fr 1fr;
        }

        &__row{
            display: grid;
            grid-gap: 15px;
            grid-template-columns: 1fr 1fr 1fr 1fr;
        }

        &__ceil{
            width: 100px;
            height: 100px;
            background-color: #CDC1B4;
            display: grid;
            align-items: center;

            color: #776E65;
            text-align: center;
            font-weight: 700;
            z-index: 10;
            font-size: 55px;

            &:not(:empty){
                background-color: #EEE4DA;
            }
        }
    }

</style>