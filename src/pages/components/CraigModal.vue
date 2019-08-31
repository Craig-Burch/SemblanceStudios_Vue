<template>
  <div class="section-javascript" id="CraigModal">
    
        
          <n-button class="companyGradient gradientBtn" style="font-weight: 700; font-size:16px;" id="modals" @click.native="modals.craig = true">
            Contact Me
          </n-button>
       
   
    <!-- Craig Modal -->
    <modal :show.sync="modals.craig" headerClasses="justify-content-center" style="color:black">
      <h4 slot="header" class="title title-up companyColorDark">Contact Craig</h4>
       <div class="row">
          <div class="col-4">
            <a class="col-md-3" href="tel:928-446-9757">
            <i class="companyColorDark fas fa-mobile-alt fa-4x mb-4"></i>
            </a>
          </div>
          <div class="col-4">
             <a target="_blank" href="http://ilovecode.tech/">
               <i class="companyColorDark fas fa-globe fa-4x mb-4"></i>
             </a>
          </div>
          <div class="col-4">
            <a href="mailto: semblance.craig@gmail.com">
              <i class="companyColorDark far fa-envelope-open fa-4x mb-4"></i>
            </a>
          </div>
       </div>
      <template slot="footer">
        <n-button class="buttonClose" @click.native="modals.craig = false"
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
        craig: false
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
