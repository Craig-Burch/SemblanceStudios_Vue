<template>
  <div class ="fullScreen">
    <div class= "heroBackgroundImage" style="">
      <div style=" " class="row">
        
          <div class="col-lg-12 text-center ">
           <img
              v-lazy="'img/favicon.png'"
              alt="Hero Logo"
              class="mg-raised"
            />
          </div>
         
        </div>
        <!-- scroll -->
        <div class="centerScroll">
        <a href="#" v-scroll-to="'#scrollDown'" >
           <div class="arrow-down">
             
           </div>
         </a>
       </div>
 
    </div>

    
    <div class="whatWeDoContainer" id="scrollDown">
      <div class="row d-flex justify-content-center text-left">
        <div class=" col-lg-6">
          <img class="s-logo" src="https://images.pexels.com/photos/270348/pexels-photo-270348.jpeg?auto=compress&cs=tinysrgb&dpr=2&h=750&w=1260" alt="logo" width="500" height="500" />
        </div>
        <div class=" col-lg-6">
          <h5>
            Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non proident, sunt in culpa qui officia deserunt mollit anim id est laborum.
          </h5>
        </div>
      </div>

      <div class="row d-flex justify-content-center text-left">
        <div class=" col-lg-6">
          <h5>
            Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non proident, sunt in culpa qui officia deserunt mollit anim id est laborum.
          </h5>
        </div>
         <div class=" col-lg-6">
          <img class="s-logo" src="https://images.pexels.com/photos/820673/pexels-photo-820673.jpeg?auto=compress&cs=tinysrgb&dpr=2&h=750&w=1260" alt="logo" width="500" height="500"/>
        </div>
      </div>
    </div>


      <div class="container">
            <div class="row d-flex justify-content-center text-center">
                <img class="s-logo" src="img/mainLogo2.png" alt="logo" />  
              <div class=" col-lg-8 marginMobile">
                <h4 style="color: #74FED0; font-weight: 700;">Our Site is Currently Under Construction!</h4>
                <h5 style="color: white; margin-bottom: 4%" class="description">
                 We code, we design, we love what we do. We are a collective group of creatives that come together and create lasting brands, lasting relationships and above all, happy clients.
                </h5>
              </div>
          </div> 
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
             <RandyModal class="marginMobile" style="text-align: center; margin-top: -2%;"></RandyModal>
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
            <CraigModal class="marginMobile" style="text-align: center; margin-top: -2%;"></CraigModal>
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
            <SteveModal class="marginMobile" style="text-align: center; margin-top: -2%;"></SteveModal>
          </div>
        </div>

     <!-- <div>
         <img style="margin-top: -60%;"
              v-lazy="'img/pattern2.png'"
              alt="pattern"
              class="hideMobile marginslogo"
            />
     </div> -->
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
