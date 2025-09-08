#Services Cards 

HTML
--------
<section class="creative-cards style-one">
		<div class="container">
			<div class="row">
				<div class="card-column">
					<div class="card-details">
						<div class="card-icons">
							<img class="light-icon" src="https://i.ibb.co/fV0GzDqj/construction.png" alt="icon" />
						</div>
						<h3><a href="https://www.fiverr.com/s/8zElN2v">Core Planning</a></h3>
						<p>Lorem ipsum dolor sit amet, consectne auctor aliquet. Aenean sollicitudi bibendum auctor.</p>
						<a class="read-more-btn" href="https://www.fiverr.com/s/8zElN2v"><i class="fa-solid fa-angles-right"></i></a>
					</div>
				</div>
				<div class="card-column">
					<div class="card-details">
						<div class="card-icons">
							<img class="light-icon" src="https://i.ibb.co/KjGz3dmZ/skyline.png" alt="icon" />
						</div>
						<h3><a href="https://www.fiverr.com/s/8zElN2v">Traditional Designs</a></h3>
						<p>Lorem ipsum dolor sit amet, consectne auctor aliquet. Aenean sollicitudi bibendum auctor.</p>
						<a class="read-more-btn" href="https://www.fiverr.com/s/8zElN2v"><i class="fa-solid fa-angles-right"></i></a>
					</div>
				</div>
				<div class="card-column">
					<div class="card-details">
						<div class="card-icons">
							<img class="light-icon" src="https://i.ibb.co/whkhVgQz/best-practice.png" alt="icon" />
						</div>
						<h3><a href="https://www.fiverr.com/s/8zElN2v">Quality Materials</a></h3>
						<p>Lorem ipsum dolor sit amet, consectne auctor aliquet. Aenean sollicitudi bibendum auctor.</p>
						<a class="read-more-btn" href="https://www.fiverr.com/s/8zElN2v"><i class="fa-solid fa-angles-right"></i></a>
					</div>
				</div>
			</div>
		</div>
	</section>
<!-- End of Services Cards Section -->

CSS
--------

* {
	box-sizing: border-box;
}
.creative-cards{
    padding: 120px 0;
    position: relative;
}
.creative-cards .container {
    max-width: 1320px;
    width: 100%;
    padding-right: .75rem;
    padding-left: .75rem;
    margin-right: auto;
    margin-left: auto;
}
.creative-cards .container .row{
    display: flex;
    flex-wrap: wrap;
}
.creative-cards .container .row .card-column {
    flex: 0 0 auto;
    width: 33.33333333%;
    text-align: center;
    max-width: 100%;
    padding-right: 15px;
    padding-left: 15px;
}
.card-details {
    width: 80%;
    margin: auto;
    position: relative;
    transition: .3s ease-in-out;
}
.card-details:before {
    content: "";
    width: 190px;
    height: 380px;
    background: #f7f6f2;
    position: absolute;
    left: 50%;
    top: 50%;
    transform: translate(-50%, -50%) skew(-20deg, 0deg);
    z-index: -1;
    transition: .3s ease-in-out;
}
.card-details:hover:before{
    background-color: #fffab3;
}
.card-icons {
    width: 140px;
    height: 150px;
    position: relative;
    margin: auto;
    display: flex;
    align-items: center;
    justify-content: center;
}
.card-icons:before {
    content: "";
    position: absolute;
    top: 0;
    left: 0;
    border: 1px solid;
    width: 100%;
    height: 100%;
    transform: skew(-20deg, 0deg);
    background: #fff;
    border-color: #ffee02;
    transition: .3s ease-in-out;
}
.card-details:hover .card-icons:before{
    background-color: #ffee02;
}
.card-icons img{
    position: relative;
    width: 70px;
    height: 70px;
}
.card-details h3{
    margin-bottom: 15px;
    margin-top: 50px;
    font-weight: 700;
    font-size: 1.75rem;
    line-height: 1.2;
}
.card-details h3 a{
  color: #000;
  text-decoration: none;
}
.card-details p{
    font-size: 16px;
    line-height: 30px;
    color: #444;
    font-weight: 400;
    margin-bottom: 30px;
}
.read-more-btn {
    width: 50px;
    height: 50px;
    display: flex;
    justify-content: center;
    align-items: center;
    border: 1px solid;
    border-radius: 100%;
    margin: auto;
    background: #fff;
    transform: translateX(-10px);
    opacity: 0;
    visibility: hidden;
    border-color: #ffee02;
    transition: .3s ease-in-out;
    text-decoration: none;
}
.read-more-btn i{
    color: #000;
    font-size: 12px;
}
.card-details:hover .read-more-btn{
    transform: translateX(0);
    opacity: 1;
    visibility: visible;
}

/* ============= Responsive Ipad ==================== */
@media (max-width: 992px) {
 .creative-cards .container .row .card-column {
    flex: 0 0 auto;
    width: 50%;
    margin-bottom: 40px;
}
}

/* ============= Responsive Iphone ==================== */
@media (max-width: 480px) {
 .creative-cards .container .row .card-column {
    flex: 0 0 auto;
    width: 100%;
    margin-bottom: 20px;
}
.card-details{
    width: 100%;
}
.read-more-btn{
        transform: translateX(0px);
    opacity: 1;
    visibility: visible;
}
}