<template>
    <div id="app">
        <b-container class="vh-100">
            <b-row class="bg-info">
                <b-col class="p-4">
                    <img alt="Флаг Российской Федерации" id="flag" class="pb-3"
                         src="./assets/images/flag.svg"/>
                    <h1><b>OpenRUS</b></h1>
                    <h2>Открытая система голосования граждан Российской Федерации</h2>
                </b-col>
            </b-row>
            <b-row class="bg-dark">
                <b-col class="p-4">
                    <p class="text-white">
                        <b>Мы занимаемся разработкой системы со следующими характеристиками:</b>
                    </p>
                    <b-list-group>
                        <b-list-group-item>
                            <h4>Доступ и идентификация</h4>
                            Система доступна всем пользователям интернета по номеру телефона,
                            зарегистрированного в Российской Федерации.
                        </b-list-group-item>
                        <b-list-group-item>
                            <h4>Источник опросов</h4>
                            Все опросы создаются пользователями системы.
                        </b-list-group-item>
                        <b-list-group-item>
                            <h4>Изменение данных</h4>
                            Система предоставляет возможность изменить своё решение по каждому вопросу.
                        </b-list-group-item>
                        <b-list-group-item>
                            <h4>Достоверность данных</h4>
                            Мы гарантируем достоверность данных путём децентрализации и использования технологии
                            Blockchain.
                        </b-list-group-item>
                        <b-list-group-item>
                            <h4>Открытость системы</h4>
                            Весь код системы является открытым и доступен всем желающим:
                            <br>
                            <a href="https://github.com/OpenRUS" target="_blank">https://github.com/OpenRUS</a>
                        </b-list-group-item>
                    </b-list-group>
                </b-col>
            </b-row>
            <b-row class="bg-secondary">
                <b-col class="p-4 text-white">
                    <p>Мы рады услышать Ваше мнение и заинтересованы в любого рода помощи и поддержке.</p>
                    <p>
                        Со всеми вопросами и предложениями пишите на
                        <a href="mailto:info@openrus.net">info@openrus.net</a>
                    </p>
                </b-col>
            </b-row>
        </b-container>
    </div>
</template>

<script>
    export default {
        name: 'App'
    }
</script>

<style lang="scss">
    @import './assets/styles/theme.scss';
    @import '../node_modules/bootstrap/scss/bootstrap.scss';

    body {
        background-color: $secondary;
    }

    #app {
        font-family: 'Montserrat', sans-serif;
        -webkit-font-smoothing: antialiased;
        -moz-osx-font-smoothing: grayscale;
        text-align: center;
    }

    #flag {
        height: 100px;
        box-sizing: content-box;
    }
</style>
