<template>
    <NavBar />
    <CarouselCom />
    <div class="container-fluid">
        <div class="row">
            <div class="col-12 text-center p-5">
                <h3>Lorem ipsum dolor, sit amet consectetur adipisicing elit. Illo quaerat facere veniam nihil incidunt,
                </h3>
            </div>
            <!-- feature -->
            <div class="row text-center justify-content-evenly ">
                <div class="col-md-3  mt-5 ">
                    <h1><i class="bi bi-calendar-range-fill text-primary"></i></h1>
                    <h5>Build for developer</h5>
                    <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Fuga ut aspernatur delectus nihil!
                        Velit, non!</p>
                </div>
                <div class="col-md-3 mt-5">
                    <h1><i class="bi bi-file-code-fill text-danger"></i></h1>
                    <h5>Build for developer</h5>
                    <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Fuga ut aspernatur delectus nihil!
                        Velit, non!</p>
                </div>
                <div class="col-md-3 mt-5">
                    <h1><i class="bi bi-easel-fill text-info"></i></h1>
                    <h5>Build for developer</h5>
                    <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Fuga ut aspernatur delectus nihil!
                        Velit, non!</p>
                </div>
            </div>
        </div>
        <hr>

        <!-- growth -->

        <div class="row mt-2 justify-content-evenly">
            <div class="col-md-5">
                <img src="@/assets/business.jpg" alt="Business img" class="img-fluid">
            </div>
            <div class="col-md-5 d-flex flex-column justify-content-center">

                <div>
                    <h6>Web-Development</h6>
                    <div class="progress mb-3" role="progressbar" aria-label="Success example" aria-valuenow="25"
                        aria-valuemin="0" aria-valuemax="100">
                        <div class="progress-bar bg-success" style="width: 25%"></div>
                    </div>
                </div>
                <div>
                    <h6>App-Development</h6>
                    <div class="progress mb-3" role="progressbar" aria-label="Warning example" aria-valuenow="75"
                        aria-valuemin="0" aria-valuemax="100">
                        <div class="progress-bar bg-warning" style="width: 75%"></div>
                    </div>
                </div>

                <div>
                    <h6>SEO</h6>
                    <div class="progress mb-3" role="progressbar" aria-label="Info example" aria-valuenow="50"
                        aria-valuemin="0" aria-valuemax="100">
                        <div class="progress-bar bg-info" style="width: 50%"></div>
                    </div>
                </div>

                <div>
                    <h6>Markiting</h6>
                    <div class="progress mb-3" role="progressbar" aria-label="Danger example" aria-valuenow="100"
                        aria-valuemin="0" aria-valuemax="100">
                        <div class="progress-bar bg-danger" style="width: 100%"></div>
                    </div>
                </div>

            </div>
        </div>

        <div class="row justify-content-evenly " style="background-color: #f1f1f1;">
            <div class="col-md-5 mt-4">
                <h3 class="mb-4">Contact Form</h3>
                <form>
                    <div class="mb-3">
                        <label for="exampleInputName" class="form-label">Full Name</label>
                        <input type="email" class="form-control" id="exampleInputName" aria-describedby="emailHelp">
                        <div id="emailHelp" class="form-text">We'll never share your email with anyone else.</div>
                    </div>
                    <div class="mb-3">
                        <label for="exampleInputEmail1" class="form-label">Email address</label>
                        <input type="email" class="form-control" id="exampleInputEmail1" aria-describedby="emailHelp">
                        <div id="emailHelp" class="form-text">We'll never share your email with anyone else.</div>
                    </div>
                    <div class="mb-3">
                        <label for="exampleFormControlTextarea1" class="form-label">Message</label>
                        <textarea class="form-control" id="exampleFormControlTextarea1" rows="3"></textarea>
                    </div>
                    <button type="submit" class="btn btn-danger">Submit</button>
                </form>
            </div>
            <div class="col-md-5 mt-4">
                <h3 class="mb-4">Address</h3>
                <p>1180 Kimbely Way,WILLISTON PARK<br>
                    New York - 115689 <br>
                    <i class="bi bi-telephone"></i>:917-772-5081
                </p>
                <iframe
                    src="https://www.google.com/maps/embed?pb=!1m18!1m12!1m3!1d6044.901803231697!2d-74.00005306227389!3d40.75210646581324!2m3!1f0!2f0!3f0!3m2!1i1024!2i768!4f13.1!3m3!1m2!1s0x89c25957145c04bf%3A0xbcb504b55063de86!2sMoynihan%20Train%20Hall%20at%20Penn%20Station!5e0!3m2!1sen!2s!4v1715771500788!5m2!1sen!2s"
                    style="width:100%;" height="300" allowfullscreen="" loading="lazy"
                    referrerpolicy="no-referrer-when-downgrade" class="mb-3"></iframe>
            </div>
        </div>

        <!-- faq -->
        <div class="row justify-content-evenly pt-5 pb-5">
            <div class="col-10">
                <h3 class="text-center pb-4">FAQ</h3>
                <div class="accordion" id="accordionExample">
                    <div class="accordion-item">
                        <h2 class="accordion-header">
                            <button class="accordion-button" type="button" data-bs-toggle="collapse"
                                data-bs-target="#collapseOne" aria-expanded="true" aria-controls="collapseOne">
                                Accordion Item #1
                            </button>
                        </h2>
                        <div id="collapseOne" class="accordion-collapse collapse show"
                            data-bs-parent="#accordionExample">
                            <div class="accordion-body">
                                <strong>This is the first item's accordion body.</strong> It is shown by default, until
                                the collapse plugin adds the appropriate classes that we use to style each element.
                                These classes control the overall appearance, as well as the showing and hiding via CSS
                                transitions. You can modify any of this with custom CSS or overriding our default
                                variables. It's also worth noting that just about any HTML can go within the
                                <code>.accordion-body</code>, though the transition does limit overflow.
                            </div>
                        </div>
                    </div>
                    <div class="accordion-item">
                        <h2 class="accordion-header">
                            <button class="accordion-button collapsed" type="button" data-bs-toggle="collapse"
                                data-bs-target="#collapseTwo" aria-expanded="false" aria-controls="collapseTwo">
                                Accordion Item #2
                            </button>
                        </h2>
                        <div id="collapseTwo" class="accordion-collapse collapse" data-bs-parent="#accordionExample">
                            <div class="accordion-body">
                                <strong>This is the second item's accordion body.</strong> It is hidden by default,
                                until the collapse plugin adds the appropriate classes that we use to style each
                                element. These classes control the overall appearance, as well as the showing and hiding
                                via CSS transitions. You can modify any of this with custom CSS or overriding our
                                default variables. It's also worth noting that just about any HTML can go within the
                                <code>.accordion-body</code>, though the transition does limit overflow.
                            </div>
                        </div>
                    </div>
                    <div class="accordion-item">
                        <h2 class="accordion-header">
                            <button class="accordion-button collapsed" type="button" data-bs-toggle="collapse"
                                data-bs-target="#collapseThree" aria-expanded="false" aria-controls="collapseThree">
                                Accordion Item #3
                            </button>
                        </h2>
                        <div id="collapseThree" class="accordion-collapse collapse" data-bs-parent="#accordionExample">
                            <div class="accordion-body">
                                <strong>This is the third item's accordion body.</strong> It is hidden by default, until
                                the collapse plugin adds the appropriate classes that we use to style each element.
                                These classes control the overall appearance, as well as the showing and hiding via CSS
                                transitions. You can modify any of this with custom CSS or overriding our default
                                variables. It's also worth noting that just about any HTML can go within the
                                <code>.accordion-body</code>, though the transition does limit overflow.
                            </div>
                        </div>
                    </div>
                </div>
            </div>
        </div>

        <!-- footer -->
        <div class="row justify-content-evenly bg-dark text-white pt-4 pb-4">
            <div class="col-md-3">
                <h3 class="pb-3">Foody Moody</h3>
                <p>Lorem ipsum dolor sit, amet consectetur adipisicing elit. Autem neque, explicabo tempora sequi omnis ipsam vero delectus adipisci molestias dolore Lorem ipsum dolor sit amet consectetur adipisicing elit. Reiciendis, veritatis.

                </p>
            </div>
            <div class="col-md-3">
                <h3 class="pb-3">Important Links</h3>
                <ul >
                    <li ><a class="text-decoration-none text-white" href="#">Home</a></li>
                    <li ><a class="text-decoration-none text-white" href="#">About Us</a></li>
                    <li ><a class="text-decoration-none text-white" href="#">Contact Us</a></li>
                    <li ><a class="text-decoration-none text-white" href="#">Our Team</a></li>
                    <li ><a class="text-decoration-none text-white" href="#">Our Client</a></li>

                </ul>

            </div>
            <div class="col-md-3">
                <h3 class="pb-3">Contact Us</h3>
                <p>1180 Kimbely Way,WILLISTON PARK<br>
                    New York - 115689 <br>
                    <i class="bi bi-telephone"></i>:917-772-5081
                </p>
            </div>
        </div>
        <div class="row justify-content-center text-center pt-2 pb-2 bg-secondary text-white">
            <div class="col-10">Copyright 1999-2024 by TechGun. All Right Reserved</div>
        </div>
    </div>
</template>

<!-- script section -->
<script>
import NavBar from "./NavBar.vue";
import CarouselCom from "./Carousel.vue";

export default {
    name: "HomeCom",
    components: {
        NavBar,
        CarouselCom,
    },
}
</script>

<!-- style section -->
<style></style>