<template>
  <NavBar />
  <UserGreet :nama="namauser" />
  <HomeCarousels />
  <ItemCard />
</template>

<script>
import NavBar from '../components/NavBar.vue'
import UserGreet from '../components/UserGreet.vue'
import HomeCarousels from '@/components/HomeCarousels.vue'
import ItemCard from '@/components/ItemCard.vue'
export default{
    components:{
        NavBar,
        UserGreet,
        HomeCarousels,
        ItemCard
    },
    data() {
      return {
        namauser: "William"
      }
    },
}
</script>
