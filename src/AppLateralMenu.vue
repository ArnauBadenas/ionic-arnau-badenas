<template>
  <ion-menu content-id="main-content">
    <ion-header>
      <ion-toolbar>
        <ion-title>Contingut de menú</ion-title>
      </ion-toolbar>
    </ion-header>
    <ion-content class="ion-padding">Aquest és un menú</ion-content>
  </ion-menu>
  <ion-page id="main-content">
    <ion-header>
      <ion-toolbar>
        <ion-buttons slot="start">
          <ion-menu-button></ion-menu-button>
        </ion-buttons>
        <ion-title>Menu</ion-title>
      </ion-toolbar>
    </ion-header>
    <ion-content class="ion-padding">
      <ion-card>
        <ion-card-header>
          <ion-card-title>Hola francesc</ion-card-title>
          <ion-card-subtitle>Crec que el menu lateral que demanes és el que hi ha.</ion-card-subtitle>
        </ion-card-header>

        <ion-card-content>
          He posat aquest component perque no sabia que més posar.
        </ion-card-content>
      </ion-card>
    </ion-content>
  </ion-page>
</template>

<script setup lang="ts">
import { IonButtons, IonContent, IonHeader, IonMenu, IonMenuButton, IonPage, IonTitle, IonToolbar, IonButton, IonRouterOutlet, IonCard, IonCardContent, IonCardHeader, IonCardSubtitle, IonCardTitle } from '@ionic/vue';

</script>