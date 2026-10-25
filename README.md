<main class="container my-3">
    <div class="row">
       <!-- left Side -->
        <div class="col-lg-3">
          <div class="catagory-box">
            <h4 class="bg-danger p-3 border rounded-2 text-white">
               <i class="bi bi-grid-3x3-gap-fill"> </i> Categories
            </h4>

            <div class="accordion" id="accordionPanelsStayOpenExample">
                <div class="accordion-item">
                  <h2 class="accordion-header">
                    <button class="accordion-button" type="button" data-bs-toggle="collapse" data-bs-target="#panelsStayOpen-collapseOne" aria-expanded="true" aria-controls="panelsStayOpen-collapseOne">
                      Electronics
                    </button>
                  </h2>
                  <div id="panelsStayOpen-collapseOne" class="accordion-collapse collapse show">
                    <div class="accordion-body">
                        <ul>  
                          <li> Tab</li>
                          <li> Laptop </li>
                          <li> Television </li>
                          <li> Phone</li>
                        </ul>
                    </div>
                  </div>
                </div>

                <div class="accordion-item">
                  <h2 class="accordion-header">
                    <button class="accordion-button" type="button" data-bs-toggle="collapse" data-bs-target="#fashon" aria-expanded="true" aria-controls="panelsStayOpen-collapseOne">
                     Fashon
                    </button>
                  </h2>
                  <div id="fashon" class="accordion-collapse collapse show">
                    <div class="accordion-body">
                        <ul>  
                          <li> Clothing </li>
                          <li> Jewllery </li>
                          <li> Bags </li>
                          <li> Shoes </li>
                        </ul>
                    </div>
                  </div>
                </div>

                <div class="accordion-item">
                  <h2 class="accordion-header">
                    <button class="accordion-button" type="button" data-bs-toggle="collapse" data-bs-target="#home&living" aria-expanded="true" aria-controls="panelsStayOpen-collapseOne">
                      Home and Living
                    </button>
                  </h2>
                  <div id="home&living" class="accordion-collapse collapse show">
                    <div class="accordion-body">
                        <ul>  
                          <li> Furniture </li>
                          <li> Kitchen </li>
                          <li> Decoration </li>
                          <li> Crokarige </li>
                        </ul>
                    </div>
                  </div>
                </div>

            </div>
             <!-- Filter Card -->
        <div class="filter-box mt-4">
          <h5 class="bg-danger p-3 border rounded-2 text-white"><i class="bi bi-funnel"></i> Quick Filter</h5>
          <label class="form-label mt-3">Price Range</label>
          <select class="form-select" id="priceFilter">
            <option value="all">All Prices</option>
            <option value="under50">Under $50</option>
            <option value="50to100">$50 - $100</option>
            <option value="over100">Over $100</option>
          </select>
        </div>
          </div>
        </div>    
       <!-- left Side -->
        <!-- RIGHT PANE -->
      <section class="col-lg-9">
        <div class="d-flex justify-content-between align-items-center flex-wrap gap-2 mb-3">
          <div>
            <h3 class="mb-1">All Products</h3>
            <p class="text-muted mb-0"><span id="productResultCount">8</span> products found</p>
          </div>
          <select class="form-select w-25" id="sortProducts">
            <option value="default">Sort: Default</option>
            <option value="low">Price: Low to High</option>
            <option value="high">Price: High to Low</option>
            <option value="name">Name: A-Z</option>
          </select>
        </div>

                       <!-- Right Side -->
      <div class="row g-4">
        <!-- Product 1 -->
          <div class="col-sm-6 col-xl-4 product-item" data-name="Premium Headphone" data-price="49">
            <div class="card product-card h-100">
              <div class="product-image-wrap">
                <span class="badge bg-danger product-badge">SALE</span>
                <button class="wishlist-btn" title="Add to wishlist"><i class="bi bi-heart"></i></button>
                <img src="https://images.unsplash.com/photo-1505740420928-5e560c06d30e?auto=format&fit=crop&w=700&q=80"
                     class="card-img-top" alt="Premium Headphone">
              </div>
              <div class="card-body d-flex flex-column">
                <small class="text-muted">Electronics</small>
                <h5 class="card-title">Premium Headphone</h5>
                <div class="rating mb-2">★★★★★ <span>(24)</span></div>
                <p class="card-text">Comfortable wireless headphone with premium sound.</p>
                <div class="price mt-auto">$49.00</div>
                <button class="btn btn-primary w-100 add-cart" data-product="Premium Headphone" data-price="49">
                  <i class="bi bi-cart-plus"></i> Add to Cart
                </button>
              </div>
            </div>
          </div>

          <!-- Product 2 -->
          <div class="col-sm-6 col-xl-4 product-item" data-name="Smart Watch" data-price="79">
            <div class="card product-card h-100">
              <div class="product-image-wrap">
                <span class="badge bg-success product-badge">NEW</span>
                <button class="wishlist-btn" title="Add to wishlist"><i class="bi bi-heart"></i></button>
                <img src="https://images.unsplash.com/photo-1523275335684-37898b6baf30?auto=format&fit=crop&w=700&q=80"
                     class="card-img-top" alt="Smart Watch">
              </div>
              <div class="card-body d-flex flex-column">
                <small class="text-muted">Electronics</small>
                <h5 class="card-title">Smart Watch</h5>
                <div class="rating mb-2">★★★★★ <span>(31)</span></div>
                <p class="card-text">Modern smartwatch with fitness and notification features.</p>
                <div class="price mt-auto">$79.00</div>
                <button class="btn btn-primary w-100 add-cart" data-product="Smart Watch" data-price="79">
                  <i class="bi bi-cart-plus"></i> Add to Cart
                </button>
              </div>
            </div>
          </div>

          <!-- Product 3 -->
          <div class="col-sm-6 col-xl-4 product-item" data-name="Classic Camera" data-price="129">
            <div class="card product-card h-100">
              <div class="product-image-wrap">
                <span class="badge bg-warning text-dark product-badge">HOT</span>
                <button class="wishlist-btn" title="Add to wishlist"><i class="bi bi-heart"></i></button>
                <img src="https://images.unsplash.com/photo-1516035069371-29a1b244cc32?auto=format&fit=crop&w=700&q=80"
                     class="card-img-top" alt="Classic Camera">
              </div>
              <div class="card-body d-flex flex-column">
                <small class="text-muted">Electronics</small>
                <h5 class="card-title">Classic Camera</h5>
                <div class="rating mb-2">★★★★☆ <span>(18)</span></div>
                <p class="card-text">Capture beautiful moments with this high-quality camera.</p>
                <div class="price mt-auto">$129.00</div>
                <button class="btn btn-primary w-100 add-cart" data-product="Classic Camera" data-price="129">
                  <i class="bi bi-cart-plus"></i> Add to Cart
                </button>
              </div>
            </div>
          </div>

          <!-- Product 4 -->
          <div class="col-sm-6 col-xl-4 product-item" data-name="Leather Backpack" data-price="59">
            <div class="card product-card h-100">
              <div class="product-image-wrap">
                <button class="wishlist-btn" title="Add to wishlist"><i class="bi bi-heart"></i></button>
                <img src="https://images.unsplash.com/photo-1553062407-98eeb64c6a62?auto=format&fit=crop&w=700&q=80"
                     class="card-img-top" alt="Leather Backpack">
              </div>
              <div class="card-body d-flex flex-column">
                <small class="text-muted">Fashion</small>
                <h5 class="card-title">Leather Backpack</h5>
                <div class="rating mb-2">★★★★★ <span>(42)</span></div>
                <p class="card-text">Stylish and durable backpack for everyday use.</p>
                <div class="price mt-auto">$59.00</div>
                <button class="btn btn-primary w-100 add-cart" data-product="Leather Backpack" data-price="59">
                  <i class="bi bi-cart-plus"></i> Add to Cart
                </button>
              </div>
            </div>
          </div>

          <!-- Product 5 -->
          <div class="col-sm-6 col-xl-4 product-item" data-name="Running Shoes" data-price="89">
            <div class="card product-card h-100">
              <div class="product-image-wrap">
                <span class="badge bg-info product-badge">BEST</span>
                <button class="wishlist-btn" title="Add to wishlist"><i class="bi bi-heart"></i></button>
                <img src="https://images.unsplash.com/photo-1542291026-7eec264c27ff?auto=format&fit=crop&w=700&q=80"
                     class="card-img-top" alt="Running Shoes">
              </div>
              <div class="card-body d-flex flex-column">
                <small class="text-muted">Fashion</small>
                <h5 class="card-title">Running Shoes</h5>
                <div class="rating mb-2">★★★★★ <span>(56)</span></div>
                <p class="card-text">Lightweight running shoes designed for comfort.</p>
                <div class="price mt-auto">$89.00</div>
                <button class="btn btn-primary w-100 add-cart" data-product="Running Shoes" data-price="89">
                  <i class="bi bi-cart-plus"></i> Add to Cart
                </button>
              </div>
            </div>
          </div>

          <!-- Product 6 -->
          <div class="col-sm-6 col-xl-4 product-item" data-name="Sunglasses" data-price="35">
            <div class="card product-card h-100">
              <div class="product-image-wrap">
                <span class="badge bg-danger product-badge">SALE</span>
                <button class="wishlist-btn" title="Add to wishlist"><i class="bi bi-heart"></i></button>
                <img src="https://images.unsplash.com/photo-1511499767150-a48a237f0083?auto=format&fit=crop&w=700&q=80"
                     class="card-img-top" alt="Sunglasses">
              </div>
              <div class="card-body d-flex flex-column">
                <small class="text-muted">Fashion</small>
                <h5 class="card-title">Sunglasses</h5>
                <div class="rating mb-2">★★★★☆ <span>(15)</span></div>
                <p class="card-text">Trendy sunglasses with a clean and modern design.</p>
                <div class="price mt-auto">$35.00</div>
                <button class="btn btn-primary w-100 add-cart" data-product="Sunglasses" data-price="35">
                  <i class="bi bi-cart-plus"></i> Add to Cart
                </button>
              </div>
            </div>
          </div>

          <!-- Product 7 -->
          <div class="col-sm-6 col-xl-4 product-item" data-name="Desk Lamp" data-price="45">
            <div class="card product-card h-100">
              <div class="product-image-wrap">
                <button class="wishlist-btn" title="Add to wishlist"><i class="bi bi-heart"></i></button>
                <img src="https://images.unsplash.com/photo-1507473885765-e6ed057f782c?auto=format&fit=crop&w=700&q=80"
                     class="card-img-top" alt="Desk Lamp">
              </div>
              <div class="card-body d-flex flex-column">
                <small class="text-muted">Home & Living</small>
                <h5 class="card-title">Modern Desk Lamp</h5>
                <div class="rating mb-2">★★★★★ <span>(20)</span></div>
                <p class="card-text">Elegant desk lamp for your home or office setup.</p>
                <div class="price mt-auto">$45.00</div>
                <button class="btn btn-primary w-100 add-cart" data-product="Modern Desk Lamp" data-price="45">
                  <i class="bi bi-cart-plus"></i> Add to Cart
                </button>
              </div>
            </div>
          </div>

          <!-- Product 8 -->
          <div class="col-sm-6 col-xl-4 product-item" data-name="Perfume" data-price="110">
            <div class="card product-card h-100">
              <div class="product-image-wrap">
                <span class="badge bg-success product-badge">NEW</span>
                <button class="wishlist-btn" title="Add to wishlist"><i class="bi bi-heart"></i></button>
                <img src="https://images.unsplash.com/photo-1541643600914-78b084683601?auto=format&fit=crop&w=700&q=80"
                     class="card-img-top" alt="Perfume">
              </div>
              <div class="card-body d-flex flex-column">
                <small class="text-muted">Beauty & Care</small>
                <h5 class="card-title">Premium Perfume</h5>
                <div class="rating mb-2">★★★★★ <span>(27)</span></div>
                <p class="card-text">A premium fragrance with a fresh and elegant aroma.</p>
                <div class="price mt-auto">$110.00</div>
                <button class="btn btn-primary w-100 add-cart" data-product="Premium Perfume" data-price="110">
                  <i class="bi bi-cart-plus"></i> Add to Cart
                </button>
              </div>
            </div>
          </div>

           <!-- Product 9 -->
          <div class="col-sm-6 col-xl-4 product-item" data-name="Perfume" data-price="110">
            <div class="card product-card h-100">
              <div class="product-image-wrap">
                <span class="badge bg-success product-badge">NEW</span>
                <button class="wishlist-btn" title="Add to wishlist"><i class="bi bi-heart"></i></button>
                <img src="https://images.unsplash.com/photo-1541643600914-78b084683601?auto=format&fit=crop&w=700&q=80"
                     class="card-img-top" alt="Perfume">
              </div>
              <div class="card-body d-flex flex-column">
                <small class="text-muted">Beauty & Care</small>
                <h5 class="card-title">Premium Perfume</h5>
                <div class="rating mb-2">★★★★★ <span>(27)</span></div>
                <p class="card-text">A premium fragrance with a fresh and elegant aroma.</p>
                <div class="price mt-auto">$110.00</div>
                <button class="btn btn-primary w-100 add-cart" data-product="Premium Perfume" data-price="110">
                  <i class="bi bi-cart-plus"></i> Add to Cart
                </button>
              </div>
            </div>
          </div>

          <!-- No Result -->
        <div id="noResult" class="alert alert-warning text-center mt-4 d-none">
          No product found.
        </div>

        <!-- Pagination -->
        <nav class="mt-5" aria-label="Product pagination">
          <ul class="pagination justify-content-center">
            <li class="page-item disabled"><a class="page-link" href="#">Previous</a></li>
            <li class="page-item"><a class="page-link" href="#">1</a></li>
            <li class="page-item active"><a class="page-link" href="#">2</a></li>
            <li class="page-item"><a class="page-link" href="#">3</a></li>
            <li class="page-item "><a class="page-link" href="#">Next</a></li>
          </ul>
        </nav>
      

        </div>
      </div>

                       <!-- Right Side -->
    </section>
    </div> <!--main row-->

   </main>
