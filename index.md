---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults

layout: default
slub:  home
---
<!--动画部分开始-->
<!--<div class="animation">-->

<div style="position: relative ;z-index:-10;">
    <video loop="loop" autoplay playsinline muted  class="video" style="overflow:hidden">
        <source type="video/mp4" src="https://demo3.academyofmine.com/wp-content/uploads/2017/08/Cherries-1.mp4" />
    </video>

<!--</div>-->
</div>
<!--动画结束-->

<!--列表开始-->
<div class="contentlist container-fluid">
    <!--列表标题-->
    <div class="Our_Courses">

            <h1 style="text-align: left;"><strong>Our Courses</strong></h1>
            <p style="text-align: left;">Choose from a selection of our awesome courses below</p>

    </div>
    <!--列表内容-->
    <div class="fenge"></div>
    <div class="contentHTML_content">
        <div class="Our_content">

            {% for post in site.posts limit:4 %}
            <div class="COntent_div">
                <div class="COntent_divcontainer">
                    <a href="#" class="COntent_divcontainer-url">
                        <img width="100%" src="{{post:image}}" class="COntent_divcontainer-image" alt="">
                    </a>
                </div>
                <h2 class="Our_content_title">
                    <a href="{{ post.url }}">
                        {{ post.title }}        </a>
                </h2>

                <div class="star-rating">

                    <span class="glyphicon glyphicon-star-empty strat" aria-hidden="true"></span>
                    <span class="glyphicon glyphicon-star-empty strat" aria-hidden="true"></span>
                    <span class="glyphicon glyphicon-star-empty strat" aria-hidden="true"></span>
                    <span class="glyphicon glyphicon-star-empty strat" aria-hidden="true"></span>
                    <span class="glyphicon glyphicon-star-empty  strat" aria-hidden="true"></span>
                    <span class="review-text">( 0 reviews )</span>
                </div>

                <hr class="divider">

                <div class="course-price">
                    FREE
                </div>

                <hr class="divider">

                <div class="course-instructor">
                    <div style="width:32px;height:32px;overflow:hidden;">
                        <img src="./images/quan.jpg" alt="author-img">
                    </div>

                    <p>
                        Tech Support        </p>
                </div>

            </div>
            {% endfor %}



        </div>
    </div>
</div>
<div class="fenge"></div>
<div class="fenge"></div>

<!--列表结束-->

<!--choose us 开始-->
<div class="container-fluid chooseus">
    <div class="fenge30"></div>
    <div class="choosetitle">
        <h1 style="text-align: center">
            <strong>Why Choose Us</strong>
        </h1>
    </div>
    <div class="fenge"></div>
    <div class="choosecontent">
        <div class="chooseus_content">
            <div class="chooseus_content_image">
                <img src="./images/pg3.jpg"  style="width:90px;height:89px" alt="">
            </div>
            <div class="chooseus_content_text">
                <h4 class="chooseus_content_text_title">Deep Industry Experience</h4>
                <div class="chooseus_content_text_content">
                    <p>We have more than 10 Years exprience in delivering quality learning on Cherry Farming</p>
                </div>
            </div>
        </div>

        <div class="chooseus_content">
            <div class="chooseus_content_image">
                <img src="./images/pg3.jpg"  style="width:90px;height:89px" alt="">
            </div>
            <div class="chooseus_content_text">
                <h4 class="chooseus_content_text_title">Deep Industry Experience</h4>
                <div class="chooseus_content_text_content">
                    <p>We have more than 10 Years exprience in delivering quality learning on Cherry Farming</p>
                </div>
            </div>
        </div>

        <div class="chooseus_content">
            <div class="chooseus_content_image">
                <img src="./images/pg3.jpg"  style="width:90px;height:89px" alt="">
            </div>
            <div class="chooseus_content_text">
                <h4 class="chooseus_content_text_title">Deep Industry Experience</h4>
                <div class="chooseus_content_text_content">
                    <p>We have more than 10 Years exprience in delivering quality learning on Cherry Farming</p>
                </div>
            </div>
        </div>

    </div>

</div>
<!--choose us 结束-->


<!--getstarted 开始-->
<div class="container-fluid getstarted">
    <div class="getstarted_center">
        <div class="getstarted_title">

            <h1 style="text-align: center;color: #fff;">Click below to view all our Course Offerings</h1>
        </div>

        <div class="getstarted_btn">
            <a class="getstarted_button" href="https://demo3.academyofmine.com/our-courses/">Get Started</a>
        </div>

    </div>

</div>
<!--getstarted 结束-->


<!--about us 开始-->
<div class="fenge30"></div>
<div class="container-fluid aboutus">
    <div class="aboutus_title">
        <div class="aboutus_title_text">
            <h1 style="text-align: center;"><strong>What Other Farmers Are Saying about us?</strong></h1>
        </div>
    </div>

    <div class="about_content">
        <div class="about_content_lists">
            <div class="about_content_list">
                <div class="about_content_list_image">
                    <img src="./images/pg2.jpg" style="width:90px;height:89px" alt="">
                </div>

                <div class="et_pb_testimonial_description" style="margin-left: 0px;">
                    <div class="et_pb_testimonial_description_inner">
                        <p><span>Some really great information and very well presented</span></p>
                        <strong class="et_pb_testimonial_author">Yvette M. Northrop</strong>
                        <p class="et_pb_testimonial_meta">1533 Spring Haven Trail, NJ 07017</p>
                    </div> <!-- .et_pb_testimonial_description_inner -->
                </div>

            </div>
        </div>

        <div class="about_content_lists">
            <div class="about_content_list">
                <div class="about_content_list_image">
                    <img src="./images/pg3.jpg"  style="width:90px;height:89px" alt="">
                </div>

                <div class="et_pb_testimonial_description" style="margin-left: 0px;">
                    <div class="et_pb_testimonial_description_inner">
                        <p><span>Some really great information and very well presented</span></p>
                        <strong class="et_pb_testimonial_author">Yvette M. Northrop</strong>
                        <p class="et_pb_testimonial_meta">1533 Spring Haven Trail, NJ 07017</p>
                    </div> <!-- .et_pb_testimonial_description_inner -->
                </div>

            </div>
        </div>

        <div class="about_content_lists">
            <div class="about_content_list">
                <div class="about_content_list_image">
                    <img src="./images/pg1.jpg"  style="width:90px;height:89px" alt="">
                </div>

                <div class="et_pb_testimonial_description" style="margin-left: 0px;">
                    <div class="et_pb_testimonial_description_inner">
                        <p><span>Some really great information and very well presented</span></p>
                        <strong class="et_pb_testimonial_author">Yvette M. Northrop</strong>
                        <p class="et_pb_testimonial_meta">1533 Spring Haven Trail, NJ 07017</p>
                    </div> <!-- .et_pb_testimonial_description_inner -->
                </div>

            </div>
        </div>

    </div>

</div>
<!--aboutus结束-->


<!--jionnow 开始-->
<div class="container-fluid joinnow">

    <div class="joinnow_center">
        <div class="joinnow_title">

            <h1 style="text-align: center;color: #fff;">Look No Further. Get Started Today</h1>
            <h4></h4>
            <h4 style="text-align: center;color: #fff;">Registed for all our courses with 50% discount</h4>
        </div>

        <div class="joinnow_btn">
            <a class="joinnow_button" href="https://demo3.academyofmine.com/our-courses/">Join Now</a>
        </div>

    </div>

</div>
<!--joinnow结束-->


<!--email us 开始-->
<div class="container-fluid email">
    <div class="email_content">

        <div class="email_content_left">
            <div class="email_content_left_list">
                <img width="200" height="200" src="https://demo3.academyofmine.com/wp-content/uploads/2017/08/Cherry-small.jpeg" class=" et_bloom_image_slideup et_bloom_image" alt="" srcset="https://demo3.academyofmine.com/wp-content/uploads/2017/08/Cherry-small.jpeg 200w, https://demo3.academyofmine.com/wp-content/uploads/2017/08/Cherry-small-150x150.jpeg 150w, https://demo3.academyofmine.com/wp-content/uploads/2017/08/Cherry-small-157x157.jpeg 157w, https://demo3.academyofmine.com/wp-content/uploads/2017/08/Cherry-small-40x40.jpeg 40w, https://demo3.academyofmine.com/wp-content/uploads/2017/08/Cherry-small-60x60.jpeg 60w, https://demo3.academyofmine.com/wp-content/uploads/2017/08/Cherry-small-32x32.jpeg 32w, https://demo3.academyofmine.com/wp-content/uploads/2017/08/Cherry-small-50x50.jpeg 50w, https://demo3.academyofmine.com/wp-content/uploads/2017/08/Cherry-small-64x64.jpeg 64w, https://demo3.academyofmine.com/wp-content/uploads/2017/08/Cherry-small-96x96.jpeg 96w, https://demo3.academyofmine.com/wp-content/uploads/2017/08/Cherry-small-128x128.jpeg 128w" sizes="(max-width: 200px) 100vw, 200px">
                <div class="email_content_left_list_text">
                    <h2>Subscribe to get FREE Cherry Tips</h2>
                    <p>We send new tips every month to enhance your Cherry Farming Skills</p>
                </div>
            </div>

        </div>


        <div class="email_content_right">

            <div class="email_content_form">

                <div class="email_content_fields">

                    <p class="email_content_email">
                        <input placeholder="Email" class="inputText">
                    </p>

                    <button class="inputText">
                        <span class="et_bloom_subscribe_loader"></span>
                        <span class="et_bloom_button_text et_bloom_button_text_color_dark">Subscribe</span>
                    </button>
                </div>


            </div>
        </div>

    </div>

</div>
<!--email结束-->