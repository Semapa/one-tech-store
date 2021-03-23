<template>
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
                <div class="product_image d-flex flex-column align-items-center justify-content-center"><img src="../../images/new_5.jpg" alt=""></div>
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
                <div class="product_image d-flex flex-column align-items-center justify-content-center"><img src="../../images/featured_1.png" alt=""></div>
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
                <div class="product_image d-flex flex-column align-items-center justify-content-center"><img src="../../images/featured_2.png" alt=""></div>
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
                <div class="product_image d-flex flex-column align-items-center justify-content-center"><img src="../../images/featured_3.png" alt=""></div>
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
                <div class="product_image d-flex flex-column align-items-center justify-content-center"><img src="../../images/featured_4.png" alt=""></div>
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
                <div class="product_image d-flex flex-column align-items-center justify-content-center"><img src="../../images/shop_1.jpg" alt=""></div>
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
                <div class="product_image d-flex flex-column align-items-center justify-content-center"><img src="../../images/featured_5.png" alt=""></div>
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
                <div class="product_image d-flex flex-column align-items-center justify-content-center"><img src="../../images/featured_6.png" alt=""></div>
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
                <div class="product_image d-flex flex-column align-items-center justify-content-center"><img src="../../images/featured_7.png" alt=""></div>
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
                <div class="product_image d-flex flex-column align-items-center justify-content-center"><img src="../../images/featured_8.png" alt=""></div>
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
                <div class="product_image d-flex flex-column align-items-center justify-content-center"><img src="../../images/new_1.jpg" alt=""></div>
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
                <div class="product_image d-flex flex-column align-items-center justify-content-center"><img src="../../images/new_2.jpg" alt=""></div>
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
                <div class="product_image d-flex flex-column align-items-center justify-content-center"><img src="../../images/new_3.jpg" alt=""></div>
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
                <div class="product_image d-flex flex-column align-items-center justify-content-center"><img src="../../images/new_4.jpg" alt=""></div>
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
                <div class="product_image d-flex flex-column align-items-center justify-content-center"><img src="../../images/featured_1.png" alt=""></div>
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
                <div class="product_image d-flex flex-column align-items-center justify-content-center"><img src="../../images/new_6.jpg" alt=""></div>
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
                <div class="product_image d-flex flex-column align-items-center justify-content-center"><img src="../../images/new_7.jpg" alt=""></div>
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
                <div class="product_image d-flex flex-column align-items-center justify-content-center"><img src="../../images/new_8.jpg" alt=""></div>
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
                <div class="product_image d-flex flex-column align-items-center justify-content-center"><img src="../../images/shop_2.jpg" alt=""></div>
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
                <div class="product_image d-flex flex-column align-items-center justify-content-center"><img src="../../images/featured_5.png" alt=""></div>
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
    </div>
</template>