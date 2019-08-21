<template>
  <div class ="fullScreen">
      <!-- filter-color="orange" -->
      <!-- nice fade gradient to set up in above div if needed -->
      
      <div class="container">
        <div class="content-center">
           <div class="row justify-content-md-center">
              <img style="margin-top: 2%" class="s-logo" src="img/mainLogo2.png" alt="" />  
           </div>
          <div class="container text-center">
            <div class="row justify-content-md-center">
              <div class="col-md-12 col-lg-8">
                <h4 style="color: #74FED0; margin-top: 2%"class="title">Our Site is Currently Under Construction!</h4>
                <h5 style="color: white; margin-bottom: 4%" class="description">
                 We code, we design, we love what we do. We are a collective group of creatives that come together and create lasting brands, lasting relationships and above all, happy clients.
                </h5>
              </div>
            </div>
          </div>
          <!-- <h1 class="h1-seo">Now UI Kit.</h1>
          <h3>A beautiful Bootstrap 4 UI kit. Yours free.</h3> -->
      <div id="images">
        <div class="row">
          <div class="col-sm-4">
            <img
              v-lazy="'img/randy.png'"
              alt="Randy Img"
              class="rounded img-raised"
              style="border-radius: 30px !important;"
            />
            <p style="margin-top: 5%; color: #74FED0; text-align: center;" class="category justify-content-md-center">Randy Renninger</p>
            <p style="margin-top: -5%; color: #74FED0; text-align: center;">Graphic Designer</p>
             <RandyModal style="text-align: center; margin-top: -2%;"></RandyModal>
          </div>
          <div class="col-sm-4">
            <img
              v-lazy="'img/steve.png'"
              alt="Steve Img"
              class="rounded img-raised"
              style="border-radius: 30px !important;"
            />
            <p style="margin-top: 5%; color: #74FED0; text-align: center;" class="category">Steve Hubis</p>
            <p style="margin-top: -5%; color: #74FED0; text-align: center;">Sales and marketing</p>
            <SteveModal style="text-align: center; margin-top: -2%;"></SteveModal>
          </div>
          <div class="col-sm-4">
            <img
              v-lazy="'img/craig.png'"
              alt="Craig Img"
              class="rounded img-raised"
              style="border-radius: 30px !important;"
            />
            <p style="margin-top: 5%; color: #74FED0; text-align: center;" class="category">Craig Burch</p>
            <p style="margin-top: -5%; color: #74FED0; text-align: center;">Web Developer</p>
            <CraigModal style="text-align: center; margin-top: -2%;"></CraigModal>
          </div>
        </div>
      </div>
     </div>
     <div>
         <img style="margin-top: -60%;"
              v-lazy="'img/pattern2.png'"
              alt="pattern"
              class="hideMobile"
            />
     </div>
   </div>
    <!-- <div class="main">
      <div class="section section-images">
        <div class="container">
          <div class="row">
            <div class="col-md-12">
              <div class="hero-images-container">
                <img src="img/hero-image-1.png" alt="" />
              </div>
              <div class="hero-images-container-1">
                <img src="img/hero-image-2.png" alt="" />
              </div>
              <div class="hero-images-container-2">
                <img src="img/hero-image-3.png" alt="" />
              </div>
            </div>
          </div>
        </div>
      </div>
    </div> -->
    <!-- <basic-elements></basic-elements> -->
    <!-- <typography></typography> -->
    <!-- <navigation></navigation> -->
    <!-- <tabs-section></tabs-section> -->
    <!-- <progress-pagination></progress-pagination> -->
    <!-- <notifications></notifications> -->
    <!-- <carousel-section></carousel-section> -->
    <!-- <nucleo-icons-section></nucleo-icons-section> -->
    
    <!-- <signup-form></signup-form> -->
    <!-- <examples-section></examples-section> -->
    <!-- <download-section></download-section> -->
  </div>
</template>
<script>
import { Parallax } from '@/components';
import BasicElements from './components/BasicElementsSection';
import Card from '@/components'
import Navigation from './components/Navigation';
import TabsSection from './components/Tabs';
import ProgressPagination from './components/ProgressPagination';
import Notifications from './components/Notifications';
import Typography from './components/Typography';
import RandyModal from './components/RandyModal';
import SteveModal from './components/SteveModal';
import CraigModal from './components/CraigModal';
import CarouselSection from './components/CarouselSection';
import NucleoIconsSection from './components/NucleoIconsSection';
import SignupForm from './components/SignupForm';
import ExamplesSection from './components/ExamplesSection';
import DownloadSection from './components/DownloadSection';

export default {
  name: 'index',
  bodyClass: 'index-page',
  components: {
    Parallax,
    Card,
    BasicElements,
    Navigation,
    TabsSection,
    ProgressPagination,
    Notifications,
    Typography,
    RandyModal,
    SteveModal,
    CraigModal,
    CarouselSection,
    NucleoIconsSection,
    SignupForm,
    ExamplesSection,
    DownloadSection
  }
};
</script>
<style></style>
