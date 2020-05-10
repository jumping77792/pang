<template>
<v-app>
    <div>
        <v-toolbar dark color="green" >
            <v-toolbar-title>
                <nuxt-link to="/">nordebird</nuxt-link>
            </v-toolbar-title>
        <v-spacer />

            <v-toolbar-items>
                <v-text-field labe='검색' prepend-icon="mdi-magnify"/>
                <v-btn text nuxt to ='/profile' :style="{display: 'flex', alignItems: 'center'}">
                    <div>프로필</div>
                </v-btn>
                <v-btn text nuxt to ='/singup' :style="{display: 'flex', alignItems: 'center'}">
                    <div>회원가입</div>
                </v-btn>
            </v-toolbar-items>
        </v-toolbar>
       
        
    </div>
</v-app>
</template>

<script>
export default {

 head() {
   return {
     title: '디폴트레이아웃'
   }
 },
}
</script>

<style>

</style>