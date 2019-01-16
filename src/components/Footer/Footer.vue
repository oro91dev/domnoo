<template>
    <footer>
        <div class="container">
            <div>
                <img :src="logoIcon"/>
                <div class="contact">
                    <div>Ring oss</div>
                    <div>22 22 55 55</div>
                </div>
            </div>
        </div>
    </footer>
</template>

<script>
    import Logo from '../../assets/images/dlogo.png';

    export default {
        data(){
            return {
                logoIcon: Logo
            }
        }
    }
</script>