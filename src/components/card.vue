.<template>
    <div class="card">
        <product-image-vue></product-image-vue>
        <p class="model">Kids</p>
        <p class="tipe">Yellow T-shirts</p>
        <p class="harga">$180</p>
    </div>
</template>

<script>
import productImageVue from "./product-image.vue"
export default {

components: {
productImageVue
    }
}
</script>

<style>
.card {
border: 1px solid #C4C4C4;
box-sizing: border-box;
border-radius: 16px;
width: fit-content;
padding: 8px;
margin: 8px;
}
</style>