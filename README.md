Skip to content
Why GitHub? 
Team
Enterprise
Explore 
Marketplace
Pricing 
Search

Sign in
Sign up
CodeBoxxTechSchool
/
GenesisProgram
11648
Code
Issues
Pull requests
1
Actions
Projects
Security
Insights
GenesisProgram/Smarty/HTML_BS4/index-onepage-construction.html
@ngenest
ngenest Complete Smarty Template
…
Latest commit aa63799 on Aug 28, 2018
 History
 1 contributor
1416 lines (1130 sloc)  44.9 KB
  
<!DOCTYPE html>
<html lang="en">
	<head>
		<meta charset="utf-8" />
		<title>Smarty - Multipurpose + Admin</title>
		<meta name="description" content="" />
		<meta name="Author" content="Dorin Grigoras [www.stepofweb.com]" />

		<!-- mobile settings -->
		<meta name="viewport" content="width=device-width, maximum-scale=1, initial-scale=1, user-scalable=0" />
		<!--[if IE]><meta http-equiv='X-UA-Compatible' content='IE=edge,chrome=1'><![endif]-->

		<!-- WEB FONTS : use %7C instead of | (pipe) -->
		<link href="https://fonts.googleapis.com/css?family=Open+Sans:300,400,600%7CRaleway:300,400,500,600,700%7CLato:300,400,400italic,600,700" rel="stylesheet" type="text/css" />

		<!-- CORE CSS -->
		<link href="assets/plugins/bootstrap/css/bootstrap.min.css" rel="stylesheet" type="text/css" />

		<!-- REVOLUTION SLIDER -->
		<link href="assets/plugins/slider.revolution/css/extralayers.css" rel="stylesheet" type="text/css" />
		<link href="assets/plugins/slider.revolution/css/settings.css" rel="stylesheet" type="text/css" />

		<!-- THEME CSS -->
		<link href="assets/css/essentials.css" rel="stylesheet" type="text/css" />
		<link href="assets/css/layout.css" rel="stylesheet" type="text/css" />

		<!-- PAGE LEVEL SCRIPTS -->
		<link href="assets/css/header-1.css" rel="stylesheet" type="text/css" />
		<link href="assets/css/color_scheme/yellow.css" rel="stylesheet" type="text/css" id="color_scheme" />
	</head>

	<!--
		AVAILABLE BODY CLASSES:
		
		smoothscroll 			= create a browser smooth scroll
		enable-animation		= enable WOW animations
		bg-grey					= grey background
		grain-grey				= grey grain background
		grain-blue				= blue grain background
		grain-green				= green grain background
		grain-blue				= blue grain background
		grain-orange			= orange grain background
		grain-yellow			= yellow grain background
		
		boxed 					= boxed layout
		pattern1 ... patern11	= pattern background
		menu-vertical-hide		= hidden, open on click
		
		BACKGROUND IMAGE [together with .boxed class]
		data-background="assets/images/_smarty/boxed_background/1.jpg"
	-->
	<body class="smoothscroll enable-animation">

		<!-- SLIDE TOP -->
		<div id="slidetop">

			<div class="container">
				
				<div class="row">

					<div class="col-md-4">
						<h6><i class="icon-heart"></i> WHY SMARTY?</h6>
						<p>Lorem ipsum dolor sit amet, consectetur adipiscing elit. Maecenas metus nulla, commodo a sodales sed, dignissim pretium nunc. Nam et lacus neque. Ut enim massa, sodales tempor convallis et, iaculis ac massa. </p>
					</div>

					<div class="col-md-4">
						<h6><i class="fa-facheck"></i> RECENTLY VISITED</h6>
						<ul class="list-unstyled">
							<li><a href="#"><i class="fa fa-angle-right"></i> Consectetur adipiscing elit amet</a></li>
							<li><a href="#"><i class="fa fa-angle-right"></i> This is a very long text, very very very very very very very very very very very very </a></li>
							<li><a href="#"><i class="fa fa-angle-right"></i> Lorem ipsum dolor sit amet</a></li>
							<li><a href="#"><i class="fa fa-angle-right"></i> Dolor sit amet,consectetur adipiscing elit amet</a></li>
							<li><a href="#"><i class="fa fa-angle-right"></i> Consectetur adipiscing elit amet,consectetur adipiscing elit</a></li>
						</ul>
					</div>

					<div class="col-md-4">
						<h6><i class="icon-envelope"></i> CONTACT INFO</h6>
						<ul class="list-unstyled">
							<li><b>Address:</b> PO Box 21132, Here Weare St, <br /> Melbourne, Vivas 2355 Australia</li>
							<li><b>Phone:</b> 1-800-565-2390</li>
							<li><b>Email:</b> <a href="mailto:support@yourname.com">support@yourname.com</a></li>
						</ul>
					</div>

				</div>

			</div>

			<a class="slidetop-toggle" href="#"><!-- toggle button --></a>

		</div>
		<!-- /SLIDE TOP -->


		<!-- wrapper -->
		<div id="wrapper">

			<!-- 
				AVAILABLE HEADER CLASSES
				Default nav height: 96px
				.header-md 		= 70px nav height
				.header-sm 		= 60px nav height
				.b-0 		= remove bottom border (only with transparent use)
				.transparent	= transparent header
				.translucent	= translucent header
				.sticky			= sticky header
				.static			= static header
				.dark			= dark header
				.bottom			= header on bottom
				
				shadow-before-1 = shadow 1 header top
				shadow-after-1 	= shadow 1 header bottom
				shadow-before-2 = shadow 2 header top
				shadow-after-2 	= shadow 2 header bottom
				shadow-before-3 = shadow 3 header top
				shadow-after-3 	= shadow 3 header bottom
				.clearfix		= required for mobile menu, do not remove!
				Example Usage:  class="clearfix sticky header-sm transparent b-0"
			-->
			<div id="header" class="navbar-toggleable-md sticky header-md clearfix">

				<!-- TOP NAV -->
				<header id="topNav">
					<div class="container">

						<!-- Mobile Menu Button -->
						<button class="btn btn-mobile" data-toggle="collapse" data-target=".nav-main-collapse">
							<i class="fa fa-bars"></i>
						</button>

						<!-- Logo -->
						<a class="logo float-left scrollTo" href="#top">
							<img src="assets/images/_smarty/logo_dark.png" alt="" />
						</a>

						<!-- 
							Top Nav 
							
							AVAILABLE CLASSES:
							submenu-dark = dark sub menu
						-->
						<div class="navbar-collapse collapse float-right nav-main-collapse submenu-dark">
							<nav class="nav-main">

								<!-- 
									.nav-onepage
									Required for onepage navigation links
									
									Add .external for an external link!
								-->
								<ul id="topMain" class="nav nav-pills nav-main nav-onepage">
									<li class="active"><!-- HOME -->
										<a href="#home">
											HOME
										</a>
									</li>
									<li><!-- SERVICES -->
										<a href="#services">
											SERVICES
										</a>
									</li>
									<li><!-- WORK -->
										<a href="#work">
											WORK
										</a>
									</li>
									<li><!-- NEWS -->
										<a href="#news">
											NEWS
										</a>
									</li>
									<li><!-- OVERVIEW -->
										<a href="#overview">
											OVERVIEW
										</a>
									</li>
									<li><!-- CLIENTS -->
										<a href="#clients">
											CLIENTS
										</a>
									</li>
									<li><!-- BLOG -->
										<a class="external" href="blog-default-aside-left.html">
											BLOG
										</a>
									</li>
									<li><!-- CONTACT -->
										<a href="#contact">
											CONTACT
										</a>
									</li>
								</ul>

							</nav>
						</div>

					</div>
				</header>
				<!-- /Top Nav -->

			</div>



			<!-- REVOLUTION SLIDER -->
			<div class="slider fullwidthbanner-container roundedcorners">
				<!--
					Navigation Styles:
					
						data-navigationStyle="" theme default navigation
						
						data-navigationStyle="preview1"
						data-navigationStyle="preview2"
						data-navigationStyle="preview3"
						data-navigationStyle="preview4"
						
					Bottom Shadows
						data-shadow="1"
						data-shadow="2"
						data-shadow="3"
						
					Slider Height (do not use on fullscreen mode)
						data-height="300"
						data-height="350"
						data-height="400"
						data-height="450"
						data-height="500"
						data-height="550"
						data-height="600"
						data-height="650"
						data-height="700"
						data-height="750"
						data-height="800"
				-->
				<div class="fullwidthbanner" data-height="600" data-shadow="0" data-navigationStyle="preview2">
					<ul class="hide">
					
						<!-- SLIDE  -->
						<li data-transition="parallaxtobottom" data-slotamount="7" data-masterspeed="600"  data-saveperformance="off"  data-title="Architectural View">
							<!-- MAIN IMAGE -->
							<img src="demo_files/images/yellow-min.jpg"  alt="cover image"  data-bgposition="center top" data-bgfit="cover" data-bgrepeat="no-repeat">

							<div class="tp-caption white_big skewfromleft tp-resizeme"
								data-x="471"
								data-y="100" 
								data-speed="400"
								data-start="1500"
								data-easing="Power3.easeInOut"
								data-splitin="words"
								data-splitout="none"
								data-elementdelay="0.1"
								data-endelementdelay="0.1"
								data-endspeed="600"
								style="z-index: 2; color:#fff; font-size:65px; line-height:85px; font-weight:bold; letter-spacing:0; text-shadow:none;">
									Architectural View
							</div>

							<div class="tp-caption content_text_center skewfromleft tp-resizeme"
								data-x="530"
								data-y="195" 
								data-speed="500"
								data-start="2000"
								data-easing="Power3.easeInOut"
								data-splitin="none"
								data-splitout="none"
								data-elementdelay="0.1"
								data-endelementdelay="0.1"
								data-endspeed="600"

								style="z-index: 3; font-size:20px; color:#fff; font-weight:300; text-shadow:none;">
									If you dream of designing a new home that takes full advantage, <br />
									our team is the best in this field.
							</div>

							<div class="tp-caption tp-fade"
								data-x="left"
								data-y="25" 
								data-speed="300"
								data-start="800"
								data-easing="Power3.easeInOut"
								data-elementdelay="0.1"
								data-endelementdelay="0.1"
								data-endspeed="300"
								style="z-index: 4;">
									<img src="demo_files/images/thematics/construction/worker-min.png" alt="">
							</div>

							<div class="tp-caption skewfromleft tp-resizeme  un-button-2-lg"
								data-x="665"
								data-y="300" 
								data-speed="300"
								data-start="2500"
								data-easing="Power3.easeInOut"
								data-splitin="none"
								data-splitout="none"
								data-elementdelay="0.1"
								data-endelementdelay="0.1"
								data-endspeed="300"

								style="z-index: 5; max-width: auto; max-height: auto; white-space: nowrap;">
									<a class="btn btn-warning btn-lg" href="#">OUR SERVICES &nbsp; <i class="fa fa-angle-right"></i></a>
							</div>
						</li>

						<!-- SLIDE  -->
						<li data-transition="parallaxtotop" data-slotamount="7" data-masterspeed="300"  data-saveperformance="off" data-title="Bright Future">
							<!-- MAIN IMAGE -->
							<img src="demo_files/images/thematics/construction/slider_2-min.jpg" alt="cover image"  data-bgposition="center top" data-bgfit="cover" data-bgrepeat="no-repeat">

							<div class="overlay dark-4"><!-- dark overlay [0 to 9 opacity] --></div>

							<div class="tp-caption font-roboto skewfromleft tp-resizeme"
								data-x="50"
								data-y="100" 
								data-speed="500"
								data-start="1500"
								data-easing="Cubic.easeOut"
								data-splitin="none"
								data-splitout="none"
								data-elementdelay="0.1"
								data-endelementdelay="0.1"
								data-endspeed="500"
								style="z-index: 2; color:#fff; font-size:65px; line-height:85px; font-weight:bold; letter-spacing:0; text-shadow:none;">
									Creating a Bright Future <br />
									Together
							</div>

							<div class="tp-caption skewfromrightshort tp-resizeme"
								data-x="50"
								data-y="300" 
								data-speed="500"
								data-start="1000"
								data-easing="easeInCirc"
								data-splitin="none"
								data-splitout="none"
								data-elementdelay="0.1"
								data-endelementdelay="0.1"
								data-endspeed="500"
								style="z-index: 3; font-size:20px; color:#fff; font-weight:300; text-shadow:none;">
									If you dream of designing a new home that takes full advantage, <br />
									our team is the best in this field.
							</div>

							<div class="tp-caption sfb tp-resizeme"
								data-x="50"
								data-y="410" 
								data-speed="500"
								data-start="1500"
								data-easing="Power3.easeIn"
								data-splitin="none"
								data-splitout="none"
								data-elementdelay="1"
								data-endelementdelay="0.1"
								data-endspeed="500"
								style="z-index: 4; max-width: auto;">
									<a class="btn btn-warning btn-lg" href="#">OUR SERVICES &nbsp; <i class="fa fa-angle-right"></i></a>
							</div>

							<div class="tp-caption sfb tp-resizeme"
								data-x="250"
								data-y="410" 
								data-speed="500"
								data-start="1500"
								data-easing="Power3.easeInOut"
								data-splitin="none"
								data-splitout="none"
								data-elementdelay="0.1"
								data-endelementdelay="0.1"
								data-endspeed="500"
								style="z-index: 6; max-width: auto; max-height: auto; white-space: nowrap;">
									<a class="btn btn-default btn-lg" href="#">GET A QUOTE &nbsp; <i class="fa fa-angle-right"></i></a>
							</div>
						</li>

					</ul>

				</div>
			</div>
			<!-- /REVOLUTION SLIDER -->


			<hr class="m-0" /><!-- 1px line separator -->


			<!-- BUTTON CALLOUT -->
			<a href="#" class="btn btn-xlg btn-primary fs-20 fullwidth m-0 rad-0 p-40">
				<span class="font-lato fs-30">
					Did Smarty convinced you? 
					<strong>Contact us &raquo;</strong>
				</span>
			</a>
			<!-- /BUTTON CALLOUT -->


			
			<!-- Services -->
			<section id="services">
				<div class="container">

					<div class="row">
						<div class="col-sm-4">
							<a class="image-hover lightbox" href="https://vimeo.com/ondemand/buildingwithawareness/108669033" data-plugin-options='{"type":"iframe"}'>
								<span class="image-hover-icon image-hover-dark"><!-- image-hover-light | image-hover-dark -->
									<i class="fa fa-vimeo-square"><!-- video icon --></i>
								</span>
								<img class="img-fluid" src="demo_files/images/thematics/construction/c3-min.jpg" alt="img" />
							</a>

							<h3 class="mt-10">The Green Building</h3>
							<p>Lorem ipsum dolor sit amet, consectetur adipiscing elit. Maecenas metus nulla, commodo a sodales sed, dignissim pretium nunc. Nam et lacus neque.</p>
							<a href="#" class="btn btn-default">THE BENEFITS</a>
						</div>

						<div class="col-sm-4">
							<a class="image-hover lightbox" href="https://www.youtube.com/watch?v=ZhCyoDlltbo" data-plugin-options='{"type":"iframe"}'>
								<span class="image-hover-icon image-hover-dark"><!-- image-hover-light | image-hover-dark -->
									<i class="fa fa-youtube-square"><!-- video icon --></i>
								</span>
								<img class="img-fluid" src="demo_files/images/thematics/construction/c1-min.jpg" alt="img" />
							</a>
							<h3 class="mt-10">Best House Renovation</h3>
							<p>Lorem ipsum dolor sit amet, consectetur adipiscing elit. Maecenas metus nulla, commodo a sodales sed, dignissim pretium nunc. Nam et lacus neque.</p>
							<a href="#" class="btn btn-default">READ MORE</a>
						</div>

						<div class="col-sm-4">
							<img class="img-fluid" src="demo_files/images/thematics/construction/c2-min.jpg" alt="img" />
							<h3 class="mt-10">The Effective Teamwork</h3>
							<p>Lorem ipsum dolor sit amet, consectetur adipiscing elit. Maecenas metus nulla, commodo a sodales sed, dignissim pretium nunc. Nam et lacus neque.</p>
							<a href="#" class="btn btn-default">READ MORE</a>
						</div>

					</div>

				</div>
			</section>
			<!-- /Services -->

			


			<!-- Parallax -->
			<section class="parallax parallax-1" style="background-image: url('demo_files/images/1200x800/34-min.jpg');">
				<div class="overlay dark-5"><!-- dark overlay [1 to 9 opacity] --></div>

				<div class="container">

					<div class="text-center">
						<h2 class="fs-40 fw-300">Contractor &amp; Construction Since 1982</h2>
						<a class="btn btn-default btn-lg" href="#">GET A QUOTE <i class="fa fa-angle-right"></i></a> 
						&nbsp; OR &nbsp; 
						<a class="btn btn-warning btn-lg" href="#">OUR SERVICES <i class="fa fa-angle-right"></i></a>
					</div>

				</div>
			</section>
			<!-- /Parallax -->




			<!-- PORTFOLIO -->
			<section id="work">
				<div class="container">

					<div class="heading-title heading-dotted text-center">
						<h2>Featured Work</h2>
					</div>

					<div class="text-center">
						<ul class="nav nav-pills mix-filter mb-60">
							<li data-filter="all" class="filter active"><a href="#">All</a></li>
							<li data-filter="development" class="filter"><a href="#">Development</a></li>
							<li data-filter="photography" class="filter"><a href="#">Photography</a></li>
							<li data-filter="design" class="filter"><a href="#">Design</a></li>
						</ul>
					</div>

				</div>

				<div id="portfolio" class="portfolio-nogutter">

						<div class="row mix-grid">

							<div class="col-md-3 col-sm-3 mix design"><!-- item -->

								<div class="item-box">
									<figure>
										<span class="item-hover">
											<span class="overlay dark-5"></span>
											<span class="inner">

												<!-- lightbox -->
												<a class="ico-rounded lightbox" href="demo_files/images/thematics/construction/w1-min.jpg" data-plugin-options='{"type":"image"}'>
													<span class="fa fa-plus fs-20"></span>
												</a>

												<!-- details -->
												<a class="ico-rounded lightbox" href="ajax/portfolio-detail-modal-6.html" data-plugin-options='{"type":"ajax", "closeOnBgClick":false}'>
													<span class="glyphicon glyphicon-option-horizontal fs-20"></span>
												</a>

											</span>
										</span>

										<img class="img-fluid" src="demo_files/images/thematics/construction/w1-min.jpg" width="600" height="399" alt="">
									</figure>

									<div class="item-box-desc">
										<h3>Architect Project</h3>
										<ul class="list-inline categories m-0">
											<li><a href="#">Architecture</a></li>
											<li><a href="#">Design</a></li>
										</ul>
									</div>

								</div>

							</div><!-- /item -->


							<div class="col-md-3 col-sm-3 mix development"><!-- item -->

								<div class="item-box">
									<figure>
										<span class="item-hover">
											<span class="overlay dark-5"></span>
											<span class="inner">

												<!-- lightbox -->
												<a class="ico-rounded lightbox" href="demo_files/images/thematics/construction/w2-min.jpg" data-plugin-options='{"type":"image"}'>
													<span class="fa fa-plus fs-20"></span>
												</a>

												<!-- details -->
												<a class="ico-rounded lightbox" href="ajax/portfolio-detail-modal-6.html" data-plugin-options='{"type":"ajax", "closeOnBgClick":false}'>
													<span class="glyphicon glyphicon-option-horizontal fs-20"></span>
												</a>

											</span>
										</span>

										<img class="img-fluid" src="demo_files/images/thematics/construction/w2-min.jpg" width="600" height="399" alt="">
									</figure>

									<div class="item-box-desc">
										<h3>Speaker Design</h3>
										<ul class="list-inline categories m-0">
											<li><a href="#">Audio</a></li>
											<li><a href="#">Design</a></li>
										</ul>
									</div>

								</div>

							</div><!-- /item -->


							<div class="col-md-3 col-sm-3 mix photography"><!-- item -->

								<div class="item-box">
									<figure>
										<span class="item-hover">
											<span class="overlay dark-5"></span>
											<span class="inner">

												<!-- lightbox -->
												<a class="ico-rounded lightbox" href="demo_files/images/thematics/construction/w3-min.jpg" data-plugin-options='{"type":"image"}'>
													<span class="fa fa-plus fs-20"></span>
												</a>

												<!-- details -->
												<a class="ico-rounded lightbox" href="ajax/portfolio-detail-modal-4.html" data-plugin-options='{"type":"ajax", "closeOnBgClick":false}'>
													<span class="glyphicon glyphicon-option-horizontal fs-20"></span>
												</a>

											</span>
										</span>

										<img class="img-fluid" src="demo_files/images/thematics/construction/w3-min.jpg" width="600" height="399" alt="">
									</figure>

									<div class="item-box-desc">
										<h3>Mobile Development</h3>
										<ul class="list-inline categories m-0">
											<li><a href="#">Development</a></li>
											<li><a href="#">Design</a></li>
										</ul>
									</div>

								</div>

							</div><!-- /item -->


							<div class="col-md-3 col-sm-3 mix design"><!-- item -->

								<div class="item-box">
									<figure>
										<span class="item-hover">
											<span class="overlay dark-5"></span>
											<span class="inner">

												<!-- lightbox -->
												<a class="ico-rounded lightbox" href="demo_files/images/thematics/construction/w4-min.jpg" data-plugin-options='{"type":"image"}'>
													<span class="fa fa-plus fs-20"></span>
												</a>

												<!-- details -->
												<a class="ico-rounded" href="portfolio-single-slider.html">
													<span class="glyphicon glyphicon-option-horizontal fs-20"></span>
												</a>

											</span>
										</span>

										<img class="img-fluid" src="demo_files/images/thematics/construction/w4-min.jpg" width="600" height="399" alt="">
									</figure>

									<div class="item-box-desc">
										<h3>Nature Art</h3>
										<ul class="list-inline categories m-0">
											<li><a href="#">Nature</a></li>
											<li><a href="#">Art</a></li>
										</ul>
									</div>

								</div>

							</div><!-- /item -->


							<div class="col-md-3 col-sm-3 mix design"><!-- item -->

								<div class="item-box">
									<figure>
										<span class="item-hover">
											<span class="overlay dark-5"></span>
											<span class="inner">

												<!-- lightbox -->
												<a class="ico-rounded lightbox" href="demo_files/images/thematics/construction/w5-min.jpg" data-plugin-options='{"type":"image"}'>
													<span class="fa fa-plus fs-20"></span>
												</a>

												<!-- details -->
												<a class="ico-rounded" href="portfolio-single-slider.html">
													<span class="glyphicon glyphicon-option-horizontal fs-20"></span>
												</a>

											</span>
										</span>

										<img class="img-fluid" src="demo_files/images/thematics/construction/w5-min.jpg" width="600" height="399" alt="">
									</figure>

									<div class="item-box-desc">
										<h3>Nature Art</h3>
										<ul class="list-inline categories m-0">
											<li><a href="#">Nature</a></li>
											<li><a href="#">Art</a></li>
										</ul>
									</div>

								</div>

							</div><!-- /item -->


							<div class="col-md-3 col-sm-3 mix photography"><!-- item -->

								<div class="item-box">
									<figure>
										<span class="item-hover">
											<span class="overlay dark-5"></span>
											<span class="inner">

												<!-- lightbox -->
												<a class="ico-rounded lightbox" href="demo_files/images/thematics/construction/w6-min.jpg" data-plugin-options='{"type":"image"}'>
													<span class="fa fa-plus fs-20"></span>
												</a>

												<!-- details -->
												<a class="ico-rounded" href="portfolio-single-slider.html">
													<span class="glyphicon glyphicon-option-horizontal fs-20"></span>
												</a>

											</span>
										</span>

										<img class="img-fluid" src="demo_files/images/thematics/construction/w6-min.jpg" width="600" height="399" alt="">
									</figure>

									<div class="item-box-desc">
										<h3>Mobile Development</h3>
										<ul class="list-inline categories m-0">
											<li><a href="#">Development</a></li>
											<li><a href="#">Design</a></li>
										</ul>
									</div>

								</div>

							</div><!-- /item -->


							<div class="col-md-3 col-sm-3 mix design"><!-- item -->

								<div class="item-box">
									<figure>
										<span class="item-hover">
											<span class="overlay dark-5"></span>
											<span class="inner">

												<!-- lightbox -->
												<a class="ico-rounded lightbox" href="demo_files/images/thematics/construction/w7-min.jpg" data-plugin-options='{"type":"image"}'>
													<span class="fa fa-plus fs-20"></span>
												</a>

												<!-- details -->
												<a class="ico-rounded" href="portfolio-single-slider.html">
													<span class="glyphicon glyphicon-option-horizontal fs-20"></span>
												</a>

											</span>
										</span>

										<img class="img-fluid" src="demo_files/images/thematics/construction/w7-min.jpg" width="600" height="399" alt="">
									</figure>

									<div class="item-box-desc">
										<h3>Nature Art</h3>
										<ul class="list-inline categories m-0">
											<li><a href="#">Nature</a></li>
											<li><a href="#">Art</a></li>
										</ul>
									</div>

								</div>

							</div><!-- /item -->


							<div class="col-md-3 col-sm-3 mix design"><!-- item -->

								<div class="item-box">
									<figure>
										<span class="item-hover">
											<span class="overlay dark-5"></span>
											<span class="inner">

												<!-- lightbox -->
												<a class="ico-rounded lightbox" href="demo_files/images/thematics/construction/w8-min.jpg" data-plugin-options='{"type":"image"}'>
													<span class="fa fa-plus fs-20"></span>
												</a>

												<!-- details -->
												<a class="ico-rounded" href="portfolio-single-slider.html">
													<span class="glyphicon glyphicon-option-horizontal fs-20"></span>
												</a>

											</span>
										</span>

										<img class="img-fluid" src="demo_files/images/thematics/construction/w8-min.jpg" width="600" height="399" alt="">
									</figure>

									<div class="item-box-desc">
										<h3>Nature Art</h3>
										<ul class="list-inline categories m-0">
											<li><a href="#">Nature</a></li>
											<li><a href="#">Art</a></li>
										</ul>
									</div>

								</div>

							</div><!-- /item -->


						</div>


				</div>
			</section>
			<!-- /PORTFOLIO -->




			<!-- Testimonials -->
			<section class="section-xs dark">
				<div class="container">

					<div class="owl-carousel text-center owl-testimonial m-0" data-plugin-options='{"singleItem": true, "autoPlay": 3500, "navigation": false, "pagination": true, "transitionStyle":"fade"}'>
						<div class="testimonial">
							<figure>
								<img class="rounded" src="demo_files/images/people/300x300/11-min.jpg" alt="" />
							</figure>
							<div class="testimonial-content p-0">
								<p class="lead">Incidunt deleniti blanditiis quas aperiam recusandae consequatur ullam quibusdam cum libero.</p>
								<cite>
									Joana Doe
									<span>Company Ltd.</span>
								</cite>
							</div>
						</div>
						<div class="testimonial">
							<figure>
								<img class="rounded" src="demo_files/images/people/300x300/12-min.jpg" alt="" />
							</figure>
							<div class="testimonial-content p-0">
								<p class="lead">Quod necessitatibus quis expedita harum provident eos obcaecati id culpa.</p>
								<cite>
									Melissa Doe
									<span>Company Ltd.</span>
								</cite>
							</div>
						</div>
					</div>

				</div>
			</section>
			<!-- /Testimonials -->





			<!-- News -->
			<section id="news">
				<div class="container">

					<div class="heading-title heading-dotted text-center">
						<h2>Recent News</h2>
					</div>

					<!-- 
						controlls-over		= navigation buttons over the image 
						buttons-autohide 	= navigation buttons visible on mouse hover only
						
						data-plugin-options:
							"singleItem": true
							"autoPlay": true (or ms. eg: 4000)
							"navigation": true
							"pagination": true
							"items": "4"
						owl-carousel item paddings
							.owl-padding-0
							.owl-padding-3
							.owl-padding-6
							.owl-padding-10
							.owl-padding-15
							.owl-padding-20
					-->
					<div class="owl-carousel owl-padding-10 buttons-autohide controlls-over" data-plugin-options='{"singleItem": false, "items":"4", "autoPlay": 4000, "navigation": true, "pagination": false}'>
						<div class="img-hover">
							<a href="blog-single-default.html">
								<img class="img-fluid" src="demo_files/images/451x300/24-min.jpg" alt="">
							</a>

							<h4 class="text-left mt-20"><a href="blog-single-default.html">Lorem Ipsum Dolor</a></h4>
							<p class="text-left">Lorem ipsum dolor sit amet, consectetur adipisicing elit. Cupiditate, asperiores quod est tenetur in.</p>
							<ul class="text-left fs-12 list-inline list-separator">
								<li>
									<i class="fa fa-calendar"></i> 
									29th Jan 2017
								</li>
								<li>
									<a href="blog-single-default.html#comments">
										<i class="fa fa-comments"></i> 
										3
									</a>
								</li>
							</ul>
						</div>
						<div class="img-hover">
							<a href="blog-single-default.html">
								<img class="img-fluid" src="demo_files/images/451x300/17-min.jpg" alt="">
							</a>

							<h4 class="text-left mt-20"><a href="blog-single-default.html">Lorem Ipsum Dolor</a></h4>
							<p class="text-left">Lorem ipsum dolor sit amet, consectetur adipisicing elit. Cupiditate, asperiores quod est tenetur in.</p>
							<ul class="text-left fs-12 list-inline list-separator">
								<li>
									<i class="fa fa-calendar"></i> 
									29th Jan 2017
								</li>
								<li>
									<a href="blog-single-default.html#comments">
										<i class="fa fa-comments"></i> 
										3
									</a>
								</li>
							</ul>
						</div>
						<div class="img-hover">
							<a href="blog-single-default.html">
								<img class="img-fluid" src="demo_files/images/451x300/30-min.jpg" alt="">
							</a>

							<h4 class="text-left mt-20"><a href="blog-single-default.html">Lorem Ipsum Dolor</a></h4>
							<p class="text-left">Lorem ipsum dolor sit amet, consectetur adipisicing elit. Cupiditate, asperiores quod est tenetur in.</p>
							<ul class="text-left fs-12 list-inline list-separator">
								<li>
									<i class="fa fa-calendar"></i> 
									29th Jan 2017
								</li>
								<li>
									<a href="blog-single-default.html#comments">
										<i class="fa fa-comments"></i> 
										3
									</a>
								</li>
							</ul>
						</div>
						<div class="img-hover">
							<a href="blog-single-default.html">
								<img class="img-fluid" src="demo_files/images/451x300/26-min.jpg" alt="">
							</a>

							<h4 class="text-left mt-20"><a href="blog-single-default.html">Lorem Ipsum Dolor</a></h4>
							<p class="text-left">Lorem ipsum dolor sit amet, consectetur adipisicing elit. Cupiditate, asperiores quod est tenetur in.</p>
							<ul class="text-left fs-12 list-inline list-separator">
								<li>
									<i class="fa fa-calendar"></i> 
									29th Jan 2017
								</li>
								<li>
									<a href="blog-single-default.html#comments">
										<i class="fa fa-comments"></i> 
										3
									</a>
								</li>
							</ul>
						</div>
						<div class="img-hover">
							<a href="blog-single-default.html">
								<img class="img-fluid" src="demo_files/images/451x300/18-min.jpg" alt="">
							</a>
							<h4 class="text-left mt-20"><a href="blog-single-default.html">Lorem Ipsum Dolor</a></h4>
							<p class="text-left">Lorem ipsum dolor sit amet, consectetur adipisicing elit. Cupiditate, asperiores quod est tenetur in.</p>
							<ul class="text-left fs-12 list-inline list-separator">
								<li>
									<i class="fa fa-calendar"></i> 
									29th Jan 2017
								</li>
								<li>
									<a href="blog-single-default.html#comments">
										<i class="fa fa-comments"></i> 
										3
									</a>
								</li>
							</ul>
						</div>
						<div class="img-hover">
							<a href="blog-single-default.html">
								<img class="img-fluid" src="demo_files/images/451x300/34-min.jpg" alt="">
							</a>
							<h4 class="text-left mt-20"><a href="blog-single-default.html">Lorem Ipsum Dolor</a></h4>
							<p class="text-left">Lorem ipsum dolor sit amet, consectetur adipisicing elit. Cupiditate, asperiores quod est tenetur in.</p>
							<ul class="text-left fs-12 list-inline list-separator">
								<li>
									<i class="fa fa-calendar"></i> 
									29th Jan 2017
								</li>
								<li>
									<a href="blog-single-default.html#comments">
										<i class="fa fa-comments"></i> 
										3
									</a>
								</li>
							</ul>
						</div>
						<div class="img-hover">
							<a href="blog-single-default.html">
								<img class="img-fluid" src="demo_files/images/451x300/37-min.jpg" alt="">
							</a>
							<h4 class="text-left mt-20"><a href="blog-single-default.html">Lorem Ipsum Dolor</a></h4>
							<p class="text-left">Lorem ipsum dolor sit amet, consectetur adipisicing elit. Cupiditate, asperiores quod est tenetur in.</p>
							<ul class="text-left fs-12 list-inline list-separator">
								<li>
									<i class="fa fa-calendar"></i> 
									29th Jan 2017
								</li>
								<li>
									<a href="blog-single-default.html#comments">
										<i class="fa fa-comments"></i> 
										3
									</a>
								</li>
							</ul>
						</div>
						<div class="img-hover">
							<a href="blog-single-default.html">
								<img class="img-fluid" src="demo_files/images/451x300/23-min.jpg" alt="">
							</a>
							<h4 class="text-left mt-20"><a href="blog-single-default.html">Lorem Ipsum Dolor</a></h4>
							<p class="text-left">Lorem ipsum dolor sit amet, consectetur adipisicing elit. Cupiditate, asperiores quod est tenetur in.</p>
							<ul class="text-left fs-12 list-inline list-separator">
								<li>
									<i class="fa fa-calendar"></i> 
									29th Jan 2017
								</li>
								<li>
									<a href="blog-single-default.html#comments">
										<i class="fa fa-comments"></i> 
										3
									</a>
								</li>
							</ul>
						</div>
					</div>

				</div>
			</section>
			<!-- /News -->




			<!-- Overview -->
			<section id="overview">
				<div class="container text-center">

					<div class="row text-left">

						<div class="col-sm-8">
							<img src="demo_files/images/laptop.png" alt="product image" />
						</div>

						<div class="col-sm-4">
							<h3 class="fw-300">Quick <span>Overview</span></h3>
						
							<p>Lorem ipsum dolor sit amet, hinc dolores noluisse at vel, ex quod aperiri scaevola has, cum te sanctus denique. Eu liber docendi petentium has, labore.</p>
							<p>Etiam falli mentitum id mel, ut mel sumo postulant referrentur. At has minim imperdiet, soluta offendit ocurreret sea an. </p>
							
							<hr />

							<ul class="list-unstyled list-icons">
								<li><i class="fa fa-check"></i> Nobis nemore epicuri pro ea</li>
								<li><i class="fa fa-check"></i> Qui dicunt singulis dissentias an</li>
								<li><i class="fa fa-check"></i> Ea vis diceret constituam</li>
								<li><i class="fa fa-check"></i> Mei no autem idque integre, sumo facilis</li>
								<li><i class="fa fa-check"></i> Est quodsi labitur moderatius an</li>
							</ul>

						</div>
					</div>

				</div>
			</section>
			<!-- /Overview -->





			<!-- Clients -->
			<section id="clients" class="alternate">
				<div class="container">

					<div class="heading-title heading-dotted text-center">
						<h2>Our Clients</h2>
					</div>

					<ul class="row clients-dotted list-inline">
						<li class="col-md-3 col-sm-3 col-6">
							<a href="#">
								<img class="img-fluid" src="demo_files/images/brands/1.jpg" alt="client" />
							</a>
						</li>
						<li class="col-md-3 col-sm-3 col-6">
							<a href="#">
								<img class="img-fluid" src="demo_files/images/brands/2.jpg" alt="client" />
							</a>
						</li>
						<li class="col-md-3 col-sm-3 col-6">
							<a href="#">
								<img class="img-fluid" src="demo_files/images/brands/3.jpg" alt="client" />
							</a>
						</li>
						<li class="col-md-3 col-sm-3 col-6">
							<a href="#">
								<img class="img-fluid" src="demo_files/images/brands/4.jpg" alt="client" />
							</a>
						</li>
						<li class="col-md-3 col-sm-3 col-6">
							<a href="#">
								<img class="img-fluid" src="demo_files/images/brands/5.jpg" alt="client" />
							</a>
						</li>
						<li class="col-md-3 col-sm-3 col-6">
							<a href="#">
								<img class="img-fluid" src="demo_files/images/brands/6.jpg" alt="client" />
							</a>
						</li>
						<li class="col-md-3 col-sm-3 col-6">
							<a href="#">
								<img class="img-fluid" src="demo_files/images/brands/7.jpg" alt="client" />
							</a>
						</li>
						<li class="col-md-3 col-sm-3 col-6">
							<a href="#">
								<img class="img-fluid" src="demo_files/images/brands/8.jpg" alt="client" />
							</a>
						</li>
					</ul>

				</div>
			</section>
			<!-- /Clients -->




			<!-- CONTACT -->
			<section id="contact">
				<div class="container">

					<header class="text-center mb-60">
						<h2>Contact Us</h2>
						<p class="lead font-lato">Lorem ipsum dolor sit amet adipiscium elit</p>
						<hr />
					</header>


					<div class="row">

						<!-- FORM -->
						<div class="col-md-8 col-sm-8">

							<h3>Drop us a line or just say <strong><em>Hello!</em></strong></h3>

							
							<!--
								MESSAGES
								
									How it works?
									The form data is posted to php/contact.php where the fields are verified!
									php.contact.php will redirect back here and will add a hash to the end of the URL:
										#alert_success 		= email sent
										#alert_failed		= email not sent - internal server error (404 error or SMTP problem)
										#alert_mandatory	= email not sent - required fields empty
										Hashes are handled by assets/js/contact.js
									Form data: required to be an array. Example:
										contact[email][required]  WHERE: [email] = field name, [required] = only if this field is required (PHP will check this)
										Also, add `required` to input fields if is a mandatory field. 
										Example: <input required type="email" value="" class="form-control" name="contact[email][required]">
									PLEASE NOTE: IF YOU WANT TO ADD OR REMOVE FIELDS (EXCEPT CAPTCHA), JUST EDIT THE HTML CODE, NO NEED TO EDIT php/contact.php or javascript
												 ALL FIELDS ARE DETECTED DINAMICALY BY THE PHP
									WARNING! Do not change the `email` and `name`!
												contact[name][required] 	- should stay as it is because PHP is using it for AddReplyTo (phpmailer)
												contact[email][required] 	- should stay as it is because PHP is using it for AddReplyTo (phpmailer)
							-->

							<!-- Alert Success -->
							<div id="alert_success" class="alert alert-success mb-30">
								<button type="button" class="close" data-dismiss="alert" aria-hidden="true">&times;</button>
								<strong>Thank You!</strong> Your message successfully sent!
							</div><!-- /Alert Success -->


							<!-- Alert Failed -->
							<div id="alert_failed" class="alert alert-danger mb-30">
								<button type="button" class="close" data-dismiss="alert" aria-hidden="true">&times;</button>
								<strong>[SMTP] Error!</strong> Internal server error!
							</div><!-- /Alert Failed -->


							<!-- Alert Mandatory -->
							<div id="alert_mandatory" class="alert alert-danger mb-30">
								<button type="button" class="close" data-dismiss="alert" aria-hidden="true">&times;</button>
								<strong>Sorry!</strong> You need to complete all mandatory (*) fields!
							</div><!-- /Alert Mandatory -->


							<form action="php/contact.php" method="post" enctype="multipart/form-data">
								<fieldset>
									<input type="hidden" name="action" value="contact_send" />

									<div class="row">
											<div class="col-md-4">
												<label for="contact:name">Full Name *</label>
												<input required type="text" value="" class="form-control" name="contact[name][required]" id="contact:name">
											</div>
											<div class="col-md-4">
												<label for="contact:email">E-mail Address *</label>
												<input required type="email" value="" class="form-control" name="contact[email][required]" id="contact:email">
											</div>
											<div class="col-md-4">
												<label for="contact:phone">Phone</label>
												<input type="text" value="" class="form-control" name="contact[phone]" id="contact:phone">
											</div>
									</div>
									<div class="row">
											<div class="col-md-8">
												<label for="contact:subject">Subject *</label>
												<input required type="text" value="" class="form-control" name="contact[subject][required]" id="contact:subject">
											</div>
											<div class="col-md-4">
												<label for="contact_department">Department</label>
												<select class="form-control pointer" name="contact[department]">
													<option value="">--- Select ---</option>
													<option value="Marketing">Marketing</option>
													<option value="Webdesign">Webdesign</option>
													<option value="Architecture">Architecture</option>
												</select>
											</div>
									</div>
									<div class="row">
											<div class="col-md-12">
												<label for="contact:message">Message *</label>
												<textarea required maxlength="10000" rows="8" class="form-control" name="contact[message]" id="contact:message"></textarea>
											</div>
									</div>
									<div class="row">
											<div class="col-md-12">
												<label for="contact:attachment">File Attachment</label>

												<!-- custom file upload -->
												<input class="custom-file-upload" type="file" id="file" name="contact[attachment]" id="contact:attachment" data-btn-text="Select a File" />
												<small class="text-muted block">Max file size: 10Mb (zip/pdf/jpg/png)</small>

											</div>
									</div>

								</fieldset>

								<div class="row">
									<div class="col-md-12">
										<button type="submit" class="btn btn-primary"><i class="fa fa-check"></i> SEND MESSAGE</button>
									</div>
								</div>
							</form>

						</div>
						<!-- /FORM -->


						<!-- INFO -->
						<div class="col-md-4 col-sm-4">

							<h2>Visit Us</h2>

							<!-- 
							Available heights
								h-100
								h-150
								h-200
								h-250
								h-300
								h-350
								h-400
								h-450
								h-500
								h-550
								h-600
							-->
							<div id="map2" class="h-400 grayscale"></div>

							<hr />

							<p>
								<span class="block"><strong><i class="fa fa-map-marker"></i> Address:</strong> Street Name, City Name, Country</span>
								<span class="block"><strong><i class="fa fa-phone"></i> Phone:</strong> <a href="tel:1800-555-1234">1800-555-1234</a></span>
								<span class="block"><strong><i class="fa fa-envelope"></i> Email:</strong> <a href="mailto:mail@yourdomain.com">mail@yourdomain.com</a></span>
							</p>

						</div>
						<!-- /INFO -->

					</div>

				</div>
			</section>
			<!-- /CONTACT -->




			<!-- FOOTER -->
			<footer id="footer">
				<div class="container">


					<div class="row">

						<!-- col #1 -->
						<div class="col-md-8">

							<h3 class="letter-spacing-1">WHY US?</h3>

							<!-- Small Description -->
							<p>
								Lorem ipsum dolor sit amet, consectetur adipiscing elit. Curabitur imperdiet hendrerit volutpat. Sed in nunc nec ligula consectetur mollis in vel justo. Vestibulum ante ipsum. Lorem ipsum dolor sit amet, consectetur adipiscing elit. Curabitur imperdiet hendrerit volutpat.
							</p>
							<h2>(800) 123-4567</h2>
						</div>
						<!-- /col #1 -->

						<!-- col #2 -->
						<div class="col-md-4">
							<h3 class="letter-spacing-1">KEEP IN TOUCH</h3>

							<!-- Newsletter Form -->
							<p>Subscribe to Our Newsletter to get Important News & Offers</p>

							<form class="validate" action="php/newsletter.php" method="post" data-success="Subscribed! Thank you!" data-toastr-position="bottom-right">
								<div class="input-group">
									<span class="input-group-addon"><i class="fa fa-envelope"></i></span>
									<input type="email" id="email" name="email" class="form-control required" placeholder="Enter your Email">
									<span class="input-group-btn">
										<button class="btn btn-success" type="submit">Subscribe</button>
									</span>
								</div>
							</form>
							<!-- /Newsletter Form -->


						</div>
						<!-- /col #2 -->

					</div>


				</div>

				<div class="copyright">
					<div class="container">
						<ul class="float-right m-0 list-inline mobile-block">
							<li><a href="#">Terms &amp; Conditions</a></li>
							<li>&bull;</li>
							<li><a href="#">Privacy</a></li>
						</ul>
						&copy; All Rights Reserved, Company LTD
					</div>
				</div>

			</footer>
			<!-- /FOOTER -->

		</div>
		<!-- /wrapper -->


		<!-- SCROLL TO TOP -->
		<a href="#" id="toTop"></a>


		<!-- PRELOADER -->
		<div id="preloader">
			<div class="inner">
				<span class="loader"></span>
			</div>
		</div><!-- /PRELOADER -->


		<!-- JAVASCRIPT FILES -->
		<script>var plugin_path = 'assets/plugins/';</script>
		<script src="assets/plugins/jquery/jquery-3.3.1.min.js"></script>

		<script src="assets/js/scripts.js"></script>
		
		<!-- STYLESWITCHER - REMOVE -->
		<script async src="demo_files/styleswitcher/styleswitcher.js"></script>

		<!-- REVOLUTION SLIDER -->
		<script src="assets/plugins/slider.revolution/js/jquery.themepunch.tools.min.js"></script>
		<script src="assets/plugins/slider.revolution/js/jquery.themepunch.revolution.min.js"></script>
		<script src="assets/js/view/demo.revolution_slider.js"></script>

		<!-- PAGELEVEL SCRIPTS -->
		<script src="assets/js/contact.js"></script>

		<!-- 
			GMAP.JS 
			http://hpneo.github.io/gmaps/
		-->
		<script src="//maps.google.com/maps/api/js?key=AIzaSyCqCn84CgZN6o1Xc3P4dM657HIxkX3jzPY"></script>
		<script src="assets/plugins/gmaps.js"></script>
		<script>

			jQuery(document).ready(function(){

				/**
					@BASIC GOOGLE MAP
				**/
				var map2 = new GMaps({
					div: '#map2',
					lat: -12.043333,
					lng: -77.028333,
					scrollwheel: false
				});

				var marker = map2.addMarker({
					lat: -12.043333,
					lng: -77.028333,
					title: 'Company, Inc.'
				});

			});

		</script>
	</body>
</html>
© 2021 GitHub, Inc.
Terms
Privacy
Security
Status
Docs
Contact GitHub
Pricing
API
Training
Blog
About
 You signed in with another tab or window. Reload to refresh your session.
