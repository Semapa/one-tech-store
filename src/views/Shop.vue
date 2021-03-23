<template>

<div class="shop">
    <div class="container">
        <div class="row">
            <div class="col-lg-3">

                <!-- Shop Sidebar -->
                <div class="shop_sidebar">
                    <div class="sidebar_section">
                        <div class="sidebar_title">Категории</div>
                        <ul class="sidebar_categories">
                            <li><a href="#">Компьютеры и ноутбуки</a></li>
                            <li><a href="#">Камеры и фотоаппараты</a></li>
                            <li><a href="#">Оборудование</a></li>
                            <li><a href="#">Смартфоны и планшеты</a></li>
                            <li><a href="#">ТВ и аудио</a></li>
                            <li><a href="#">Автомобильная электроника</a></li>
                            <li><a href="#">Игровые приставки и видеоигры</a></li>
                            <li><a href="#">Аксессуары</a></li>
                        </ul>
                    </div>
                </div>
            </div>

            <div class="col-lg-9">
                
                <!-- Shop Content -->

                <div class="shop_content">
                    <div class="shop_bar clearfix">
                        <div class="shop_product_count"><span>186</span> найдено продуктов</div>
                        <div class="shop_sorting">
                            <span>Сортировать по:</span>
                            <ul>
                                <li>
                                    <span class="sorting_text">рейтингу<i class="fas fa-chevron-down"></i></span>
                                    <ul>
                                        <li class="shop_sorting_button" data-isotope-option='{ "sortBy": "original-order" }'>рейтингу</li>
                                        <li class="shop_sorting_button" data-isotope-option='{ "sortBy": "name" }'>названию</li>
                                        <li class="shop_sorting_button" data-isotope-option='{ "sortBy": "price" }'>цене</li>
                                    </ul>
                                </li>
                            </ul>
                        </div>
                    </div>

                    <div class="product_grid">
                        <div class="product_grid_border"></div>

                        <!-- Product Item -->
                        <div class="product_item is_new">
                            <div class="product_border"></div>
                            <div class="product_image d-flex flex-column align-items-center justify-content-center"><img src="../images/new_5.jpg" alt=""></div>
                            <div class="product_content">
                                <div class="product_price">$225</div>
                                <div class="product_name"><div><a href="#" tabindex="0">Philips BT6900A</a></div></div>
                                <div class="product_extras">
                                    <button class="product_cart_button">Add to Cart</button>
                                </div>
                            </div>
                            <div class="product_fav"><i class="fas fa-heart"></i></div>
                            <ul class="product_marks">
                                <li class="product_mark product_discount">-25%</li>
                                <li class="product_mark product_new">new</li>
                            </ul>
                        </div>

                        <!-- Product Item -->
                        <div class="product_item discount">
                            <div class="product_border"></div>
                            <div class="product_image d-flex flex-column align-items-center justify-content-center"><img src="../images/featured_1.png" alt=""></div>
                            <div class="product_content">
                                <div class="product_price">$225<span>$300</span></div>
                                <div class="product_name"><div><a href="#" tabindex="0">Huawei MediaPad...</a></div></div>
                                <div class="product_extras">
                                    <button class="product_cart_button">Add to Cart</button>
                                </div>
                            </div>
                            <div class="product_fav"><i class="fas fa-heart"></i></div>
                            <ul class="product_marks">
                                <li class="product_mark product_discount">-25%</li>
                                <li class="product_mark product_new">new</li>
                            </ul>
                        </div>

                        <!-- Product Item -->
                        <div class="product_item">
                            <div class="product_border"></div>
                            <div class="product_image d-flex flex-column align-items-center justify-content-center"><img src="../images/featured_2.png" alt=""></div>
                            <div class="product_content">
                                <div class="product_price">$379</div>
                                <div class="product_name"><div><a href="#" tabindex="0">Apple iPod shuffle</a></div></div>
                                <div class="product_extras">
                                    <button class="product_cart_button">Add to Cart</button>
                                </div>
                            </div>
                            <div class="product_fav"><i class="fas fa-heart"></i></div>
                            <ul class="product_marks">
                                <li class="product_mark product_discount">-25%</li>
                                <li class="product_mark product_new">new</li>
                            </ul>
                        </div>

                        <!-- Product Item -->
                        <div class="product_item">
                            <div class="product_border"></div>
                            <div class="product_image d-flex flex-column align-items-center justify-content-center"><img src="../images/featured_3.png" alt=""></div>
                            <div class="product_content">
                                <div class="product_price">$225</div>
                                <div class="product_name"><div><a href="#" tabindex="0">Sony MDRZX310W</a></div></div>
                            </div>
                            <div class="product_fav"><i class="fas fa-heart"></i></div>
                            <ul class="product_marks">
                                <li class="product_mark product_discount">-25%</li>
                                <li class="product_mark product_new">new</li>
                            </ul>
                        </div>

                        <!-- Product Item -->
                        <div class="product_item is_new">
                            <div class="product_border"></div>
                            <div class="product_image d-flex flex-column align-items-center justify-content-center"><img src="../images/featured_4.png" alt=""></div>
                            <div class="product_content">
                                <div class="product_price">$379</div>
                                <div class="product_name"><div><a href="#" tabindex="0">LUNA Smartphone</a></div></div>
                            </div>
                            <div class="product_fav"><i class="fas fa-heart"></i></div>
                            <ul class="product_marks">
                                <li class="product_mark product_discount">-25%</li>
                                <li class="product_mark product_new">new</li>
                            </ul>
                        </div>

                        <!-- Product Item -->
                        <div class="product_item is_new">
                            <div class="product_border"></div>
                            <div class="product_image d-flex flex-column align-items-center justify-content-center"><img src="../images/shop_1.jpg" alt=""></div>
                            <div class="product_content">
                                <div class="product_price">$379</div>
                                <div class="product_name"><div><a href="#" tabindex="0">Canon IXUS 175...</a></div></div>
                            </div>
                            <div class="product_fav"><i class="fas fa-heart"></i></div>
                            <ul class="product_marks">
                                <li class="product_mark product_discount">-25%</li>
                                <li class="product_mark product_new">new</li>
                            </ul>
                        </div>

                        <!-- Product Item -->
                        <div class="product_item">
                            <div class="product_border"></div>
                            <div class="product_image d-flex flex-column align-items-center justify-content-center"><img src="../images/featured_5.png" alt=""></div>
                            <div class="product_content">
                                <div class="product_price">$379<span>$300</span></div>
                                <div class="product_name"><div><a href="#" tabindex="0">Canon STM Kit...</a></div></div>
                            </div>
                            <div class="product_fav"><i class="fas fa-heart"></i></div>
                            <ul class="product_marks">
                                <li class="product_mark product_discount">-25%</li>
                                <li class="product_mark product_new">new</li>
                            </ul>
                        </div>

                        <!-- Product Item -->
                        <div class="product_item">
                            <div class="product_border"></div>
                            <div class="product_image d-flex flex-column align-items-center justify-content-center"><img src="../images/featured_6.png" alt=""></div>
                            <div class="product_content">
                                <div class="product_price">$225<span>$300</span></div>
                                <div class="product_name"><div><a href="#" tabindex="0">Samsung J330F</a></div></div>
                            </div>
                            <div class="product_fav"><i class="fas fa-heart"></i></div>
                            <ul class="product_marks">
                                <li class="product_mark product_discount">-25%</li>
                                <li class="product_mark product_new">new</li>
                            </ul>
                        </div>

                        <!-- Product Item -->
                        <div class="product_item">
                            <div class="product_border"></div>
                            <div class="product_image d-flex flex-column align-items-center justify-content-center"><img src="../images/featured_7.png" alt=""></div>
                            <div class="product_content">
                                <div class="product_price">$225</div>
                                <div class="product_name"><div><a href="#" tabindex="0">Lenovo IdeaPad</a></div></div>
                            </div>
                            <div class="product_fav"><i class="fas fa-heart"></i></div>
                            <ul class="product_marks">
                                <li class="product_mark product_discount">-25%</li>
                                <li class="product_mark product_new">new</li>
                            </ul>
                        </div>

                        <!-- Product Item -->
                        <div class="product_item">
                            <div class="product_border"></div>
                            <div class="product_image d-flex flex-column align-items-center justify-content-center"><img src="../images/featured_8.png" alt=""></div>
                            <div class="product_content">
                                <div class="product_price">$379</div>
                                <div class="product_name"><div><a href="#" tabindex="0">Digitus EDNET...</a></div></div>
                            </div>
                            <div class="product_fav"><i class="fas fa-heart"></i></div>
                            <ul class="product_marks">
                                <li class="product_mark product_discount">-25%</li>
                                <li class="product_mark product_new">new</li>
                            </ul>
                        </div>

                        <!-- Product Item -->
                        <div class="product_item is_new">
                            <div class="product_border"></div>
                            <div class="product_image d-flex flex-column align-items-center justify-content-center"><img src="../images/new_1.jpg" alt=""></div>
                            <div class="product_content">
                                <div class="product_price">$225</div>
                                <div class="product_name"><div><a href="#" tabindex="0">Astro M2 Black</a></div></div>
                            </div>
                            <div class="product_fav"><i class="fas fa-heart"></i></div>
                            <ul class="product_marks">
                                <li class="product_mark product_discount">-25%</li>
                                <li class="product_mark product_new">new</li>
                            </ul>
                        </div>

                        <!-- Product Item -->
                        <div class="product_item is_new">
                            <div class="product_border"></div>
                            <div class="product_image d-flex flex-column align-items-center justify-content-center"><img src="../images/new_2.jpg" alt=""></div>
                            <div class="product_content">
                                <div class="product_price">$225</div>
                                <div class="product_name"><div><a href="#" tabindex="0">Transcend T.Sonic</a></div></div>
                            </div>
                            <div class="product_fav"><i class="fas fa-heart"></i></div>
                            <ul class="product_marks">
                                <li class="product_mark product_discount">-25%</li>
                                <li class="product_mark product_new">new</li>
                            </ul>
                        </div>

                        <!-- Product Item -->
                        <div class="product_item is_new">
                            <div class="product_border"></div>
                            <div class="product_image d-flex flex-column align-items-center justify-content-center"><img src="../images/new_3.jpg" alt=""></div>
                            <div class="product_content">
                                <div class="product_price">$225</div>
                                <div class="product_name"><div><a href="#" tabindex="0">Xiaomi Band 2...</a></div></div>
                            </div>
                            <div class="product_fav"><i class="fas fa-heart"></i></div>
                            <ul class="product_marks">
                                <li class="product_mark product_discount">-25%</li>
                                <li class="product_mark product_new">new</li>
                            </ul>
                        </div>

                        <!-- Product Item -->
                        <div class="product_item is_new">
                            <div class="product_border"></div>
                            <div class="product_image d-flex flex-column align-items-center justify-content-center"><img src="../images/new_4.jpg" alt=""></div>
                            <div class="product_content">
                                <div class="product_price">$379</div>
                                <div class="product_name"><div><a href="#" tabindex="0">Rapoo T8 White</a></div></div>
                            </div>
                            <div class="product_fav"><i class="fas fa-heart"></i></div>
                            <ul class="product_marks">
                                <li class="product_mark product_discount">-25%</li>
                                <li class="product_mark product_new">new</li>
                            </ul>
                        </div>

                        <!-- Product Item -->
                        <div class="product_item discount">
                            <div class="product_border"></div>
                            <div class="product_image d-flex flex-column align-items-center justify-content-center"><img src="../images/featured_1.png" alt=""></div>
                            <div class="product_content">
                                <div class="product_price">$225<span>$300</span></div>
                                <div class="product_name"><div><a href="#" tabindex="0">Huawei MediaPad...</a></div></div>
                            </div>
                            <div class="product_fav"><i class="fas fa-heart"></i></div>
                            <ul class="product_marks">
                                <li class="product_mark product_discount">-25%</li>
                                <li class="product_mark product_new">new</li>
                            </ul>
                        </div>

                        <!-- Product Item -->
                        <div class="product_item is_new">
                            <div class="product_border"></div>
                            <div class="product_image d-flex flex-column align-items-center justify-content-center"><img src="../images/new_6.jpg" alt=""></div>
                            <div class="product_content">
                                <div class="product_price">$379</div>
                                <div class="product_name"><div><a href="#" tabindex="0">Nokia 3310 (2017)</a></div></div>
                            </div>
                            <div class="product_fav"><i class="fas fa-heart"></i></div>
                            <ul class="product_marks">
                                <li class="product_mark product_discount">-25%</li>
                                <li class="product_mark product_new">new</li>
                            </ul>
                        </div>

                        <!-- Product Item -->
                        <div class="product_item is_new">
                            <div class="product_border"></div>
                            <div class="product_image d-flex flex-column align-items-center justify-content-center"><img src="../images/new_7.jpg" alt=""></div>
                            <div class="product_content">
                                <div class="product_price">$225</div>
                                <div class="product_name"><div><a href="#" tabindex="0">Rapoo 7100p Gray</a></div></div>
                            </div>
                            <div class="product_fav"><i class="fas fa-heart"></i></div>
                            <ul class="product_marks">
                                <li class="product_mark product_discount">-25%</li>
                                <li class="product_mark product_new">new</li>
                            </ul>
                        </div>

                        <!-- Product Item -->
                        <div class="product_item is_new">
                            <div class="product_border"></div>
                            <div class="product_image d-flex flex-column align-items-center justify-content-center"><img src="../images/new_8.jpg" alt=""></div>
                            <div class="product_content">
                                <div class="product_price">$379</div>
                                <div class="product_name"><div><a href="#" tabindex="0">Canon EF</a></div></div>
                            </div>
                            <div class="product_fav"><i class="fas fa-heart"></i></div>
                            <ul class="product_marks">
                                <li class="product_mark product_discount">-25%</li>
                                <li class="product_mark product_new">new</li>
                            </ul>
                        </div>

                        <!-- Product Item -->
                        <div class="product_item is_new">
                            <div class="product_border"></div>
                            <div class="product_image d-flex flex-column align-items-center justify-content-center"><img src="../images/shop_2.jpg" alt=""></div>
                            <div class="product_content">
                                <div class="product_price">$225</div>
                                <div class="product_name"><div><a href="#" tabindex="0">Gembird SPK-103</a></div></div>
                            </div>
                            <div class="product_fav"><i class="fas fa-heart"></i></div>
                            <ul class="product_marks">
                                <li class="product_mark product_discount">-25%</li>
                                <li class="product_mark product_new">new</li>
                            </ul>
                        </div>

                        <!-- Product Item -->
                        <div class="product_item is_new">
                            <div class="product_border"></div>
                            <div class="product_image d-flex flex-column align-items-center justify-content-center"><img src="../images/featured_5.png" alt=""></div>
                            <div class="product_content">
                                <div class="product_price">$379</div>
                                <div class="product_name"><div><a href="#" tabindex="0">Canon STM Kit...</a></div></div>
                            </div>
                            <div class="product_fav"><i class="fas fa-heart"></i></div>
                            <ul class="product_marks">
                                <li class="product_mark product_discount">-25%</li>
                                <li class="product_mark product_new">new</li>
                            </ul>
                        </div>

                    </div>

                    <!-- Shop Page Navigation -->

                    <div class="shop_page_nav d-flex flex-row">
                        <div class="page_prev d-flex flex-column align-items-center justify-content-center"><i class="fas fa-chevron-left"></i></div>
                        <ul class="page_nav d-flex flex-row">
                            <li><a href="#">1</a></li>
                            <li><a href="#">2</a></li>
                            <li><a href="#">3</a></li>
                            <li><a href="#">...</a></li>
                            <li><a href="#">21</a></li>
                        </ul>
                        <div class="page_next d-flex flex-column align-items-center justify-content-center"><i class="fas fa-chevron-right"></i></div>
                    </div>

                </div>

            </div>
        </div>
    </div>
</div>

<!-- Newsletter -->

	<div class="newsletter">
		<div class="container">
			<div class="row">
				<div class="col">
					<div class="newsletter_container d-flex flex-lg-row flex-column align-items-lg-center align-items-center justify-content-lg-start justify-content-center">
						<div class="newsletter_title_container">
							<div class="newsletter_icon"><img src="images/send.png" alt=""></div>
							<div class="newsletter_title">Подпишитесь чтобы получать новости</div>
							<div class="newsletter_text"><p>...и получите 20% скидку на первую покупку.</p></div>
						</div>
						<div class="newsletter_content clearfix">
							<form action="#" class="newsletter_form">
								<input type="email" class="newsletter_input" required="required" placeholder="Введите свой email адрес">
								<button class="newsletter_button">Подписаться</button>
							</form>
							<div class="newsletter_unsubscribe_link"><a href="#">отписаться от рассылки</a></div>
						</div>
					</div>
				</div>
			</div>
		</div>
	</div>

	<!-- Footer -->

	<footer class="footer">
		<div class="container">
			<div class="row">

				<div class="col-lg-3 footer_col">
					<div class="footer_column footer_contact">
						<div class="logo_container">
							<div class="logo"><a href="#">OneTech</a></div>
						</div>
						<div class="footer_title">Got Question? Call Us 24/7</div>
						<div class="footer_phone">+38 068 005 3570</div>
						<div class="footer_contact_text">
							<p>17 Princess Road, London</p>
							<p>Grester London NW18JR, UK</p>
						</div>
						<div class="footer_social">
							<ul>
								<li><a href="#"><i class="fab fa-facebook-f"></i></a></li>
								<li><a href="#"><i class="fab fa-twitter"></i></a></li>
								<li><a href="#"><i class="fab fa-youtube"></i></a></li>
								<li><a href="#"><i class="fab fa-google"></i></a></li>
								<li><a href="#"><i class="fab fa-vimeo-v"></i></a></li>
							</ul>
						</div>
					</div>
				</div>

				<div class="col-lg-2 offset-lg-2">
					<div class="footer_column">
						<div class="footer_title">Find it Fast</div>
						<ul class="footer_list">
							<li><a href="#">Computers & Laptops</a></li>
							<li><a href="#">Cameras & Photos</a></li>
							<li><a href="#">Hardware</a></li>
							<li><a href="#">Smartphones & Tablets</a></li>
							<li><a href="#">TV & Audio</a></li>
						</ul>
						<div class="footer_subtitle">Gadgets</div>
						<ul class="footer_list">
							<li><a href="#">Car Electronics</a></li>
						</ul>
					</div>
				</div>

				<div class="col-lg-2">
					<div class="footer_column">
						<ul class="footer_list footer_list_2">
							<li><a href="#">Video Games & Consoles</a></li>
							<li><a href="#">Accessories</a></li>
							<li><a href="#">Cameras & Photos</a></li>
							<li><a href="#">Hardware</a></li>
							<li><a href="#">Computers & Laptops</a></li>
						</ul>
					</div>
				</div>

				<div class="col-lg-2">
					<div class="footer_column">
						<div class="footer_title">Customer Care</div>
						<ul class="footer_list">
							<li><a href="#">My Account</a></li>
							<li><a href="#">Order Tracking</a></li>
							<li><a href="#">Wish List</a></li>
							<li><a href="#">Customer Services</a></li>
							<li><a href="#">Returns / Exchange</a></li>
							<li><a href="#">FAQs</a></li>
							<li><a href="#">Product Support</a></li>
						</ul>
					</div>
				</div>

			</div>
		</div>
	</footer>
</template>