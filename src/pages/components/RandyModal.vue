<template>
  <div class="section-javascript" id="RandyModal">
          <n-button class="companyGradient gradientBtn" style="font-weight: 700; font-size:16px;" id="modals" @click.native="modals.randy = true">
            Contact Me
          </n-button>
    <!-- Randy Modal -->
    <modal :show.sync="modals.randy" headerClasses="justify-content-center" style="color:black">
      <h4 slot="header" class="title title-up companyColorDark">Contact Randy</h4>
        <div class="row">
          <div class="col-4">
            <a href="tel:267-885-5347">
            <i class="companyColorDark fas fa-mobile-alt fa-4x mb-4"></i>
            </a>
          </div>
          <div class="col-4">
             <a target="_blank" href="http://renninger.design">
               <i class="companyColorDark fas fa-globe fa-4x mb-4"></i>
             </a>
          </div>
          <div class="col-4">
            <a href="mailto: semblance.randy@gmail.com">
              <i class="companyColorDark far fa-envelope-open fa-4x mb-4"></i>
            </a>
          </div>
       </div>
      <template slot="footer">
        <n-button class="buttonClose" @click.native="modals.randy = false"
          >Close</n-button
        >
      </template>
    </modal>
  </div>
</template>
<script>
import { Card, Button, Modal, FormGroupInput } from '@/components';
import { Popover, Tooltip, DatePicker } from 'element-ui';

export default {
  components: {
    Card,
    Modal,
    [Button.name]: Button
  },
  data() {
    return {
      modals: {
        randy: false
      },
    };
  }
};
</script>
<style lang="scss">
#javascriptComponents {
  .modal-buttons,
  .popover-buttons,
  .tooltip-buttons {
    .btn + .btn {
      margin-left: 3px;
    }
  }
}
</style>
