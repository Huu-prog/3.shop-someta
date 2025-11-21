<script setup>


import Slides from '@/components/slide/Slides.vue';
import Policysection from '@/components/Theheader/Policysection.vue';
import Categories from '@/components/Theheader/Categories.vue';
import danhmucnoibat from '@/components/main/Categoryproductsection/danhmucnoibat.vue';
// import Productlist from '@/components/main/Productlist.vue';
import Casungonlua from '@/components/main/Categoryproductsection/Casungonlua.vue';
import Anphaminvanphong from '@/components/main/Categoryproductsection/Anphaminvanphong.vue';
import Dichvuinan from '@/components/main/Categoryproductsection/Dichvuinan.vue';
import inandongphuc from '@/components/main/Categoryproductsection/inandongphuc.vue';
import Quatangdoanhnghiep from '@/components/main/Categoryproductsection/Quatangdoanhnghiep.vue';
import Quatangkhachhang from '@/components/main/Categoryproductsection/Quatangkhachhang.vue';
import Hotlinefloating from '@/components/Theheader/Hotlinefloating .vue';




</script>

<template>


<Slides />

<!-- <Categories /> -->
<!-- <Productlist /> -->
<danhmucnoibat />
<Casungonlua categoryName="Ca sứ "
  categoryLink="/danh-muc/ca-su"
  :products="gomSuProducts" /> 
<Anphaminvanphong categoryName="Ấn phẩm in văn phòng"
  categoryLink="/danh-muc/ấn phẩm văn phòng"
  :products="thuyTinhProducts" />
<Dichvuinan categoryName="Dịch vụ in ấn"
  categoryLink="/danh-muc/in ấn"
  :products="vanPhongProducts" /> 
<inandongphuc categoryName="In ấn các loại áo đa dạng"
  categoryLink="/danh-muc/in ấn áo đa dạng "
  :products="vanPhongProducts" /> 
<Quatangdoanhnghiep categoryName="Quà tặng doanh nghiệp"
  categoryLink="/danh-muc/doanh nghiệp"
  :products="doanhNghiepProducts" /> 
<Quatangkhachhang
  categoryName="Quà tặng khách hàng"
  categoryLink="/danh-muc/khach-hang"
  :products="khachHangProducts"
/>
<Hotlinefloating />
<Policysection />
</template>

<style scoped></style>
