<template>
      <header class="main-header">
        <div class="topbar">
            <div class="container">
                <div class="topbar__left">
                    <div class="topbar__social">
                        <a href="#" class="fab fa-facebook-square"></a>
                        <a href="#" class="fab fa-twitter"></a>
                        <a href="#" class="fab fa-pinterest-p"></a>
                        <a href="#" class="fab fa-instagram"></a>
                    </div><!-- /.topbar__social -->
                    <p>Welcome to Grainguru Technologies Inc</p>
                </div><!-- /.topbar__left -->
                <div class="topbar__right">
                    <a href="#"><i class="agrikon-icon-email"></i>info@graingurutechnologies.com</a>
                    <a href="#"><i class="agrikon-icon-clock"></i>Mon - Sat 8:00 - 6:30, Sunday - CLOSED</a>
                </div><!-- /.topbar__right -->
            </div><!-- /.container -->
        </div><!-- /.topbar -->
        <nav class="main-menu">
            <div class="container">
                <div class="logo-box">
                    <a href="#" aria-label="logo image"><img src="assets/images/logos/grain-guru-logo.png" width="153" alt=""></a>
                    <span class="fa fa-bars mobile-nav__toggler"></span>
                </div><!-- /.logo-box -->
                <ul class="main-menu__list">
                    <li class="dropdown">
                        <a href="#">Home</a>
                    </li>
                    <li>
                        <a href="#">About Us</a>
                    </li>
                    <li class="dropdown"><a href="#">Products</a>
                    </li>
                    <li class="dropdown">
                        <a href="#">Solutions</a>
                        <!-- <ul>
                            <li><a href="projects.html">Projects</a></li>
                            <li><a href="project-details.html">Projects Details</a></li>
                        </ul> -->
                    </li>
                    <li class="dropdown"><a href="#">Contact Us</a>
                        <!-- <ul>
                            <li><a href="blog.html">News</a></li>
                            <li><a href="blog-details.html">News Details</a></li>
                        </ul> -->
                    </li>
                </ul>
                <!-- /.main-menu__list -->

                <div class="main-header__info">
                    <!-- <a href="#" class="search-toggler main-header__search-btn"><i class="agrikon-icon-magnifying-glass"></i></a> -->
                    <!-- <a class="main-header__cart-btn" href="#"><i class="agrikon-icon-shopping-cart"></i></a> -->
                    <a href="tel:92-666-888-0000" class="main-header__info-phone">
                        <i class="agrikon-icon-phone-call"></i>
                        <span class="main-header__info-phone-content">
                            <span class="main-header__info-phone-text">Call Anytime</span>
                            <span class="main-header__info-phone-title">coming soon..</span>
                        </span><!-- /.main-header__info-phone-content -->
                    </a><!-- /.main-header__info-phone -->
                </div><!-- /.main-header__info -->
            </div><!-- /.container -->
        </nav>
        <!-- /.main-menu -->
    </header><!-- /.main-header -->
</template>

<script>
export default {
    name: 'MainHeader',
}
</script>