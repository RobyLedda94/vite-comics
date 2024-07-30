<script>
import { headerMenu } from '../data/menu'
export default {
    data() {
        return {
            headerMenu
        }
    },
}
</script>
<template lang="">
    <header>
        <div class='container'>
            <div class='row'>
                <div class='col-12'>
                    <div class='content-header d-flex justify-content-between align-items-center py-3'>
                        <div class='logo'>
                            <img src='../assets/img/dc-logo.png' />
                        </div>
                        <div class='navigazione'>
                            <ul class='d-flex list-unstyled'>
                                <li v-for="lista, index in headerMenu" :key="index" :class="lista.current ? 'active' : ''">{{lista.label}}</li>
                            </ul>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </header>
</template>

<style lang="scss" scoped>
    ul {
        li{
            padding: 30px 20px;
            font-size: 13px;
            font-weight: bold;
            color: rgb(133, 133, 133);
    

            &:hover {
                color: #387cec;
                border-bottom: 2px solid #387cec;
                cursor: pointer;
            }
        }
    }

    .active{
        color: #387cec;
        border-bottom: 2px solid #387cec;
    }
</style>

<!-- props -->