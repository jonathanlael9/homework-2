<template>
  <ion-page>
    <ion-header :translucent="true">
      <ion-toolbar>
        <ion-title>Kolam</ion-title>
      </ion-toolbar>
    </ion-header>

    <ion-content :fullscreen="true">
      <ion-header collapse="condense">
        <ion-toolbar>
          <ion-title size="large">Kolam</ion-title>
        </ion-toolbar>
      </ion-header>
      <div>
        <ion-card class="box">
          <ion-card-header>
            <div class="boxaktif">
              <ion-card-title style="color: black;">Alpha</ion-card-title>
              <p class="aktif">Aktif</p>
            </div>
            <div class="garis"></div>
          </ion-card-header>

          <ion-card-content>
            <img src="/assets/icon/calendar.svg"><p>01-09-2022</p>
            <img src="/assets/icon/timesheet.svg"><p>90 Hari</p>
            <img src="/assets/icon/whole_fish.svg"><P>200 Ekor</p>
          </ion-card-content>
        </ion-card>
        <ion-card class="box">
          <ion-card-header>
            <div class="boxaktif">
              <ion-card-title style="color: black;">Beta</ion-card-title>
              <p class="noaktif">Tidak Aktif</p>
            </div>
            <div class="garis"></div>
          </ion-card-header>
          <ion-card-content>
            <img src="/assets/icon/calendar.svg"><p>01-09-2022</p>
            <img src="/assets/icon/timesheet.svg"><p>90 Hari</p>
            <img src="/assets/icon/whole_fish.svg"><P>200 Ekor</p>
          </ion-card-content>
        </ion-card>
        <ion-card class="box">
          <ion-card-header>
            <div class="boxaktif">
              <ion-card-title style="color: black;">Charlie</ion-card-title>
              <p class="aktif">Aktif</p>
            </div>
            <div class="garis"></div>
          </ion-card-header>

          <ion-card-content>
            <img src="/assets/icon/calendar.svg"><p>01-09-2022</p>
            <img src="/assets/icon/timesheet.svg"><p>90 Hari</p>
            <img src="/assets/icon/whole_fish.svg"><P>200 Ekor</p>
          </ion-card-content>
        
        </ion-card>
        <ion-card class="box">
          <ion-card-header>
            <div class="boxaktif">
              <ion-card-title style="color: black;">Delta</ion-card-title>
              <p class="aktif">Aktif</p>
            </div>
            <div class="garis"></div>
          </ion-card-header>

          <ion-card-content>
            <img src="/assets/icon/calendar.svg"><p>01-09-2022</p>
            <img src="/assets/icon/timesheet.svg"><p>90 Hari</p>
            <img src="/assets/icon/whole_fish.svg"><P>200 Ekor</p>
          </ion-card-content>
        </ion-card>

        <ion-card class="box">
          <ion-card-header>
            <div class="boxaktif">
              <ion-card-title style="color: black;">Epsilon</ion-card-title>
              <p class="aktif">Aktif</p>
            </div>
            <div class="garis"></div>
          </ion-card-header>

          <ion-card-content>
            <img src="/assets/icon/calendar.svg"><p>01-09-2022</p>
            <img src="/assets/icon/timesheet.svg"><p>90 Hari</p>
            <img src="/assets/icon/whole_fish.svg"><P>200 Ekor</p>
          </ion-card-content>
        </ion-card>
      </div>
    </ion-content>
  </ion-page>
</template>
  
<script lang="ts">
import { IonContent, IonHeader, IonPage, IonTitle, IonToolbar, } from '@ionic/vue';
import { defineComponent } from 'vue';

export default defineComponent({
  name: 'PageSecond',
  components: {
    IonContent,
    IonHeader,
    IonPage,
    IonTitle,
    IonToolbar
  }
});
</script>

<style scoped>
@font-face {
    font-family: 'popreg';
    src: url(../theme/Poppins-Regular.ttf);
  }
  @font-face {
    font-family: 'poppin';
    src: url(../theme/Poppins-Bold.ttf);
  }
#container {
  text-align: center;

  position: absolute;
  left: 0;
  right: 0;
  top: 50%;
  transform: translateY(-50%);
}

#container strong {
  font-size: 20px;
  line-height: 26px;
}

#container p {
  font-size: 16px;
  line-height: 22px;

  color: #8c8c8c;

  margin: 0;
}

#container a {
  text-decoration: none;
}


.box {
  font-family: poppin;
  background-color: white;
  color: black;
  width: 98%;
  padding: 30px 25px;
  border-radius: 15px;
  margin-bottom: 30px;
}

.boxaktif{
  justify-content: space-between;
  display: flex;
  margin-bottom: 50px;
}


.aktif{
  font-family: popreg;
  font-size: 16px;
  margin-left: 5px;
  margin-bottom: -20px;
  background-color: #1B7C1A;
  text-align: center;
  vertical-align: middle;
  padding: 8px 16px;
  color: white;
  border-radius: 8px;
}

.noaktif {
  font-family: popreg;
  font-size: 16px;
  margin-left: 5px;
  margin-bottom: -20px;
  background-color: #ff0000;
  text-align: center;
  vertical-align: middle;
  padding: 8px 16px;
  color: white;
  border-radius: 8px;
}

.garis {
  margin-top: 10px;
  border-bottom: black 3px solid;
}
</style>
  