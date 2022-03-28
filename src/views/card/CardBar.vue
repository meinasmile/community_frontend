<template>
  <section>
      <login-welcom/>
      <tip-card/>
      <PromotionCard/>
  </section>
  
</template>

<script>
import LoginWelcom from '@/views/card/LoginWelcome';
import TipCard from '@/views/card/Tip';
import PromotionCard from '@/views/card/Promotion';
// @ is an alias to /src


export default {
  name: 'CardBar',
  components: { LoginWelcom, TipCard, PromotionCard},
  data(){
    return {
    } 
      },
  created(){
    
  }, 
  methods: {
    
  }
};
</script>
