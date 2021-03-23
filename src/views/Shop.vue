<template>
    <div class="shop">
        <div class="container">
            <div class="row">
                <div class="col-lg-3">
                    <shop-sidebar />
                </div>
                <div class="col-lg-9">
                    <shop-content />
                    <app-pagination />                
                </div>
            </div>
        </div>
    </div>
    <the-newsletter />
</template>

<script>
import ShopSidebar from '@/components/shop/ShopSidebar'
import ShopContent from '@/components/shop/ShopContent'
import TheNewsletter from '@/components/TheNewsletter'
import AppPagination from '@/ui/AppPagination'

export default ({
    components: {ShopSidebar, ShopContent, AppPagination, TheNewsletter},
    setup() {
        
    },
})
</script>