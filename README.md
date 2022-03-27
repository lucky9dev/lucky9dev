- 👋 Hi, I’m @lucky9dev
- 👀 I’m interested in ...
- 🌱 I’m currently learning ...
- 💞️ I’m looking to collaborate on ...
- 📫 How to reach me ...

<!---
lucky9dev/lucky9dev is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->
<!DOCTYPE html>
<html lang="en">

<head>
	<!-- Meta -->
	<meta charset="utf-8">
	<meta http-equiv="X-UA-Compatible" content="IE=edge">
	<meta name="viewport" content="width=device-width, initial-scale=1.0">
	<meta name="description" content="">
	<meta name="keywords" content="">
	<meta name="author" content="Awaiken Theme">
	<!-- Page Title -->
	<title>Read Me</title>
	<!-- Google Fonts css-->
	<link href="https://fonts.googleapis.com/css?family=Berkshire+Swash%7CRoboto:300,400,400i,500,500i,700,700i,900"
		rel="stylesheet">
	<!-- Bootstrap css -->
	<link href="css/bootstrap.min.css" rel="stylesheet" media="screen">
	<!-- Font Awesome icon css-->
	<link href="css/font-awesome.min.css" rel="stylesheet" media="screen">
	<link href="css/flaticon.css" rel="stylesheet" media="screen">
	<!-- Swiper's CSS -->
	<link rel="stylesheet" href="css/swiper.min.css">
	<!-- Animated css -->
	<link href="css/animate.css" rel="stylesheet">
	<!-- Magnific Popup CSS -->
	<link href="css/magnific-popup.css" rel="stylesheet">
	<!-- Animation Headline CSS -->
	<link href="css/animation-headline.css" rel="stylesheet">
	<!-- Slick nav css -->
	<link rel="stylesheet" href="css/slicknav.css">
	<!-- Main custom css -->
	<link href="css/custom.css" rel="stylesheet" media="screen">
	<link href="css/particle.css" rel="stylesheet" media="screen">

	<link rel="shortcut icon" href="./images/image.png" type="image/x-icon">
	<!-- HTML5 shim and Respond.js for IE8 support of HTML5 elements and media queries -->
	<!-- WARNING: Respond.js doesn't work if you view the page via file:// -->
	<!--[if lt IE 9]>
      <script src="https://oss.maxcdn.com/html5shiv/3.7.2/html5shiv.min.js"></script>
      <script src="https://oss.maxcdn.com/respond/1.4.2/respond.min.js"></script>
    <![endif]-->
  <script>
    const personal_Info = {
      first_name: "Terry",
      last_name: "Milam",
      introduce: "An experienced Full Stack Web Developer who has the strengths are in giving realistic promises, being responsive and responsible, concentrating on business needs and communications.",
      based_on: "Henry, TN",
      email: "toptowermilan@gmail.com",
      skype_id: "x0x0x0x0x0x0x0",
      contact_number: "7316134796",
      links: {
        resume_link:"",
        skype_link:"",
        linkedin_link:"",
      },
    }
    const my_exp = {
      education: {
        name: "The University of Tennessee",
        date_from: 2010,
        date_to: 2014,
        degree: "Bechalor's Degree",
        field: "Computer Science"
      },
      career: {
        name: "The University of Tennessee",
        date_from: 2010,
        date_to: 2014,
        role: "Bechalor's Degree",
        
      },
      skills: [
        {title:"SCSS & SASS", exp:5},
        {title:"JavaScript", exp:5},
        {title:"ES5 & ES6", exp:5},
        {title:"Typescript", exp:5},
        {title:"React", exp:5},
        {title:"Redux-saga", exp:5},
        {title:"NodeJS", exp:5},
        {title:"Socket.io", exp:5},
        {title:"ExpressJS", exp:5},
        {title:"MySQL & PostgreSQL", exp:5},
        {title:"MongoDB", exp:5},
        {title:"AWS", exp:5},
      ]
    }
    const myservices = [
      "Front-End Development", 
      "Web Development", 
      "Pixel-Perfect & Responsible", 
      "Highly Scalable", 
      "Clean Coding", 
      "24 X 7 Support"
    ]
    const portfolio = {

    }
    text_out = (strlist) => {
      if(typeof(strlist) === "object")
        document.write(strlist.join(' '))
      else
        document.write(strlist)
    }
  </script>
</head>

<body data-spy="scroll" data-target="#main-navbar" data-offset="75">

	<!-- Preloader starts -->
	<div class="preloader">
		<div class="loader">
			<div class="diamond"></div>
			<div class="diamond"></div>
			<div class="diamond"></div>
		</div>
	</div>
	<!-- Preloader Ends -->

	<!-- Header Section Start -->
	<header class="header">
		<nav class="navbar navbar-expand-md navbar-light fixed-top" id="main-navbar">
			<div class="container">
				<!-- Navbar Brand start -->
				<a class="navbar-brand" href="#">
					<h1><span><script>text_out(personal_Info.first_name)</script></span> <script>text_out(personal_Info.last_name)</script></h1>
				</a>
				<!-- Navbar Brand end -->

				<!-- Navigation Starts -->
				<ul class="navbar-nav ml-auto" id="main-menu">
					<li class="nav-item"><a class="nav-link active" href="#home">Home</a></li>
					<li class="nav-item"><a class="nav-link" href="#about">About</a></li>
					<li class="nav-item"><a class="nav-link" href="#services">Services</a></li>
					<li class="nav-item"><a class="nav-link" href="#resume">Resume</a></li>
					<li class="nav-item"><a class="nav-link" href="#portfolio">Portfolio</a></li>
					<li class="nav-item"><a class="nav-link" href="#contact">Contact</a></li>
				</ul>
				<!-- Navigation Ends -->

				<div class="navbar-toggle"></div>
				<div id="responsive-menu"></div>
			</div>
		</nav>
	</header>
	<!-- Header Section End -->

	<!-- Banner Slider Section starts -->
	<!-- <div id="particles">
		<div id="webcoderskull">
		</div>
	</div> -->
	<div class="banner" id="home">

		<div class="container">
			<div class="row">
				<div class="col-lg-6">
					<!-- Banner Content Start -->
					<div class="banner-content">
						<h2 class="cd-headline clip">
							<span class="before-heading">Hello , world! </span>
							<span class="cd-words-wrapper">
								<b>Full Stack Developer</b>
								<b class="is-visible">Front-End Developer</b>
								<b >React Developer</b>
							</span>
						</h2>
						<p><script>text_out(personal_Info.introduce)</script></p>

						<a href="https://drive.google.com/file/d/1J2SAul2VDAkTy73Hke_AWSwmeww93tdX/view?usp=sharing" class="btn-download">Download Resume</a>
					</div>
					<!-- Banner Content End -->
				</div>
				<div class="col-lg-6" style="display: flex; justify-content: end; align-items:center;">
					<img src="./images/about.png" alt="" style="width: 50%;border-radius: 10%;">
				</div>
			</div>
		</div>
	</div>
	<!-- Banner Slider Section ends -->

	<!-- About us Section Starts -->
	<section class="about-us" id="about">
		<div class="container">
			<div class="row">
				<div class="col-md-12">
					<!-- Section title start -->
					<div class="section-title">
						<h2>About Me</h2>
						<p>Professional Profile - There Is All About Me</p>
					</div>
					<!-- Section title end -->
				</div>
			</div>

			<div class="row">
				<div class="col-lg-4" style="display: flex;align-items: end;">
					<!-- About image start -->
					<div class="about-image wow fadeInLeft" data-wow-delay="0.3s">
						<img src="images/image.png" alt="" />
					</div>
					<!-- About image end -->
				</div>

				<div class="col-lg-8" style="display: flex;align-items: center;">
					<!-- About Content start -->
					<div class="about-content wow fadeInUp" data-wow-delay="0.8s">
						<h3>I'm <script>text_out([personal_Info.first_name, personal_Info.last_name])</script></h3>
						<p>A talented full-stack developer with <script>let curruent_date = new Date(); text_out(curruent_date.getFullYear()-2014)</script>+ years of well-rounded experience in web development,	object-oriented and user-centered front-end development. Motivated designer and developer with experience creating custom websites through many fields' skills and having Strong collaboration skills and proven history of application development.</p>

						<p>Am passionate about solving challenging problems that others find difficult or
							impossible. Providing technical, creative, and business insights to all projects I work on.
						</p>

						<ul>
							<!-- <li><i class="flaticon-calendar"></i><b>Date of birth:</b> April 2</li> -->
							<li><i class="flaticon-freelance"></i><b>Freelance:</b>
                Available
              </li>
							<li><i class="flaticon-placeholder"></i><b>Based on:</b> 
                <script>
                  text_out(personal_Info.based_on)
                </script>
              </li>
							<li><i class="flaticon-email"></i><b>Email:</b> 
                <script>
                  text_out(personal_Info.email)
                </script>
              </li>
							<li><i class="flaticon-phone"></i><b>Contact:</b> 
                <script>
                  text_out(personal_Info.contact_number)
                </script>
              </li>
							<li style="width: 100%;"><i class="flaticon-skype"></i><b>Skype:</b> 
                <script>
                  text_out(personal_Info.skype_id)
                </script> 
              </li>
						</ul>
					</div>
					<!-- About Content End -->
				</div>
			</div>
		</div>
	</section>
	<!-- About us Section Ends -->

	<!-- Services Section Starts -->
	<section class="services" id="services">
		<div class="container">
			<div class="row">
				<div class="col-md-12">
					<!-- Section title start -->
					<div class="section-title">
						<h2>My Services</h2>
						<!-- <p>Lorem ipsum dolor sit amet</p> -->
					</div>
					<!-- Section title end -->
				</div>
			</div>

			<div class="row" style="margin-top: 15px;">
				<div class="col-md-4">
					<!-- Service Single Start -->
					<div class="service-single wow fadeInUp" data-wow-delay="0.3s">
						<div class="icon-box">
							<i class="flaticon-idea"></i>
						</div>

						<h3><script>text_out(myservices[0])</script></h3>
						<!-- <p>Lorem ipsum dolor sit amet, consectetur adipisicing elit. Doloribus assumenda voluptas</p> -->
					</div>
					<!-- Service Single End -->
				</div>

				<div class="col-md-4">
					<!-- Service Single Start -->
					<div class="service-single wow fadeInUp" data-wow-delay="0.6s">
						<div class="icon-box">
							<i class="flaticon-translation"></i>
						</div>

						<h3><script>text_out(myservices[1])</script></h3>
						<!-- <p>Lorem ipsum dolor sit amet, consectetur adipisicing elit. Doloribus assumenda voluptas</p> -->
					</div>
					<!-- Service Single End -->
				</div>

				<div class="col-md-4">
					<!-- Service Single Start -->
					<div class="service-single wow fadeInUp" data-wow-delay="0.9s">
						<div class="icon-box">
							<i class="flaticon-controls"></i>
						</div>

						<h3><script>text_out(myservices[2])</script></h3>
						<!-- <p>Lorem ipsum dolor sit amet, consectetur adipisicing elit. Doloribus assumenda voluptas</p> -->
					</div>
					<!-- Service Single End -->
				</div>

				<div class="col-md-4">
					<!-- Service Single Start -->
					<div class="service-single wow fadeInUp" data-wow-delay="1.2s">
						<div class="icon-box">
							<i class="flaticon-growth"></i>
						</div>

						<h3><script>text_out(myservices[3])</script></h3>
						<!-- <p>Lorem ipsum dolor sit amet, consectetur adipisicing elit. Doloribus assumenda voluptas</p> -->
					</div>
					<!-- Service Single End -->
				</div>

				<div class="col-md-4">
					<!-- Service Single Start -->
					<div class="service-single wow fadeInUp" data-wow-delay="1.5s">
						<div class="icon-box">
							<i class="flaticon-quality"></i>
						</div>

						<h3><script>text_out(myservices[4])</script></h3>
						<!-- <p>Lorem ipsum dolor sit amet, consectetur adipisicing elit. Doloribus assumenda voluptas</p> -->
					</div>
					<!-- Service Single End -->
				</div>

				<div class="col-md-4">
					<!-- Service Single Start -->
					<div class="service-single wow fadeInUp" data-wow-delay="1.8s">
						<div class="icon-box">
							<i class="flaticon-support"></i>
						</div>

						<h3><script>text_out(myservices[5])</script></h3>
						<!-- <p>Lorem ipsum dolor sit amet, consectetur adipisicing elit. Doloribus assumenda voluptas</p> -->
					</div>
					<!-- Service Single End -->
				</div>
			</div>
		</div>
	</section>
	<!-- Services Section Ends -->

	<!-- My Resume Section Starts -->
	<section class="my-resume" id="resume">
		<div class="container">
			<div class="row">
				<div class="col-md-12">
					<!-- Section title start -->
					<div class="section-title">
						<h2>My Resume</h2>
						<!-- <p>Lorem ipsum dolor sit amet</p> -->
					</div>
					<!-- Section title end -->
				</div>
			</div>

			<div class="row mb-5 pb-5">
				<div class="col-md-12">
					<div class="experience">
						<h3 class="sub-title"><i class="fa fa-briefcase"></i> Experience</h3>

						<!-- Experience Slider Start -->
						<div class="swiper-container experience-slider">
							<div class="swiper-wrapper">
								<!-- Experience Slide start -->
								<div class="swiper-slide">
									<div class="experience-single">
										<h5>2016 October - 2017 May</h5>
										<h4>Web & App Developer - Freelancer</h4>
										<p>This is an Australian freelance marketplace website, which allows potential employers to post jobs that freelancers can
											then bid to complete.</p>
											<br/>
										<p>At that time, I set out on this path to verify and further improve the skills that I had accumulated up to that point. In the
											process of carrying out several projects, I came to possess excellent knowledge about MVC, CI/CD, and many
											frameworks and Version control systems like GitHub, Bitbucket. I raised my skills to a higher level by boldly
											challenging new projects.</p>
									</div>
								</div>
								<!-- Experience Slide end -->

								<!-- Experience Slide start -->
								<div class="swiper-slide">
									<div class="experience-single">
										<h5>2017 May - 2018 Feburary</h5>
										<h4>Full Stack Developer - GOVTECH Group Inc.</h4>
										<ul>
											<li>Planned, wrote, and debugged mobile and web applications</li>
											<li>Developed and Deployed RESTful API using Node.js/Express</li>
											<li>Gained hands-on expertise in React Hooks, Redux, ES6, TypeScript, MUI, and modern frameworks and Libraries.</li>
											<li>Implemented the payment system, SMS verification, Push Notification, and Social Login.</li>
											<li>Experienced with PostgreSQL, Firebase, and NGINX.</li>
										</ul>
									</div>
								</div>
								<!-- Experience Slide end -->

								<!-- Experience Slide start -->
								<div class="swiper-slide">
									<div class="experience-single">
										<h5>2018 Feburary - 2019 June</h5>
										<h4>Senior Front-end Designer for eCommerce - CodeBlue Australia Inc.</h4>
										<ul>
											<li>Maintained the production site through various production tasks, such as creating functional prototypes for user testing labs and creating landing pages and newsletters with ReactJs and Bootstrap, SCSS.</li>
											<li>Lead the integration of the new eCommerce store redesign using skills containing Shopify, API, ReactJs, NextJs, Tailwind CSS, Payment Integration.</li>
											<li>Built components and set the schedule for all the eCommerce promo materials in IBM WebSphere.</li>
											<li>Implemented Unit Test and End-to-end test.</li>
											<li>Performed the role as a QA Engineer and guarantee the quality of the project including INTERFACE and functions.</li>
										</ul>
									</div>
								</div>
								<!-- Experience Slide end -->

								<!-- Experience Slide start -->
								<div class="swiper-slide">
									<div class="experience-single">
										<h5>2019 June - 2021 November</h5>
										<h4>Senior Full Stack Web Developer - Pullerits Group Inc.</h4>
										<ul>
											<li>Built NFT marketplaces with React and Scss, web3.js, solidity, Solana, smart contracts, Truffle.</li>
											<li>Developed the Trading and Exchange platform.</li>
											<li>Developed the education system: Front-end development with React and Redux, Redux-Saga, TypeScript, and Material-UI and RESTful API with Node.js / Express / MongoDB Implemented socket server to update real-time the status with socket.io and implemented SEO.</li>
											<li>Implemented Search Enginee with Algolia</li>
											<li>Implemented the function to draw the signature to the PDF document on the website.</li>
											<li>Developed features' Prototype for Front-End of Tizzazz with React and Flickty.js.</li>
											<li>Developed a Gambling website that is using CryptoCurrency with high algorithms, great web design skills (React and Redux, SCSS, Tailwind CSS, TypeScript), and Blockchain.</li>
											<li>Designed and Developed the modern landing page with PhotoShop and Figma, SVG, React, CSS, and Optimized the Site Loading Speed to 1/10.</li>
										</ul>
									</div>
								</div>
								<!-- Experience Slide end -->
							</div>

							<!-- Experience Pagination Start -->
							<div class="experience-pagination"></div>
							<!-- Experience Pagination Start -->
						</div>
						<!-- Experience Slider Start -->
					</div>
				</div>

        <!-- Education -->
				<div class="col-md-12">
					<div class="education">
						<h3 class="sub-title"><i class="fa fa-graduation-cap"></i> Education</h3>

						<!-- Education Slider Start -->
						<div class="swiper-container education-slider">
							<div class="swiper-wrapper-1">
								<!-- Experience Slide start -->
								<div class="swiper-slide">
									<div class="experience-single">
										<h5>
                      <script>
                        text_out([
                          my_exp.education.date_from,
                          '-',
                          my_exp.education.date_to,
                        ])
                      </script>
                    </h5>
										<h4>
                      <script>
                        text_out([
                          my_exp.education.degree,
                          '-',
                          my_exp.education.field,
                        ])
                      </script>
                    </h4>
										<p><script>text_out(my_exp.education.name)</script></p>
									</div>
								</div>
								<!-- Experience Slide end -->

							</div>

							<!-- Education Pagination Start -->
							<div class="education-pagination"></div>
							<!-- Education Pagination Start -->
						</div>
						<!-- Education Slider End -->
					</div>
				</div>
			</div>
						
      <!-- Skills -->
			<div class="row">
				<div class="col-md-12">
					<div class="skill">
						<h3 class="sub-title"><i class="fa fa-star-o"></i>Skills and Expertice</h3>

						<!-- Skill Content Start -->
						<div class="skill-content">
							<div class="row">
								<div class="col-md-2">
									<!-- Skill Single Start -->
									<div class="skill-single">
										<h5>React</h5>
										<div class="skill-ratting">
											<i class="fa fa-star"></i>
											<i class="fa fa-star"></i>
											<i class="fa fa-star"></i>
											<i class="fa fa-star"></i>
											<i class="fa fa-star"></i>
										</div>
									</div>
									<!-- Skill Single End -->
								</div>

								<div class="col-md-2">
									<!-- Skill Single Start -->
									<div class="skill-single">
										<h5>Redux</h5>
										<div class="skill-ratting">
											<i class="fa fa-star-o"></i>
											<i class="fa fa-star-o"></i>
											<i class="fa fa-star-o"></i>
											<i class="fa fa-star-o"></i>
											<i class="fa fa-star-o"></i>
										</div>
									</div>
									<!-- Skill Single End -->
								</div>

								<div class="col-md-2">
									<!-- Skill Single Start -->
									<div class="skill-single">
										<h5>NextJs</h5>
										<div class="skill-ratting">
											<i class="fa fa-star-o"></i>
											<i class="fa fa-star-o"></i>
											<i class="fa fa-star-o"></i>
											<i class="fa fa-star-o"></i>
											<i class="fa fa-star-half-o"></i>
										</div>
									</div>
									<!-- Skill Single End -->
								</div>

								<div class="col-md-2">
									<!-- Skill Single Start -->
									<div class="skill-single">
										<h5>NodeJs</h5>
										<div class="skill-ratting">
											<i class="fa fa-star-o"></i>
											<i class="fa fa-star-o"></i>
											<i class="fa fa-star-o"></i>
											<i class="fa fa-star-o"></i>
											<i class="fa fa-star-o"></i>
										</div>
									</div>
									<!-- Skill Single End -->
								</div>

								<div class="col-md-2">
									<!-- Skill Single Start -->
									<div class="skill-single">
										<h5>ExpressJs</h5>
										<div class="skill-ratting">
											<i class="fa fa-star-o"></i>
											<i class="fa fa-star-o"></i>
											<i class="fa fa-star-o"></i>
											<i class="fa fa-star-o"></i>
											<i class="fa fa-star-o"></i>
										</div>
									</div>
									<!-- Skill Single End -->
								</div>

								<div class="col-md-2">
									<!-- Skill Single Start -->
									<div class="skill-single">
										<h5>Bootstrap</h5>
										<div class="skill-ratting">
											<i class="fa fa-star-o"></i>
											<i class="fa fa-star-o"></i>
											<i class="fa fa-star-o"></i>
											<i class="fa fa-star-o"></i>
											<i class="fa fa-star-o"></i>
										</div>
									</div>
									<!-- Skill Single End -->
								</div>

								<div class="col-md-2">
									<!-- Skill Single Start -->
									<div class="skill-single">
										<h5>SCSS</h5>
										<div class="skill-ratting">
											<i class="fa fa-star-o"></i>
											<i class="fa fa-star-o"></i>
											<i class="fa fa-star-o"></i>
											<i class="fa fa-star-o"></i>
											<i class="fa fa-star-half-o"></i>
										</div>
									</div>
									<!-- Skill Single End -->
								</div>

								<div class="col-md-2">
									<!-- Skill Single Start -->
									<div class="skill-single">
										<h5>Material-UI</h5>
										<div class="skill-ratting">
											<i class="fa fa-star-o"></i>
											<i class="fa fa-star-o"></i>
											<i class="fa fa-star-o"></i>
											<i class="fa fa-star-o"></i>
											<i class="fa fa-star-o"></i>
										</div>
									</div>
									<!-- Skill Single End -->
								</div>

								<div class="col-md-2">
									<!-- Skill Single Start -->
									<div class="skill-single">
										<h5>TailwindCss</h5>
										<div class="skill-ratting">
											<i class="fa fa-star-o"></i>
											<i class="fa fa-star-o"></i>
											<i class="fa fa-star-o"></i>
											<i class="fa fa-star-o"></i>
											<i class="fa fa-star-half-o"></i>
										</div>
									</div>
									<!-- Skill Single End -->
								</div>

								<div class="col-md-2">
									<!-- Skill Single Start -->
									<div class="skill-single">
										<h5>MongoDB</h5>
										<div class="skill-ratting">
											<i class="fa fa-star-o"></i>
											<i class="fa fa-star-o"></i>
											<i class="fa fa-star-o"></i>
											<i class="fa fa-star-o"></i>
											<i class="fa fa-star-o"></i>
										</div>
									</div>
									<!-- Skill Single End -->
								</div>
								
								<div class="col-md-2">
									<!-- Skill Single Start -->
									<div class="skill-single">
										<h5>Solidity</h5>
										<div class="skill-ratting">
											<i class="fa fa-star-o"></i>
											<i class="fa fa-star-o"></i>
											<i class="fa fa-star-o"></i>
											<i class="fa fa-star-o"></i>
											<i class="fa fa-star-o"></i>
										</div>
									</div>
									<!-- Skill Single End -->
								</div>

								<div class="col-md-2">
									<!-- Skill Single Start -->
									<div class="skill-single">
										<h5>Web3Js</h5>
										<div class="skill-ratting">
											<i class="fa fa-star-o"></i>
											<i class="fa fa-star-o"></i>
											<i class="fa fa-star-o"></i>
											<i class="fa fa-star-o"></i>
											<i class="fa fa-star-o"></i>
										</div>
									</div>
									<!-- Skill Single End -->
								</div>
							</div>
						</div>
						<!-- Skill Content End -->
					</div>
				</div>

			</div>
		</div>
	</section>
	<!-- My Resume Section Ends -->

	<!-- Portfolio Section Starts -->
	<section class="portfolio" id="portfolio">
		<div class="container">
			<div class="row">
				<div class="col-md-12">
					<!-- Section title start -->
					<div class="section-title">
						<h2>Portfolio</h2>
						<p>See Some Of My Previous Works</p>
					</div>
					<!-- Section title end -->
				</div>
			</div>

			

			<div class="row portfolio-boxes">
				<!-- Single Portfolio starts -->
				<div class="col-md-4 col-sm-6 col-xs-12 portfolio-box">
					<div class="single-portfolio">
						<a href="#popup-1" class="has-popup">
							<img src="images/houzz/0.jpg" class="Portfolio Image" alt="" />
							<div class="single-portfolio-overlay">
								<h3>MERN E-COMMERCE</h3>
							</div>
						</a>
					</div>
					<div id="popup-1" class="popup-box mfp-fade mfp-hide">
						<div class="content">
							<div class="image">
								<div id="gallery" class="carousel slide" data-ride="carousel">
									<ul class="carousel-indicators">
									  <li data-target="#gallery" data-slide-to="0" class="active"></li>
									  <li data-target="#gallery" data-slide-to="1"></li>
									  <li data-target="#gallery" data-slide-to="2"></li>
									  <li data-target="#gallery" data-slide-to="3"></li>
									</ul>
									<div class="carousel-inner">
									  <div class="carousel-item active">
										<img src="images/houzz/0.jpg" alt="Error!"> 
									  </div>
									  <div class="carousel-item">
										<img src="images/houzz/1.jpg" alt="Error!"> 
									  </div>
									  <div class="carousel-item">
										<img src="images/houzz/2.jpg" alt="Error!"> 
									  </div>
									  <div class="carousel-item">
										<img src="images/houzz/3.jpg" alt="Error!"> 
									  </div>
									</div>
									<a class="carousel-control-prev" href="#gallery" data-slide="prev">
									  <span class="carousel-control-prev-icon"></span>
									</a>
									<a class="carousel-control-next" href="#gallery" data-slide="next">
									  <span class="carousel-control-next-icon"></span>
									</a>
								  </div>
							</div>
							<div class="desc">
								<a href="https://houzz.com"><h4>->  Houzz  <-</h4></a>
								<p>
									This is an American website, online community and software for architecture; interior design and decorating; landscape design and home improvement.
								</p>
								<p>Skills : React.js , Typescript , Bootstrap , API , Node.js , Express , MongoDB</p>
							</div>
						</div>
					</div>
				</div>
				<!-- Single Portfolio Ends -->

				<!-- Single Portfolio starts -->
				<div class="col-md-4 col-sm-6 col-xs-12 portfolio-box">
					<div class="single-portfolio">
						<a href="#popup-2" class="has-popup">
							<img src="images/betnomi/0.jpg" class="Portfolio Image" alt="" />
							<div class="single-portfolio-overlay">
								<h3>GAMBLING SITE</h3>
							</div>
						</a>
					</div>
					<div id="popup-2" class="popup-box mfp-fade mfp-hide">
						<div class="content">
							<div class="image">
								<div id="gallery" class="carousel slide" data-ride="carousel">
									<ul class="carousel-indicators">
									  <li data-target="#gallery" data-slide-to="0" class="active"></li>
									  <li data-target="#gallery" data-slide-to="1"></li>
									  <li data-target="#gallery" data-slide-to="2"></li>
									  <li data-target="#gallery" data-slide-to="3"></li>
									</ul>
									<div class="carousel-inner">
									  <div class="carousel-item active">
										<img src="images/betnomi/0.jpg" alt="Error!"> 
									  </div>
									  <div class="carousel-item">
										<img src="images/betnomi/1.jpg" alt="Error!"> 
									  </div>
									  <div class="carousel-item">
										<img src="images/betnomi/2.jpg" alt="Error!"> 
									  </div>
									  <div class="carousel-item">
										<img src="images/betnomi/3.jpg" alt="Error!"> 
									  </div>
									</div>
									<a class="carousel-control-prev" href="#gallery" data-slide="prev">
									  <span class="carousel-control-prev-icon"></span>
									</a>
									<a class="carousel-control-next" href="#gallery" data-slide="next">
									  <span class="carousel-control-next-icon"></span>
									</a>
								  </div>
							</div>
							<div class="desc">
								<a href="https://betnomi.com"><h4>->  Betnomi  <-</h4></a>
								<p>
									Betnomi is a Gambling website that is powered by Blockchain.
								</p>
								<p>Skills : Typescript , ReactJs , Tailwind CSS , NodeJs , Express , API , MongoDB , Blockchain</p>
							</div>
						</div>
					</div>
				</div>
				<!-- Single Portfolio Ends -->

				<!-- Single Portfolio starts -->
				<div class="col-md-4 col-sm-6 col-xs-12 portfolio-box">
					<div class="single-portfolio">
						<a href="#popup-3" class="has-popup">
							<img src="images/i4vision/0.jpg" class="Portfolio Image" alt="" />
							<div class="single-portfolio-overlay">
								<h3>ADVERT WEBSITE</h3>
							</div>
						</a>
					</div>
					<div id="popup-3" class="popup-box mfp-fade mfp-hide">
						<div class="content">
							<div class="image">
								<div id="gallery" class="carousel slide" data-ride="carousel">
									<ul class="carousel-indicators">
									  <li data-target="#gallery" data-slide-to="0" class="active"></li>
									  <li data-target="#gallery" data-slide-to="1"></li>
									  <li data-target="#gallery" data-slide-to="2"></li>
									  <li data-target="#gallery" data-slide-to="3"></li>
									  <li data-target="#gallery" data-slide-to="4"></li>
									</ul>
									<div class="carousel-inner">
									  <div class="carousel-item active">
										<img src="images/i4vision/0.jpg" alt="Error!"> 
									  </div>
									  <div class="carousel-item">
										<img src="images/i4vision/1.jpg" alt="Error!"> 
									  </div>
									  <div class="carousel-item">
										<img src="images/i4vision/2.jpg" alt="Error!"> 
									  </div>
									  <div class="carousel-item">
										<img src="images/i4vision/3.jpg" alt="Error!"> 
									  </div>
									  <div class="carousel-item">
										<img src="images/i4vision/4.jpg" alt="Error!"> 
									  </div>
									</div>
									<a class="carousel-control-prev" href="#gallery" data-slide="prev">
									  <span class="carousel-control-prev-icon"></span>
									</a>
									<a class="carousel-control-next" href="#gallery" data-slide="next">
									  <span class="carousel-control-next-icon"></span>
									</a>
								  </div>
							</div>
							<div class="desc">
								<a href="https://i4vision.de"><h4>->  I4vision  <-</h4></a>
								<p>
									i4Vision.Visualisation with interactivity. i4Vision. GOERING-Icon_i4vision. i4Vision makes information accessible on video panels
								</p>
								<p>Skills : Laravel , MySQL , Bootstrap </p>
							</div>
						</div>
					</div>
				</div>
				<!-- Single Portfolio Ends -->

				<!-- Single Portfolio starts -->
				<div class="col-md-4 col-sm-6 col-xs-12 portfolio-box">
					<div class="single-portfolio">
						<a href="#popup-4" class="has-popup">
							<img src="images/starkasino/0.jpg" class="Portfolio Image" alt="" />
							<div class="single-portfolio-overlay">
								<h3>GAMBLING SITE</h3>
							</div>
						</a>
					</div>
					<div id="popup-4" class="popup-box mfp-fade mfp-hide">
						<div class="content">
							<div class="image">
								<div id="gallery" class="carousel slide" data-ride="carousel">
									<ul class="carousel-indicators">
									  <li data-target="#gallery" data-slide-to="0" class="active"></li>
									  <li data-target="#gallery" data-slide-to="1"></li>
									  <li data-target="#gallery" data-slide-to="2"></li>
									  <li data-target="#gallery" data-slide-to="3"></li>
									</ul>
									<div class="carousel-inner">
									  <div class="carousel-item active">
										<img src="images/starkasino/0.jpg" alt="Error!"> 
									  </div>
									  <div class="carousel-item">
										<img src="images/starkasino/1.jpg" alt="Error!"> 
									  </div>
									  <div class="carousel-item">
										<img src="images/starkasino/2.jpg" alt="Error!"> 
									  </div>
									  <div class="carousel-item">
										<img src="images/starkasino/3.jpg" alt="Error!"> 
									  </div>
									</div>
									<a class="carousel-control-prev" href="#gallery" data-slide="prev">
									  <span class="carousel-control-prev-icon"></span>
									</a>
									<a class="carousel-control-next" href="#gallery" data-slide="next">
									  <span class="carousel-control-next-icon"></span>
									</a>
								  </div>
							</div>
							<div class="desc">
								<a href="https://starkasino.io"><h4>->  Starkasino  <-</h4></a>
								<p>
									Best Online Casino Slot & Live Games
								</p>
								<p> Skills : React and Socket , NodeJs , ExpressJs , MongoDB , RESTful API </p>
							</div>
						</div>
					</div>
				</div>
				<!-- Single Portfolio Ends -->

				<!-- Single Portfolio starts -->
				<div class="col-md-4 col-sm-6 col-xs-12 portfolio-box">
					<div class="single-portfolio">
						<a href="#popup-5" class="has-popup">
							<img src="images/bullieverisland/0.jpg" class="Portfolio Image" alt="" />
							<div class="single-portfolio-overlay">
								<h3>NFT WEBSITE</h3>
							</div>
						</a>
					</div>
					<div id="popup-5" class="popup-box mfp-fade mfp-hide">
						<div class="content">
							<div class="image">
								<div id="gallery" class="carousel slide" data-ride="carousel">
									<ul class="carousel-indicators">
									  <li data-target="#gallery" data-slide-to="0" class="active"></li>
									  <li data-target="#gallery" data-slide-to="1"></li>
									  <li data-target="#gallery" data-slide-to="2"></li>
									  <li data-target="#gallery" data-slide-to="3"></li>
									</ul>
									<div class="carousel-inner">
										<div class="carousel-item active">
										<img src="images/bullieverisland/0.jpg" alt="Error!"> 
										</div>
									  <div class="carousel-item">
										<img src="images/bullieverisland/1.jpg" alt="Error!"> 
									  </div>
									  <div class="carousel-item">
										<img src="images/bullieverisland/2.jpg" alt="Error!"> 
									  </div>
									  <div class="carousel-item">
										<img src="images/bullieverisland/3.jpg" alt="Error!"> 
									  </div>
									</div>
									<a class="carousel-control-prev" href="#gallery" data-slide="prev">
									  <span class="carousel-control-prev-icon"></span>
									</a>
									<a class="carousel-control-next" href="#gallery" data-slide="next">
									  <span class="carousel-control-next-icon"></span>
									</a>
								  </div>
							</div>
							<div class="desc">
								<a href="https://bullieverisland.com"><h4>->  Citizens Of Bulliever Island  <-</h4></a>
								<p>
									This NFT website means that 'Bulliever Island is a fantasy Metaverse Island where you can play to earn, have fun and make new friends.'
								</p>
							</div>
						</div>
					</div>
				</div>
				<!-- Single Portfolio Ends -->

				<!-- Single Portfolio starts -->
				<div class="col-md-4 col-sm-6 col-xs-12 portfolio-box">
					<div class="single-portfolio">
						<a href="#popup-6" class="has-popup">
							<img src="images/ascd/1.png" class="Portfolio Image" alt="" />
							<div class="single-portfolio-overlay">
								<h3>Passionate Community Website</h3>
							</div>
						</a>
					</div>
					<div id="popup-6" class="popup-box mfp-fade mfp-hide">
						<div class="content">
							<div class="image">
								<div id="gallery" class="carousel slide" data-ride="carousel">
									<ul class="carousel-indicators">
									  <li data-target="#gallery" data-slide-to="0" class="active"></li>
									  <li data-target="#gallery" data-slide-to="1"></li>
									  <li data-target="#gallery" data-slide-to="2"></li>
									  <li data-target="#gallery" data-slide-to="3"></li>
									  <li data-target="#gallery" data-slide-to="4"></li>
									</ul>
									<div class="carousel-inner">
									  <div class="carousel-item active">
										<img src="images/ascd/1.png" alt="Error!"> 
									  </div>
									  <div class="carousel-item">
										<img src="images/ascd/2.png" alt="Error!"> 
									  </div>
									  <div class="carousel-item">
										<img src="images/ascd/3.png" alt="Error!"> 
									  </div>
									  <div class="carousel-item">
										<img src="images/ascd/4.png" alt="Error!"> 
									  </div>
									  <div class="carousel-item">
										<img src="images/ascd/5.png" alt="Error!"> 
									  </div>
									</div>
									<a class="carousel-control-prev" href="#gallery" data-slide="prev">
									  <span class="carousel-control-prev-icon"></span>
									</a>
									<a class="carousel-control-next" href="#gallery" data-slide="next">
									  <span class="carousel-control-next-icon"></span>
									</a>
								  </div>
							</div>
							<div class="desc">
								<a href="https://ascd.org"><h4>->  ASCD  <-</h4></a>
								<p>
									ASCD empowers educators to achieve excellence in learning, teaching, and leading so that every child is healthy, safe, engaged, supported, and challenged.
								</p>
								<p>
									This is developed with React and Redux , Material-UI 5 , Algolia , React Instant Search Engine.
								</p>
							</div>
						</div>
					</div>
				</div>
				<!-- Single Portfolio Ends -->
		</div>
	</section>
	<!-- Portfolio Section Ends -->


	<!-- Contact us Section Starts -->
	<section class="contactus" id="contact">
		<div class="container">
			<div class="row">
				<div class="col-md-12">
					<!-- Section title start -->
					<div class="section-title">
						<h2>Get in touch</h2>
						<p>Feel free to drop me a line - Contact me</p>
					</div>
					<!-- Section title end -->
				</div>
			</div>
		</div>
	</section>
	<!-- Contact us Section Ends -->

	<!-- Contact Information Section Starts -->
	<div class="contact-information">
		<div class="container">
			<div class="row">

        <div class="col-lg-4">
					<!-- Contact info single start -->
					<div class="contact-info-single wow fadeInUp" data-wow-delay="0.9s">
						<h3>Email</h3>
						<p>
              <script>
                text_out(personal_Info.email)
              </script>
            </p>
					</div>
					<!-- Contact info single end -->
				</div>

        <div class="col-lg-4">
					<!-- Contact info single start -->
					<div class="contact-info-single wow fadeInUp" data-wow-delay="0.3s">
						<h3>Number</h3>
						<p>
              <script>
                text_out(personal_Info.contact_number)
              </script> </p>
					</div>
					<!-- Contact info single end -->
				</div>

        <div class="col-lg-4">
					<!-- Contact info single start -->
					<div class="contact-info-single wow fadeInUp" data-wow-delay="0.6s">
						<h3>Skype</h3>
						<p>
              <script>
                text_out(personal_Info.skype_id)
              </script> 
            </p>
					</div>
					<!-- Contact info single end -->
				</div>
				
			</div>
		</div>
	</div>
	<!-- Contact Information Section Ends -->

	<!-- Footer Section starts -->
	<footer class="main-footer">
		<div class="container">
			<div class="row">
				<div class="col-md-12">
					<!-- Footer Logo start -->
					<div class="footer-logo">
						<h1><span><script>text_out(personal_Info.first_name)</script></span> <script>text_out(personal_Info.last_name)</script></h1>
					</div>
					<!-- Footer Logo end -->

					<!-- Footer About start -->
					<div class="footer-about">
						<p>An experienced Full Stack Developer who has the strengths are in giving realistic promises, being responsive and responsible, concentrating on business needs and communications.</p>
					</div>
					<!-- Footer About end -->

					<!-- Footer Social Link start -->
					<div class="footer-social">
            <a href="https://t.me/@golden_t_s"><i class="fa fa-telegram"></i></a>
						<a href="mailto:golden.peach.ts@gmail.com"><i class="fa fa-envelope"></i></a>
						<a href="https://join.skype.com/invite/x9uVjXmB5LRY"><i class="fa fa-skype"></i></a>
					</div>
					<!-- Footer Social Link end -->

					<!-- Footer Copyright start -->
					<div class="footer-copyright">
						<p>Copyright &copy; Untitled. All rights reserved. Design By <b><script>text_out([personal_Info.first_name, personal_Info.last_name])</script></b></p>
					</div>
					<!-- Footer Copyright end -->
				</div>
			</div>
		</div>
	</footer>
	<!-- Footer Section Ends -->

	<!-- Jquery Library File -->
	<script src="js/jquery-1.12.4.min.js"></script>
	<!-- Bootstrap js file -->
	<script src="js/bootstrap.min.js"></script>
	<!-- Wow js file -->
	<script src="js/wow.js"></script>
	<!-- Swiper Carousel js file -->
	<script src="js/swiper.min.js"></script>
	<!-- Counterup js file -->
	<script src="js/waypoints.min.js"></script>
	<script src="js/jquery.counterup.min.js"></script>
	<!-- Isotop js file -->
	<script src="js/isotope.min.js"></script>
	<!-- Magnific Popup core JS file -->
	<script src="js/jquery.magnific-popup.min.js"></script>
	<!-- Slick Nav js file -->
	<script src="js/jquery.slicknav.js"></script>
	<!-- SmoothScroll -->
	<script src="js/SmoothScroll.js"></script>
	<!-- Animated Headline js file -->
	<script src="js/animation-headline.js"></script>
	<!-- Main Custom js file -->
	<script src="js/function.js"></script>
	<script src="js/particle.js"></script>
</body>

</html>
