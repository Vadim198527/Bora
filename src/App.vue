<template>
    <div id="root">
        <div id="content-wrapper">
            <main id="content">
                <section id="section1">
                    <nav id="navigation">
                    </nav>
                    <div id="page-wrapper">
                        <div id="news-left"></div>
                        <div id="main-page"></div>
                    </div>
                </section>
                <section id="section2">
                    <div id="user-panel">

                    </div>

                    <div id="ad">
                    </div>

                    <div id="news-right">
                        <header id="header-news"></header>
                    </div>
                </section>
            </main>
        </div>
    </div>
</template>

<script>

	export default {
		name: 'app',
		components: {
		}
	}
</script>

<style scoped>

    #root {
        background-color: gray;
        margin: -8px;
        width: 100%;
        padding-top: 300px;
    }

    #content-wrapper {
        display: flex;
        justify-content: center;
    }

    #content {
        display: flex;
        height: 700px;
        min-width: 960px;
    }

    #page-wrapper {
        display: flex;
        margin-top: 5px;
    }

    #section1 {
        width: 710px;
    }

    #navigation {
        width: 710px;
        height: 30px;
        background-color: aquamarine;
    }

    #news-left {
        width: 240px;
        background-color: aquamarine;
        height: 700px;
        margin-right: 5px;
    }

    #main-page {
        height: 700px;
        width: 470px;
        background-color: aquamarine;
    }

    #section2 {
        width: 240px;
        /*background-color: aquamarine;*/
        margin-left: 5px;
        margin-top: 35px;
    }

        #user-panel {
            width: 100%;
            height: 70px;
            margin-bottom: 5px;
            background-color: darkorchid;
        }

        #ad {
            width: 100%;
            height: 400px;
            border: 1px solid red;
            background-color: darkorchid;
        }

        #news-right {
            width: 100%;
            height: 500px;
            border: 1px solid red;
            background-color: darkorchid;
        }

            #header-news {
                width: 100%;
                height: 43px;
                border: 1px solid red;
                background-color: darkorchid;
            }


</style>
