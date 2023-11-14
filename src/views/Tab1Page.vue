<template>
  <ion-page>
    <ion-header>
      <ion-toolbar>
        <ion-title>Tab 1</ion-title>
      </ion-toolbar>
    </ion-header>
    <ion-content :fullscreen="true">
      <ion-header collapse="condense">
        <ion-toolbar>
          <ion-title size="large">Tab 1</ion-title>
        </ion-toolbar>
      </ion-header>

      <ExploreContainer name="Tab 1 page" />
      <!-- '''' -->
      <ion-list>
    <ion-item>
      <ion-input label="Title " placeholder="Mr/Mrs"></ion-input>
    </ion-item>
    <ion-item>
      <ion-input label="Name " placeholder="(Surname) (First Name) (Other names)"></ion-input>
    </ion-item>
    <ion-item>
      <ion-input label="Date of Birth " type='date'></ion-input>
    </ion-item>
    <ion-item>
      <ion-input label="Home County " placeholder=""></ion-input>
    </ion-item>
    <ion-item>
      <ion-input label="Postal Address " placeholder=""></ion-input>
    </ion-item>
    <ion-item>
      <ion-input label="Postal code" placeholder=""></ion-input>
    </ion-item>
    <ion-item>
      <ion-input label="Town/City " placeholder=""></ion-input>
    </ion-item>
    <ion-item>
      <ion-input label="Telephone Number" type="tel" placeholder="888-888-8888"></ion-input>
    </ion-item>
    <ion-item>
      <ion-input label="Mobile Number" type="tel" placeholder="0711-XXXX-XXXX"></ion-input>
    </ion-item>

    <ion-item>
      <ion-input label="Email Address" type="email" placeholder="email@domain.com"></ion-input>
    </ion-item>

    <ion-item>
      <ion-input label="Telephone input" type="tel" placeholder="888-888-8888"></ion-input>
    </ion-item>
      <ion-item>
      <ion-input label="Name of Alternative Contact" placeholder="(Surname) (First Name) (Other names)"></ion-input>
    </ion-item>

    <ion-item>
      <ion-input label="Telephone No" type="tel" placeholder="888-888-8888"></ion-input>
    </ion-item>

     <ion-item>
      <ion-input label="Are you living with disability" placeholder=""></ion-input>
    </ion-item>
     <ion-item>
      <ion-input label="Nature of Disability" placeholder=""></ion-input>
    </ion-item>
     <ion-item>
      <ion-input label="NCPD Reg No" placeholder=""></ion-input>
    </ion-item>
     <ion-item>
      <ion-input label="NCPD Date of Registration" placeholder=""></ion-input>
    </ion-item>
  </ion-list>
      <!-- .... -->
    </ion-content>
  </ion-page>
</template>

<script setup lang="ts">
import { IonPage, IonHeader, IonToolbar, IonTitle, IonContent } from '@ionic/vue';
import ExploreContainer from '@/components/ExploreContainer.vue';
</script>
