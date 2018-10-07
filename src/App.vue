<template>
    <div id="root">
        <div id="content-wrapper">
            <main id="content">
                <section id="section1">
                    <nav id="navigation">
                    </nav>
                    <div id="page-wrapper">
                        <div id="news-left">
                            <div class="header-news">новые сериалы</div>
                            <div class="serial"></div>
                            <div class="link-news">
                                <a>все новые сериалы</a>
                            </div>
                        </div>
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
        margin-right: 5px;
    }

        .header-news {
            width: 100%;
            font-weight: bold;
            font-size: 12px;
            padding-left: 10px;
            background-color: #F1F1F1;
            margin-bottom: 10px;
            border-bottom: 1px solid #D3D3D4;
            text-transform: uppercase;
            line-height: 42px;
            box-sizing: border-box;
        }

        .serial {
            height: 60px;
        }

        .link-news {
            background-color: #fff;
            padding: 20px 0 30px 0;
            font-size: 9px;
            text-transform: uppercase;
        }
            .link-news a {
                padding: 0 10px 0 20px;
            }


    #main-page {
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
