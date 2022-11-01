<template>
  <ion-page>
    <ion-header :translucent="true">
      <ion-toolbar>
        <ion-title>HOME</ion-title>
      </ion-toolbar>
    </ion-header>
    <ion-content :fullscreen="true">
      <ion-grid class="kolam">
        <ion-row text-center>
          <ion-col>
            <ion-card color="dark">
              <ion-card-header>
                <ion-card-subtitle>Kolam</ion-card-subtitle>
                <ion-card-title>10</ion-card-title>
              </ion-card-header>
            </ion-card>
          </ion-col>
          <ion-col>
            <ion-card color="dark">
              <ion-card-header>
                <ion-card-subtitle>Kolam Aktif</ion-card-subtitle>
                <ion-card-title>8</ion-card-title>
              </ion-card-header>
            </ion-card>
          </ion-col>
        </ion-row>
        <ion-row>
          <ion-col>
            <ion-card color="dark">
              <ion-card-header>
                <ion-card-subtitle>Ikan Hidup</ion-card-subtitle>
                <ion-card-title
                  >182 <span class="kehidupan">Ekor</span></ion-card-title
                >
              </ion-card-header>
            </ion-card>
          </ion-col>
          <ion-col>
            <ion-card color="dark">
              <ion-card-header>
                <ion-card-subtitle>Ikan Mati</ion-card-subtitle>
                <ion-card-title
                  >89 <span class="kehidupan">Ekor</span></ion-card-title
                >
              </ion-card-header>
            </ion-card>
          </ion-col>
        </ion-row>
        <ion-row>
          <ion-col>
            <ion-card color="dark">
              <ion-card-header>
                <ion-card-subtitle>Panen 2022</ion-card-subtitle>
                <ion-card-title
                  >109 <span class="pakan">Kg</span></ion-card-title
                >
              </ion-card-header>
            </ion-card>
          </ion-col>
          <ion-col>
            <ion-card color="dark">
              <ion-card-header>
                <ion-card-subtitle>Total Pakan</ion-card-subtitle>
                <ion-card-title
                  >223 <span class="pakan">Kg</span></ion-card-title
                >
              </ion-card-header>
            </ion-card>
          </ion-col>
        </ion-row>
      </ion-grid>

      <ion-grid>
        <ion-row text-center>
          <ion-col>TOTAL BERAT IKAN</ion-col>
        </ion-row>
      </ion-grid>

      <ion-grid class="Ikan">
        <ion-slides>
          <ion-row text-center>
            <ion-col>
              <ion-card color="dark">
                      <img alt="Silhouette of mountains"
                            src="/assets/icon/lele.jpg"/>
                <ion-card-header>
                  <ion-card-subtitle class="sub one" color="light"
                    >LELE</ion-card-subtitle
                  >
                  <ion-card-title>
                    <ion-text color="primary"> 200 Kg </ion-text>
                  </ion-card-title>
                </ion-card-header>
              </ion-card>
            </ion-col>
            <ion-col>
              <ion-card color="dark">
                <img alt="Silhouette of mountains"
                            src="/assets/icon/nila.png"/>
                <ion-card-header>
                  <ion-card-subtitle class="sub two" color="light"
                    >NILA MERAH</ion-card-subtitle
                  >
                  <ion-card-title>
                    <ion-text color="primary"> 200 Kg </ion-text>
                  </ion-card-title>
                </ion-card-header>
              </ion-card>
            </ion-col>
          </ion-row>
        </ion-slides>
      </ion-grid>

      <ion-grid>
        <ion-row text-center>
        </ion-row>
      </ion-grid>
            <ion-title>
              KUALITAS AIR
            </ion-title>
            <ion-grid>
              <ion-row>
              <ion-col>
                <ion-card color = 'dark'>
                  <ion-card-header>
                    <ion-card-title>
                      pH
                    </ion-card-title>
                  </ion-card-header>
                  <ion-card-content>
                    <ion-card-subtitle>
                      Normal
                      <span style='color: #6cb5ec; display: inline-block'>
                            6 Kolam
                          </span>
                    </ion-card-subtitle>
                    <ion-card-subtitle>
                      Abnormal
                      <span style='color: #6cb5ec; display: inline-block'>
                            6 Kolam
                          </span>
                    </ion-card-subtitle>
                  </ion-card-content>
                </ion-card>
              </ion-col>
              <ion-col>
                <ion-card color = 'dark'>
                  <ion-card-header>
                    <ion-card-title>
                      DO
                    </ion-card-title>
                  </ion-card-header>
                  <ion-card-content>
                    <ion-card-subtitle>
                      Normal
                      <span style='color: #6cb5ec; display: inline-block'>
                            6 Kolam
                          </span>
                    </ion-card-subtitle>
                    <ion-card-subtitle>
                      Abnormal
                      <span style='color: #6cb5ec; display: inline-block'>
                            6 Kolam
                          </span>
                    </ion-card-subtitle>
                  </ion-card-content>
                </ion-card>
              </ion-col>
            </ion-row>
            </ion-grid>
    </ion-content>
  </ion-page>
</template>


<script lang="ts">
import { defineComponent } from "vue";
import { IonContent, IonPage, IonCol, IonRow, IonGrid, IonCard, IonCardHeader, IonCardSubtitle, IonCardTitle, IonText, IonSlides} from "@ionic/vue";
export default defineComponent({
  name: "HomePage",
  components: { IonContent, IonPage, IonCol, IonRow, IonGrid, IonCard, IonCardHeader, IonCardSubtitle, IonCardTitle, IonText, IonSlides},
});
</script>

<style scoped>
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
/* developer private css */
ion-card {
  /* padding: 0; */
  margin: 0;
}
ion-card-header {
  padding: 10px;
}
ion-text {
  font-size: 16px;
}
.font1 {
  font-size: 15px;
}
.font2 {
  color: #3880ff;
  font-weight: 600;
}
.kolam ion-card-title {
  font-weight: 1000;
}
.kolam ion-card-subtitle {
  font-weight: 600;
}

</style>