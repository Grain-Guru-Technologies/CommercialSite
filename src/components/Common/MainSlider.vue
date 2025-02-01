<template>
      <section class="main-slider">
        <div class="swiper-container thm-swiper__slider" data-swiper-options='{
            "slidesPerView": 1,
            "loop": true,
            "effect": "fade",
            "autoplay": {
                "delay": 5000
            },
            "navigation": {
                "nextEl": "#main-slider__swiper-button-next",
                "prevEl": "#main-slider__swiper-button-prev"
            }
        }'>
            <div class="swiper-wrapper">
                <div class="swiper-slide">
                    <div class="image-layer" style="background-image: url(assets/images/main-slider/banner1.jpg);">
                    </div>
                    <!-- /.image-layer -->
                    <div class="container">
                        <div class="row">
                            <div class="col-xl-7 col-lg-7">
                                <span class="tagline">Welcome to Grainguru Technologies Inc</span>
                                <h2><span>Robotic</span> <br>
                                  Storage Management</h2>
                                <p>Transforming grain storage with cutting-edge robotic solutions.
                                  Ensuring efficiency, safety, and quality like never before.</p>
                                <a href="#" class=" thm-btn">Discover More</a>
                                <br/><br/>
                                <!-- /.thm-btn dynamic-radius -->
                            </div><!-- /.col-lg-7 text-right -->
                        </div><!-- /.row -->
                    </div><!-- /.container -->
                </div><!-- /.swiper-slide -->
                <div class="swiper-slide">
                    <div class="image-layer" style="background-image: url(assets/images/main-slider/banner2.jpg);">
                    </div>
                    <!-- /.image-layer -->
                    <div class="container">
                        <div class="row">
                            <div class="col-xl-7 col-lg-7">
                                <span class="tagline">Utilizing AI and Robotics for Real-Time Grain Monitoring</span>
                                <h2><span>Smart</span><br>
                                    Technology Integration</h2>
                                <p>Tracks temperature, humidity, and grain movement, allowing for proactive management and quick responses to any deviations.</p>
                                <a href="#" class=" thm-btn">Discover More</a>
                                <!-- /.thm-btn dynamic-radius -->
                            </div><!-- /.col-lg-7 text-right -->
                        </div><!-- /.row -->
                    </div><!-- /.container -->
                </div><!-- /.swiper-slide -->
                <div class="swiper-slide">
                  <div class="image-layer" style="background-image: url(assets/images/main-slider/banner3.jpg);">
                  </div>
                  <!-- /.image-layer -->
                  <div class="container">
                      <div class="row">
                          <div class="col-xl-7 col-lg-7">
                              <span class="tagline">Ensuring Safe and Secure Storage</span>
                              <h2><span>Safeguarding</span><br/>
                                Grain <br/>Quality </h2>
                              <p>Ensuring better handling of grain and preventing spoilage or contamination. Continuously monitor conditions, safeguarding the quality of stored grain.</p>

                              <a href="#" class=" thm-btn">Discover More</a>
                              <br/>
                              <br/>                             
                              <!-- /.thm-btn dynamic-radius -->
                          </div><!-- /.col-lg-7 text-right -->
                      </div><!-- /.row -->
                  </div><!-- /.container -->
              </div><!-- /.swiper-slide -->
            </div><!-- /.swiper-wrapper -->

            <!-- If we need navigation buttons -->
            <div class="main-slider__nav">
                <div class="swiper-button-prev" id="main-slider__swiper-button-next"><i class="agrikon-icon-left-arrow"></i>
                </div>
                <div class="swiper-button-next" id="main-slider__swiper-button-prev"><i class="agrikon-icon-right-arrow"></i></div>
            </div><!-- /.main-slider__nav -->

        </div><!-- /.swiper-container thm-swiper__slider -->
    </section><!-- /.main-slider -->
</template>


<script>
export default {
    name: 'MainSlider'
}
</script>