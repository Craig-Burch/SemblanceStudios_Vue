<template>
  <div>
    <div class="page-header clear-filter" filter-color="orange">
      <parallax
        class="page-header-image"
        style="background-image:url('img/bg5.jpg')"
      >
      </parallax>
      <div class="container">
        <div class="photo-container">
          <img src="img/ryan.jpg" alt="" />
        </div>
        <h3 class="title">Ryan Scheinder</h3>
        <p class="category">Photographer</p>
        <div class="content">
          <div class="social-description">
            <h2>26</h2>
            <p>Comments</p>
          </div>
          <div class="social-description">
            <h2>26</h2>
            <p>Comments</p>
          </div>
          <div class="social-description">
            <h2>48</h2>
            <p>Bookmarks</p>
          </div>
        </div>
      </div>
    </div>
    <div class="section">
      <div class="container">
        <div class="button-container">
          <a href="#button" class="btn btn-primary btn-round btn-lg">Follow</a>
          <a
            href="#button"
            class="btn btn-default btn-round btn-lg btn-icon"
            rel="tooltip"
            title="Follow me on Twitter"
          >
            <i class="fab fa-twitter"></i>
          </a>
          <a
            href="#button"
            class="btn btn-default btn-round btn-lg btn-icon"
            rel="tooltip"
            title="Follow me on Instagram"
          >
            <i class="fab fa-instagram"></i>
          </a>
        </div>
        <h3 class="title">About me</h3>
        <h5 class="description">
          An artist of considerable range, Ryan — the name taken by
          Melbourne-raised, Brooklyn-based Nick Murphy — writes, performs and
          records all of his own music, giving it a warm, intimate feel with a
          solid groove structure. An artist of considerable range.
        </h5>
        <div class="row">
          <div class="col-md-6 ml-auto mr-auto">
            <h4 class="title text-center">My Portfolio</h4>
          </div>
          <tabs
            pills
            class="nav-align-center"
            tab-content-classes="gallery"
            tab-nav-classes="nav-pills-just-icons"
            type="primary"
          >
            <tab-pane title="Profile">
              <i slot="label" class="now-ui-icons design_image"></i>

              <div class="col-md-10 ml-auto mr-auto">
                <div class="row collections">
                  <div class="col-md-6">
                    <img src="img/bg6.jpg" class="img-raised" />
                    <img src="img/bg11.jpg" alt="" class="img-raised" />
                  </div>
                  <div class="col-md-6">
                    <img src="img/bg7.jpg" alt="" class="img-raised" />
                    <img src="img/bg8.jpg" alt="" class="img-raised" />
                  </div>
                </div>
              </div>
            </tab-pane>

            <tab-pane title="Home">
              <i slot="label" class="now-ui-icons location_world"></i>

              <div class="col-md-10 ml-auto mr-auto">
                <div class="row collections">
                  <div class="col-md-6">
                    <img src="img/bg1.jpg" alt="" class="img-raised" />
                    <img src="img/bg3.jpg" alt="" class="img-raised" />
                  </div>
                  <div class="col-md-6">
                    <img src="img/bg8.jpg" alt="" class="img-raised" />
                    <img src="img/bg7.jpg" alt="" class="img-raised" />
                  </div>
                </div>
              </div>
            </tab-pane>

            <tab-pane title="Messages">
              <i slot="label" class="now-ui-icons sport_user-run"></i>

              <div class="col-md-10 ml-auto mr-auto">
                <div class="row collections">
                  <div class="col-md-6">
                    <img src="img/bg3.jpg" alt="" class="img-raised" />
                    <img src="img/bg8.jpg" alt="" class="img-raised" />
                  </div>
                  <div class="col-md-6">
                    <img src="img/bg7.jpg" alt="" class="img-raised" />
                    <img src="img/bg6.jpg" class="img-raised" />
                  </div>
                </div>
              </div>
            </tab-pane>
          </tabs>
        </div>
      </div>
    </div>



    <mdb-container>
    <h4 class="pb-2">Cascading cards</h4>
    <mdb-row>
      <mdb-col sm="4">
        <mdb-card wide>
          <div class="img-wrapper">
          <mdb-view>
            <mdb-card-image src="https://mdbootstrap.com/img/Photos/Horizontal/People/6-col/img%20%283%29.jpg" alt="Card image cap"></mdb-card-image>
            <mdb-mask flex-center waves zoom="white-slight"></mdb-mask>
          </mdb-view>
         </div>
          <mdb-card-body class="text-center" cascade>
            <mdb-card-title><strong>Alice Mayer</strong></mdb-card-title>
            <h5 class="indigo-text"><strong>Photographer</strong></h5>
            <mdb-card-text>Sed ut perspiciatis unde omnis iste natus sit voluptatem accusantium doloremque
              laudantium, totam rem aperiam.</mdb-card-text>
            <a class="fa-lg li-ic px-2">
              <mdb-icon fab icon="linkedin" /></a>
            <a class="fa-lg tw-ic px-2">
              <mdb-icon fab icon="twitter" /></a>
            <a class="fa-lg fb-ic px-2">
              <mdb-icon fab icon="facebook" /></a>
          </mdb-card-body>
        </mdb-card>
      </mdb-col>
      <mdb-col sm="4">
        <mdb-card narrow>
          <mdb-view hover cascade>
            <mdb-card-image src="https://mdbootstrap.com/img/Photos/Lightbox/Thumbnail/img%20(147).jpg" alt="Card image cap"></mdb-card-image>
            <mdb-mask flex-center waves overlay="white-slight"></mdb-mask>
          </mdb-view>
          <mdb-card-body cascade>
            <h5 class="pink-text pb-2 pt-1">
              <mdb-icon fab icon="utensils" /> Culinary</h5>
            <mdb-card-title>Cheat day inspirations</mdb-card-title>
            <mdb-card-text>Ut enim ad minima veniam, quis nostrum exercitationem ullam corporis suscipit
              laboriosam, nisi ut aliquid ex ea commodi.</mdb-card-text>
            <mdb-btn color="unique">Button</mdb-btn>
          </mdb-card-body>
        </mdb-card>
      </mdb-col>
      <mdb-col sm="4">
        <mdb-card cascade>
          <mdb-view hover cascade>
            <mdb-card-image src="https://mdbootstrap.com/img/Photos/Others/men.jpg" alt="Card image cap"></mdb-card-image>
            <mdb-mask flex-center waves overlay="white-slight"></mdb-mask>
          </mdb-view>
          <mdb-card-body class="text-center" cascade>
            <mdb-card-title><strong>Billy Cullen</strong></mdb-card-title>
            <h5>Web developer</h5>
            <mdb-card-text>Lorem ipsum dolor sit amet, consectetur adipisicing elit. Voluptatibus, ex,
              recusandae. Facere modi sunt, quod quibusdam.</mdb-card-text>
            <mdb-btn tag="a" floating small class="btn-fb">
              <mdb-icon fab icon="facebook" />
            </mdb-btn>
            <mdb-btn tag="a" floating small class="btn-tw">
              <mdb-icon fab icon="twitter" />
            </mdb-btn>
            <mdb-btn tag="a" floating small class="btn-dribbble">
              <mdb-icon fab icon="dribbble" />
            </mdb-btn>
          </mdb-card-body>
        </mdb-card>
      </mdb-col>
    </mdb-row>
  </mdb-container>


  </div>
</template>
<script>
import { Tabs, TabPane } from '@/components';
import { mdbContainer, mdbRow, mdbCol, mdbCard, mdbCardImage, mdbCardHeader, mdbCardBody, mdbCardTitle, mdbCardText, mdbCardFooter, mdbCardUp, mdbCardAvatar, mdbCardGroup, mdbBtn, mdbView, mdbMask, mdbIcon } from 'mdbvue';
export default {
  name: 'profile',
  bodyClass: 'profile-page',
  components: {
    Tabs,
    TabPane,

    mdbContainer,
    mdbRow,
    mdbCol,
    mdbCard,
    mdbCardImage,
    mdbCardHeader,
    mdbCardBody,
    mdbCardTitle,
    mdbCardText,
    mdbCardFooter,
    mdbCardUp,
    mdbCardAvatar,
    mdbCardGroup,
    mdbBtn,
    mdbView,
    mdbMask,
    mdbIcon
  }
};
</script>
<style>
  img:hover {
    transform:scale(1.3);
    -ms-transform:scale(1.3); /* IE 9 */
    -moz-transform:scale(1.3); /* Firefox */
    -webkit-transform:scale(1.3); /* Safari and Chrome */
    -o-transform:scale(1.3); /* Opera */
  
    transition: all 0.5s ease-in-out !important; 

}
img {
  transition: all 0.5s ease-out;
}
  
</style>
