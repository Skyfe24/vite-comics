<script>
export default {
    data() {
        return {
            NavbarLinks: [
                {
                    text: 'Characters',
                    url: '#',
                    current: false,
                },
                {
                    text: 'Comics',
                    url: '#',
                    current: true,
                },
                {
                    text: 'Movies',
                    url: '#',
                    current: false,
                },
                {
                    text: 'TV',
                    url: '#',
                    current: false,
                },
                {
                    text: 'Games',
                    url: '#',
                    current: false,
                },
                {
                    text: 'Collectibles',
                    url: '#',
                    current: false,
                },
                {
                    text: 'Videos',
                    url: '#',
                    current: false,
                },
                {
                    text: 'Fans',
                    url: '#',
                    current: false,
                },
                {
                    text: 'News',
                    url: '#',
                    current: false,
                },
                {
                    text: 'Shop',
                    url: '#',
                    current: false,
                },
            ]

        }
    }
}
</script>

<template>
    <!-- header-->
    <header>
        <nav>
            <div class="container" id="navbar">
                <div class="logo"><a href><img src="../assets/img/dc-logo.png" alt="logo DC comics"></a> </div>

                <div class="links">
                    <ul> QUI
                        <li v.for="link in [NavbarLinks]" :key="link.text"> <a href="link.url"> {{ link.text }} </a></li>



                    </ul>





                </div>













            </div>











        </nav>
        <h1>ciao ciao belli 20000</h1>
    </header>
</template>


<style scoped>
.container {
    max-width: 1290px;
    margin: 0 auto;
}

h1 {
    color: rgb(6, 233, 157)
}
</style>s