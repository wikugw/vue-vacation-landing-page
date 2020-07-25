<template>
    <div class="container-fluid m-0 p-0">

        <div id="home-page" class="full-height bg-danger p-4">
            <div class="container pt-3">

                <div class="row pb-5">

                    <div class="col-lg-6 pt-4 my-auto">

                        <div class="text-center mb-3 d-block d-lg-none">

                            <h1 class="display-3"> {{title}} </h1>

                            <h3>Find The World</h3>

                        </div>

                        <img id="iphone-img"
                            src="../assets/travelTreasuryiPhone.png"
                            alt="">

                    </div>

                    <div class="col-lg-6 my-auto pt-4">

                        <div class="text-center mb-3 d-none d-lg-block">

                            <h1 class="display-3"> {{title}} </h1>

                            <h3>Find The World</h3>

                        </div>

                        <div class="border p-3 p-md-5 bg-white shadow bordered">

                            <h2>Coming Soon</h2>

                            <form action="">

                                <div class="form-group">

                                    <label for="emailSignUp">
                                        Reserve your account NOW! and we'll get you in touch when it's ready to BOOM!!
                                    </label>

                                    <input  id="emailSignUp"
                                            type="text"
                                            placeholder="something with @ ... and maybe .com ??"
                                            class="form-control"
                                    >

                                    <small  id="emailHelp"
                                            class="form-text text-muted"
                                    >
                                        we won't do anything bad with your email ✌✌✌
                                    </small>

                                    <button class="btn btn-success mt-3"
                                            type="submit"
                                    >
                                        I'M IN!!
                                    </button>

                                </div>

                            </form>

                        </div>

                        <div id="available" class="p-2">

                            <h4 class="text-center mb-2 mt-3 text-light">
                                (Not Yet) Available On
                            </h4>

                            <div class="row">

                                <div class="col my-auto">

                                    <img src="../assets/download_apple.png"
                                         class="float_right img_fluid app_store_img">

                                </div>

                                <div class="col my-auto">

                                    <img src="../assets/download_google.png"
                                         class="float_left img_fluid app_store_img">

                                </div>

                            </div>

                        </div>

                    </div>

                </div>

            </div>
        </div>

        <div id="about" class="bg-light p-3 p-md-5">

            <div class="row">

                <div class="col-lg">

                    <!-- Icon made by freepik perfect from www.flaticon.com -->
                    <img src="../assets/icons/app.svg"
                        class="m-4"
                        height="120"
                    >

                    <h5 class="ml-md-4 mr-md-4">
                        Lorem ipsum dolor sit amet consectetur adipisicing elit.
                        Molestias, quis! Quam magnam nisi veniam consequuntur aut nulla!
                        Consequuntur ab accusamus, natus amet, eos at beatae, facere
                        incidunt quod recusandae quo perferendis quis necessitatibus
                        dolorum temporibus animi perspiciatis soluta ipsa.
                    </h5>

                </div>

                <div class="col-lg">

                    <!-- Icon made by freepik perfect from www.flaticon.com -->
                    <img src="../assets/icons/piggy-bank.svg"
                        class="m-4"
                        height="120"
                    >

                    <h5 class="ml-md-4 mr-md-4">
                        Lorem ipsum dolor sit amet consectetur adipisicing elit.
                        Molestias, quis! Quam magnam nisi veniam consequuntur aut nulla!
                        Consequuntur ab accusamus, natus amet, eos at beatae, facere
                        incidunt quod recusandae quo perferendis quis necessitatibus
                        dolorum temporibus animi perspiciatis soluta ipsa.
                    </h5>

                </div>

                <div class="col-lg">

                    <!-- Icon made by freepik perfect from www.flaticon.com -->
                    <img src="../assets/icons/passport.svg"
                        class="m-4"
                        height="120"
                    >

                    <h5 class="ml-md-4 mr-md-4">
                        Lorem ipsum dolor sit amet consectetur adipisicing elit.
                        Molestias, quis! Quam magnam nisi veniam consequuntur aut nulla!
                        Consequuntur ab accusamus, natus amet, eos at beatae, facere
                        incidunt quod recusandae quo perferendis quis necessitatibus
                        dolorum temporibus animi perspiciatis soluta ipsa.
                    </h5>

                </div>

            </div>

        </div>


        <div id="contact" class="p-4">

            <div class="row justify-content-center mt-3 mb-3">

                <div class="col-lg-4">

                    <h2>Any Qustions??</h2>

                    <p>👇👇 Contact us by filling the form below! 👇👇</p>

                    <form >
                        <div class="form-group text-left">

                            <input type="email"
                               class="form-control"
                               placeholder="this will be your email address"
                            >

                            <textarea rows="5"
                                    class="form-control mt-3"
                                    placeholder="ask whatever you want.."
                            >

                            </textarea>

                        </div>

                        <button type="submit"
                                class="btn btn-primary"
                        >
                            Send Message
                        </button>

                    </form>

                </div>

            </div>

        </div>


        <div id="footer" class="p-4">

            <footer class="text-light p-4">

                <a href=""
                   target="_blank"
                   class="text-warning"
                >
                    Build this App
                </a>

                |

                <a href=""
                   class="text-warning"
                >
                    Privacy Policy
                </a>

                <br>

                <small>
                    &copy; 2020, Vacationnn.app
                </small>

            </footer>

        </div>
    </div>
</template>

<script>
export default {
    header () {
        return {
            title: 'Travel'
        }
    },
    data () {
        return {
            title: 'Travel'
        }
    }
}
</script>

<style scoped>
    #home-page {
        background-color: #92d2f2;
        background: url('../assets/island-3542290_1920.jpg') no-repeat center center;
        -webkit-background-size: cover;
        -moz-backgroud-size: cover;
        -o-background-siza: cover;
        background-size: cover;
    }

    #iphone-img {
        max-height: 80vh;
    }

    #about {
        min-height: 40vh;
    }

    #contact {
        background-color: #57AEAF;
    }

    #footer {
        background-color: #252223;
    }

    #home-page h1,
    #home-page h3 {
        color: white;
    }

    .app_store_img {
        max-height: 80px;
        max-width: 100%;
    }
</style>