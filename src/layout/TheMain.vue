<template>
  <div class="app__container">
    <div class="grid">
      <div class="grid__row app__content">
        <div class="grid__column-2">
          <nav class="category">
            <h3 class="category__heading">
              <i class="category__heading-icon fas fa-list"></i>
              Danh Mục
            </h3>

            <ul class="category-list">
              <li class="category-item category-item--active">
                <a href="#" class="category-item__link">Trang điểm mặt</a>
              </li>
              <li class="category-item">
                <a href="#" class="category-item__link">Trang điểm môi</a>
              </li>
              <li class="category-item">
                <a href="#" class="category-item__link">Trang điểm mắt</a>
              </li>
            </ul>
          </nav>
        </div>
        <div class="grid__column-10">
          <div class="home-filter hide-on-mobile-tablet">
            <span class="home-filter__lable">Sắp xếp theo</span>
            <button class="home-filter__btn btn">Phổ biến</button>
            <button class="home-filter__btn btn btn__primary">Mới nhất</button>
            <button class="home-filter__btn btn">Bán chạy</button>

            <div class="select-input">
              <span class="select-input__label">Giá</span>
              <i class="select-input__icon fas fa-angle-down"></i>
              <ul class="select-input__list">
                <li class="select-input__item">
                  <a href="" class="select-input__link"> Giá: Thấp đến cao </a>
                </li>
                <li class="select-input__item">
                  <a href="" class="select-input__link"> Giá: Cao đến thấp </a>
                </li>
              </ul>
            </div>

            <div class="home-filter__page">
              <span class="home-filter__page-num">
                <span class="home-filter__page-current">1</span>/14
              </span>

              <div class="home-filter__page-control">
                <a
                  href=""
                  class="home-filter__page-btn home-filter__page-btn--disabled"
                >
                  <i class="home-filter__page-icon fas fa-angle-left"></i>
                </a>
                <a href="" class="home-filter__page-btn">
                  <i class="home-filter__page-icon fas fa-angle-right"></i>
                </a>
              </div>
            </div>
          </div>

          <div class="home-product">
            <div class="grid__row">
              <div class="grid__column-2-4">
                <a class="home-product-item">
                  <div
                    class="home-product-item-img"
                    style="
                      background-image: url(https://cf.shopee.vn/file/c4ba883648277f885e826c2d0f426d85_tn);
                    "
                  ></div>
                  <h4 class="home-product-item__name">
                    Set dưỡng trắng Whoo đông y hoàng cung Gong Jinh Yang Seol
                    Radiant
                  </h4>
                  <div class="home-product-item__price">
                    <span class="home-product-item__price-old">1.200.000</span>
                    <span class="home-product-item__price-current"
                      >999.000</span
                    >
                  </div>
                  <div class="home-product-item__action">
                    <span
                      class="home-product-item__like home-product-item__like--liked"
                    >
                      <i
                        class="home-product-item__like-icon-empty far fa-heart"
                      ></i>
                      <i
                        class="home-product-item__like-icon-fill fas fa-heart"
                      ></i>
                    </span>
                    <div class="home-product-item-rating">
                      <i class="home-product-item--gold fas fa-star"></i>
                      <i class="home-product-item--gold fas fa-star"></i>
                      <i class="home-product-item--gold fas fa-star"></i>
                      <i class="home-product-item--gold fas fa-star"></i>
                      <i class="fas fa-star"></i>
                    </div>
                    <span class="home-product-item__sold">88 đã bán</span>
                  </div>
                  <div class="home-product-item__origin">
                    <span class="home-product-item__brand">Whoo</span>
                    <span class="home-product-item__origin-name">Hàn Quốc</span>
                  </div>
                  <div class="home-product-item__favourite">
                    <i class="fas fa-check"></i>
                    <span>Yêu thích</span>
                  </div>
                  <div class="home-product-item__sale-off">
                    <span class="home-product-item__percent">10%</span>
                    <div class="home-product-item__label">GIẢM</div>
                  </div>
                </a>
              </div>
              <div class="grid__column-2-4">
                <a class="home-product-item">
                  <div
                    class="home-product-item-img"
                    style="
                      background-image: url(https://cf.shopee.vn/file/c4ba883648277f885e826c2d0f426d85_tn);
                    "
                  ></div>
                  <h4 class="home-product-item__name">
                    Set dưỡng trắng Whoo đông y hoàng cung Gong Jinh Yang Seol
                    Radiant
                  </h4>
                  <div class="home-product-item__price">
                    <span class="home-product-item__price-old">1.200.000</span>
                    <span class="home-product-item__price-current"
                      >999.000</span
                    >
                  </div>
                  <div class="home-product-item__action">
                    <span
                      class="home-product-item__like home-product-item__like--liked"
                    >
                      <i
                        class="home-product-item__like-icon-empty far fa-heart"
                      ></i>
                      <i
                        class="home-product-item__like-icon-fill fas fa-heart"
                      ></i>
                    </span>
                    <div class="home-product-item-rating">
                      <i class="home-product-item--gold fas fa-star"></i>
                      <i class="home-product-item--gold fas fa-star"></i>
                      <i class="home-product-item--gold fas fa-star"></i>
                      <i class="home-product-item--gold fas fa-star"></i>
                      <i class="fas fa-star"></i>
                    </div>
                    <span class="home-product-item__sold">88 đã bán</span>
                  </div>
                  <div class="home-product-item__origin">
                    <span class="home-product-item__brand">Whoo</span>
                    <span class="home-product-item__origin-name">Hàn Quốc</span>
                  </div>
                  <div class="home-product-item__favourite">
                    <i class="fas fa-check"></i>
                    <span>Yêu thích</span>
                  </div>
                  <div class="home-product-item__sale-off">
                    <span class="home-product-item__percent">10%</span>
                    <div class="home-product-item__label">GIẢM</div>
                  </div>
                </a>
              </div>
              <div class="grid__column-2-4">
                <a class="home-product-item">
                  <div
                    class="home-product-item-img"
                    style="
                      background-image: url(https://cf.shopee.vn/file/c4ba883648277f885e826c2d0f426d85_tn);
                    "
                  ></div>
                  <h4 class="home-product-item__name">
                    Set dưỡng trắng Whoo đông y hoàng cung Gong Jinh Yang Seol
                    Radiant
                  </h4>
                  <div class="home-product-item__price">
                    <span class="home-product-item__price-old">1.200.000</span>
                    <span class="home-product-item__price-current"
                      >999.000</span
                    >
                  </div>
                  <div class="home-product-item__action">
                    <span
                      class="home-product-item__like home-product-item__like--liked"
                    >
                      <i
                        class="home-product-item__like-icon-empty far fa-heart"
                      ></i>
                      <i
                        class="home-product-item__like-icon-fill fas fa-heart"
                      ></i>
                    </span>
                    <div class="home-product-item-rating">
                      <i class="home-product-item--gold fas fa-star"></i>
                      <i class="home-product-item--gold fas fa-star"></i>
                      <i class="home-product-item--gold fas fa-star"></i>
                      <i class="home-product-item--gold fas fa-star"></i>
                      <i class="fas fa-star"></i>
                    </div>
                    <span class="home-product-item__sold">88 đã bán</span>
                  </div>
                  <div class="home-product-item__origin">
                    <span class="home-product-item__brand">Whoo</span>
                    <span class="home-product-item__origin-name">Hàn Quốc</span>
                  </div>
                  <div class="home-product-item__favourite">
                    <i class="fas fa-check"></i>
                    <span>Yêu thích</span>
                  </div>
                  <div class="home-product-item__sale-off">
                    <span class="home-product-item__percent">10%</span>
                    <div class="home-product-item__label">GIẢM</div>
                  </div>
                </a>
              </div>
              <div class="grid__column-2-4">
                <a class="home-product-item">
                  <div
                    class="home-product-item-img"
                    style="
                      background-image: url(https://cf.shopee.vn/file/c4ba883648277f885e826c2d0f426d85_tn);
                    "
                  ></div>
                  <h4 class="home-product-item__name">
                    Set dưỡng trắng Whoo đông y hoàng cung Gong Jinh Yang Seol
                    Radiant
                  </h4>
                  <div class="home-product-item__price">
                    <span class="home-product-item__price-old">1.200.000</span>
                    <span class="home-product-item__price-current"
                      >999.000</span
                    >
                  </div>
                  <div class="home-product-item__action">
                    <span
                      class="home-product-item__like home-product-item__like--liked"
                    >
                      <i
                        class="home-product-item__like-icon-empty far fa-heart"
                      ></i>
                      <i
                        class="home-product-item__like-icon-fill fas fa-heart"
                      ></i>
                    </span>
                    <div class="home-product-item-rating">
                      <i class="home-product-item--gold fas fa-star"></i>
                      <i class="home-product-item--gold fas fa-star"></i>
                      <i class="home-product-item--gold fas fa-star"></i>
                      <i class="home-product-item--gold fas fa-star"></i>
                      <i class="fas fa-star"></i>
                    </div>
                    <span class="home-product-item__sold">88 đã bán</span>
                  </div>
                  <div class="home-product-item__origin">
                    <span class="home-product-item__brand">Whoo</span>
                    <span class="home-product-item__origin-name">Hàn Quốc</span>
                  </div>
                  <div class="home-product-item__favourite">
                    <i class="fas fa-check"></i>
                    <span>Yêu thích</span>
                  </div>
                  <div class="home-product-item__sale-off">
                    <span class="home-product-item__percent">10%</span>
                    <div class="home-product-item__label">GIẢM</div>
                  </div>
                </a>
              </div>
              <div class="grid__column-2-4">
                <a class="home-product-item">
                  <div
                    class="home-product-item-img"
                    style="
                      background-image: url(https://cf.shopee.vn/file/c4ba883648277f885e826c2d0f426d85_tn);
                    "
                  ></div>
                  <h4 class="home-product-item__name">
                    Set dưỡng trắng Whoo đông y hoàng cung Gong Jinh Yang Seol
                    Radiant
                  </h4>
                  <div class="home-product-item__price">
                    <span class="home-product-item__price-old">1.200.000</span>
                    <span class="home-product-item__price-current"
                      >999.000</span
                    >
                  </div>
                  <div class="home-product-item__action">
                    <span
                      class="home-product-item__like home-product-item__like--liked"
                    >
                      <i
                        class="home-product-item__like-icon-empty far fa-heart"
                      ></i>
                      <i
                        class="home-product-item__like-icon-fill fas fa-heart"
                      ></i>
                    </span>
                    <div class="home-product-item-rating">
                      <i class="home-product-item--gold fas fa-star"></i>
                      <i class="home-product-item--gold fas fa-star"></i>
                      <i class="home-product-item--gold fas fa-star"></i>
                      <i class="home-product-item--gold fas fa-star"></i>
                      <i class="fas fa-star"></i>
                    </div>
                    <span class="home-product-item__sold">88 đã bán</span>
                  </div>
                  <div class="home-product-item__origin">
                    <span class="home-product-item__brand">Whoo</span>
                    <span class="home-product-item__origin-name">Hàn Quốc</span>
                  </div>
                  <div class="home-product-item__favourite">
                    <i class="fas fa-check"></i>
                    <span>Yêu thích</span>
                  </div>
                  <div class="home-product-item__sale-off">
                    <span class="home-product-item__percent">10%</span>
                    <div class="home-product-item__label">GIẢM</div>
                  </div>
                </a>
              </div>
              <div class="grid__column-2-4">
                <a class="home-product-item">
                  <div
                    class="home-product-item-img"
                    style="
                      background-image: url(https://cf.shopee.vn/file/c4ba883648277f885e826c2d0f426d85_tn);
                    "
                  ></div>
                  <h4 class="home-product-item__name">
                    Set dưỡng trắng Whoo đông y hoàng cung Gong Jinh Yang Seol
                    Radiant
                  </h4>
                  <div class="home-product-item__price">
                    <span class="home-product-item__price-old">1.200.000</span>
                    <span class="home-product-item__price-current"
                      >999.000</span
                    >
                  </div>
                  <div class="home-product-item__action">
                    <span
                      class="home-product-item__like home-product-item__like--liked"
                    >
                      <i
                        class="home-product-item__like-icon-empty far fa-heart"
                      ></i>
                      <i
                        class="home-product-item__like-icon-fill fas fa-heart"
                      ></i>
                    </span>
                    <div class="home-product-item-rating">
                      <i class="home-product-item--gold fas fa-star"></i>
                      <i class="home-product-item--gold fas fa-star"></i>
                      <i class="home-product-item--gold fas fa-star"></i>
                      <i class="home-product-item--gold fas fa-star"></i>
                      <i class="fas fa-star"></i>
                    </div>
                    <span class="home-product-item__sold">88 đã bán</span>
                  </div>
                  <div class="home-product-item__origin">
                    <span class="home-product-item__brand">Whoo</span>
                    <span class="home-product-item__origin-name">Hàn Quốc</span>
                  </div>
                  <div class="home-product-item__favourite">
                    <i class="fas fa-check"></i>
                    <span>Yêu thích</span>
                  </div>
                  <div class="home-product-item__sale-off">
                    <span class="home-product-item__percent">10%</span>
                    <div class="home-product-item__label">GIẢM</div>
                  </div>
                </a>
              </div>
              <div class="grid__column-2-4">
                <a class="home-product-item">
                  <div
                    class="home-product-item-img"
                    style="
                      background-image: url(https://cf.shopee.vn/file/c4ba883648277f885e826c2d0f426d85_tn);
                    "
                  ></div>
                  <h4 class="home-product-item__name">
                    Set dưỡng trắng Whoo đông y hoàng cung Gong Jinh Yang Seol
                    Radiant
                  </h4>
                  <div class="home-product-item__price">
                    <span class="home-product-item__price-old">1.200.000</span>
                    <span class="home-product-item__price-current"
                      >999.000</span
                    >
                  </div>
                  <div class="home-product-item__action">
                    <span
                      class="home-product-item__like home-product-item__like--liked"
                    >
                      <i
                        class="home-product-item__like-icon-empty far fa-heart"
                      ></i>
                      <i
                        class="home-product-item__like-icon-fill fas fa-heart"
                      ></i>
                    </span>
                    <div class="home-product-item-rating">
                      <i class="home-product-item--gold fas fa-star"></i>
                      <i class="home-product-item--gold fas fa-star"></i>
                      <i class="home-product-item--gold fas fa-star"></i>
                      <i class="home-product-item--gold fas fa-star"></i>
                      <i class="fas fa-star"></i>
                    </div>
                    <span class="home-product-item__sold">88 đã bán</span>
                  </div>
                  <div class="home-product-item__origin">
                    <span class="home-product-item__brand">Whoo</span>
                    <span class="home-product-item__origin-name">Hàn Quốc</span>
                  </div>
                  <div class="home-product-item__favourite">
                    <i class="fas fa-check"></i>
                    <span>Yêu thích</span>
                  </div>
                  <div class="home-product-item__sale-off">
                    <span class="home-product-item__percent">10%</span>
                    <div class="home-product-item__label">GIẢM</div>
                  </div>
                </a>
              </div>
              <div class="grid__column-2-4">
                <a class="home-product-item">
                  <div
                    class="home-product-item-img"
                    style="
                      background-image: url(https://cf.shopee.vn/file/c4ba883648277f885e826c2d0f426d85_tn);
                    "
                  ></div>
                  <h4 class="home-product-item__name">
                    Set dưỡng trắng Whoo đông y hoàng cung Gong Jinh Yang Seol
                    Radiant
                  </h4>
                  <div class="home-product-item__price">
                    <span class="home-product-item__price-old">1.200.000</span>
                    <span class="home-product-item__price-current"
                      >999.000</span
                    >
                  </div>
                  <div class="home-product-item__action">
                    <span
                      class="home-product-item__like home-product-item__like--liked"
                    >
                      <i
                        class="home-product-item__like-icon-empty far fa-heart"
                      ></i>
                      <i
                        class="home-product-item__like-icon-fill fas fa-heart"
                      ></i>
                    </span>
                    <div class="home-product-item-rating">
                      <i class="home-product-item--gold fas fa-star"></i>
                      <i class="home-product-item--gold fas fa-star"></i>
                      <i class="home-product-item--gold fas fa-star"></i>
                      <i class="home-product-item--gold fas fa-star"></i>
                      <i class="fas fa-star"></i>
                    </div>
                    <span class="home-product-item__sold">88 đã bán</span>
                  </div>
                  <div class="home-product-item__origin">
                    <span class="home-product-item__brand">Whoo</span>
                    <span class="home-product-item__origin-name">Hàn Quốc</span>
                  </div>
                  <div class="home-product-item__favourite">
                    <i class="fas fa-check"></i>
                    <span>Yêu thích</span>
                  </div>
                  <div class="home-product-item__sale-off">
                    <span class="home-product-item__percent">10%</span>
                    <div class="home-product-item__label">GIẢM</div>
                  </div>
                </a>
              </div>
              <div class="grid__column-2-4">
                <a class="home-product-item">
                  <div
                    class="home-product-item-img"
                    style="
                      background-image: url(https://cf.shopee.vn/file/c4ba883648277f885e826c2d0f426d85_tn);
                    "
                  ></div>
                  <h4 class="home-product-item__name">
                    Set dưỡng trắng Whoo đông y hoàng cung Gong Jinh Yang Seol
                    Radiant
                  </h4>
                  <div class="home-product-item__price">
                    <span class="home-product-item__price-old">1.200.000</span>
                    <span class="home-product-item__price-current"
                      >999.000</span
                    >
                  </div>
                  <div class="home-product-item__action">
                    <span
                      class="home-product-item__like home-product-item__like--liked"
                    >
                      <i
                        class="home-product-item__like-icon-empty far fa-heart"
                      ></i>
                      <i
                        class="home-product-item__like-icon-fill fas fa-heart"
                      ></i>
                    </span>
                    <div class="home-product-item-rating">
                      <i class="home-product-item--gold fas fa-star"></i>
                      <i class="home-product-item--gold fas fa-star"></i>
                      <i class="home-product-item--gold fas fa-star"></i>
                      <i class="home-product-item--gold fas fa-star"></i>
                      <i class="fas fa-star"></i>
                    </div>
                    <span class="home-product-item__sold">88 đã bán</span>
                  </div>
                  <div class="home-product-item__origin">
                    <span class="home-product-item__brand">Whoo</span>
                    <span class="home-product-item__origin-name">Hàn Quốc</span>
                  </div>
                  <div class="home-product-item__favourite">
                    <i class="fas fa-check"></i>
                    <span>Yêu thích</span>
                  </div>
                  <div class="home-product-item__sale-off">
                    <span class="home-product-item__percent">10%</span>
                    <div class="home-product-item__label">GIẢM</div>
                  </div>
                </a>
              </div>
              <div class="grid__column-2-4">
                <a class="home-product-item">
                  <div
                    class="home-product-item-img"
                    style="
                      background-image: url(https://cf.shopee.vn/file/c4ba883648277f885e826c2d0f426d85_tn);
                    "
                  ></div>
                  <h4 class="home-product-item__name">
                    Set dưỡng trắng Whoo đông y hoàng cung Gong Jinh Yang Seol
                    Radiant
                  </h4>
                  <div class="home-product-item__price">
                    <span class="home-product-item__price-old">1.200.000</span>
                    <span class="home-product-item__price-current"
                      >999.000</span
                    >
                  </div>
                  <div class="home-product-item__action">
                    <span
                      class="home-product-item__like home-product-item__like--liked"
                    >
                      <i
                        class="home-product-item__like-icon-empty far fa-heart"
                      ></i>
                      <i
                        class="home-product-item__like-icon-fill fas fa-heart"
                      ></i>
                    </span>
                    <div class="home-product-item-rating">
                      <i class="home-product-item--gold fas fa-star"></i>
                      <i class="home-product-item--gold fas fa-star"></i>
                      <i class="home-product-item--gold fas fa-star"></i>
                      <i class="home-product-item--gold fas fa-star"></i>
                      <i class="fas fa-star"></i>
                    </div>
                    <span class="home-product-item__sold">88 đã bán</span>
                  </div>
                  <div class="home-product-item__origin">
                    <span class="home-product-item__brand">Whoo</span>
                    <span class="home-product-item__origin-name">Hàn Quốc</span>
                  </div>
                  <div class="home-product-item__favourite">
                    <i class="fas fa-check"></i>
                    <span>Yêu thích</span>
                  </div>
                  <div class="home-product-item__sale-off">
                    <span class="home-product-item__percent">10%</span>
                    <div class="home-product-item__label">GIẢM</div>
                  </div>
                </a>
              </div>
            </div>
          </div>

          <ul class="pagination home-product__pagination">
            <li class="pagination-item">
              <a class="pagination-item__link">
                <i class="pagination-item__icon fas fa-angle-left"></i>
              </a>
            </li>
            <li class="pagination-item pagination-item--active">
              <a class="pagination-item__link">1</a>
            </li>
            <li class="pagination-item">
              <a class="pagination-item__link">2</a>
            </li>
            <li class="pagination-item">
              <a class="pagination-item__link">3</a>
            </li>
            <li class="pagination-item">
              <a class="pagination-item__link">4</a>
            </li>
            <li class="pagination-item">
              <a class="pagination-item__link">5</a>
            </li>
            <li class="pagination-item">
              <a class="pagination-item__link">...</a>
            </li>
            <li class="pagination-item">
              <a class="pagination-item__link">14</a>
            </li>
            <li class="pagination-item">
              <a class="pagination-item__link">
                <i class="pagination-item__icon fas fa-angle-right"></i>
              </a>
            </li>
          </ul>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: "TheMain",
};
</script>

<style scoped></style>
