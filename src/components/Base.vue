<template>
    <div>
        <!-- navbar -->
        <b-navbar toggleable="lg" type="light fixed" variant="">
            <b-navbar-brand href="#">
                <img src="@/assets/logo.svg" height="40">
            </b-navbar-brand>
            <b-navbar-toggle target="nav-collapse"></b-navbar-toggle>
            <b-collapse id="nav-collapse" is-nav>
                <b-navbar-nav>
                    <b-nav-item href="#">Features</b-nav-item>
                    <b-nav-item href="#">Pricing</b-nav-item>
                    <b-nav-item href="#">Resources</b-nav-item>
                </b-navbar-nav>
                <b-navbar-nav class="ml-auto">
                    <b-nav-item href="#">Login</b-nav-item>
                    <b-nav-item href="#">
                        <b-button pill variant="primary">Sign up</b-button>
                    </b-nav-item>
                </b-navbar-nav>
            </b-collapse>
        </b-navbar>

        <!-- images -->
        <div class="container">
            <div class="row">
                <div class="col">
                   <img src="@/assets/illustration-working.svg" fluid>
                </div>
                <div class="col">
                   <h1 class="text-center font-weight-bold"><b>More than just shorter links</b></h1>
                   <p class="text-center">Build your brand's recognition and get detailed insights on how your links are performing</p>
                   <div class="row justify-content-center">
                      <b-button pill variant="primary">Get started</b-button>
                   </div>
                </div>
            </div>
        </div>

        <br/>

        <!-- card section for url shortener-->
        <div class="container">
            <div class="card p-2" style="background-color: hsl(257, 27%, 26%)">
                <img src="@/assets/bg-shorten-mobile.svg">
                <div class="card-img-overlay">
                    <form>
                        <div class="form-group">
                            <input type="text" class="form-control mb-2" placeholder="shorten a link here...">
                            <small class="form-text text-muted">please add a link</small>
                        </div>
                        <button class="btn btn-primary btn-block">shorten it!</button>
                    </form>
                </div>
            </div>
        </div>

        <br/>

        <!-- more links -->
        <div class="image-container" style="background-color: hsl(257, 27%, 26%)">
            <img src="@/assets/bg-boost-mobile.svg">
            <div class="centered">
                Boost your links today
                <br/>
                <br/>
                <b-row>
                    <b-col lg="4" class="pb-2">
                        <b-button size="lg" pill variant="primary">Get started</b-button>
                    </b-col>
                </b-row>
            </div>

            <!-- footer section -->
            <footer class="page-footer font-small pt-4">
                <div class="container text-center text-md-left" style="background-color: hsl(255, 11%, 22%)">
                    <div class="row">
                        <div class="col-md-6 mt-md-0 mt-3">
                            <h1 class="text-white" style="font-weight: bold; font-size: 3em">Shortly</h1>
                        </div>
                        <div class="col-md-3 mb-md-0 mb-3">
                            <h5 class="text-white">Features</h5>
                            <ul class="list-unstyled">
                                <li>
                                    <a href="#" style="color: #bdbdbd; font-weight: 700">Links Shortening</a>
                                </li>
                                <li>
                                    <a href="#" style="color: #bdbdbd; font-weight: 700">Branded Links</a>
                                </li>
                                <li>
                                    <a href="#" style="color: #bdbdbd; font-weight: 700">Analytics</a>
                                </li>
                            </ul>
                        </div>

                        <div class="col-md-3 mb-md-0 mb-3">
                            <h5 class="text-white">Resources</h5>
                            <ul class="list-unstyled">
                                <li>
                                    <a href="#" style="color: #bdbdbd; font-weight: 700">Blog</a>
                                </li>
                                <li>
                                    <a href="#" style="color: #bdbdbd; font-weight: 700">Developers</a>
                                </li>
                                <li>
                                    <a href="#" style="color: #bdbdbd; font-weight: 700">Support</a>
                                </li>
                            </ul>
                        </div>

                        <div class="col-md-3 mb-md-0 mb-3">
                            <h5 class="text-white">Company</h5>
                            <ul class="list-unstyled">
                                <li>
                                    <a href="#" style="color: #bdbdbd; font-weight: 700">About</a>
                                </li>
                                <li>
                                    <a href="#" style="color: #bdbdbd; font-weight: 700">Our Team</a>
                                </li>
                                <li>
                                    <a href="#" style="color: #bdbdbd; font-weight: 700">Careers</a>
                                </li>
                                <li>
                                    <a href="#" style="color: #bdbdbd; font-weight: 700">Contact</a>
                                </li>
                            </ul>
                        </div>
                    </div>
                </div>
            </footer>
        </div>
    </div>
</template>

<style scoped>
.image-container {
    position: relative;
    text-align: center;
    color: white;
    font-weight: bold;
    display: block;
    font-size: 1em;
}

.centered {
    position: absolute;
    top: 20%;
    left: 50%;
    transform: translate(-50%, -50%);
}
</style>
