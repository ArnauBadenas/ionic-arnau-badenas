<template>
   <ion-page>
      <ion-tabs>
         <ion-router-outlet></ion-router-outlet>
         <ion-tab-bar slot="bottom">
            <ion-tab-button tab="home" href="/home">Home</ion-tab-button>
            <ion-tab-button tab="library" href="/library">Library</ion-tab-button>
            <ion-tab-button tab="search" href="/search">Search</ion-tab-button>
            <ion-tab-button tab="radio" href="/radio">Radio</ion-tab-button>
         </ion-tab-bar>
      </ion-tabs>
   </ion-page>
</template>
<script setup lang="ts">
   import {IonPage, IonTabs, IonRouterOutlet, IonTabBar, IonTabButton} from '@ionic/vue'
</script>