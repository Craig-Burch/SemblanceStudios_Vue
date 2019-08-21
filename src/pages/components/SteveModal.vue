<template>
  <div class="section-javascript" id="SteveModal">
    
        
          <n-button style="color:black; background-color: #74FED0; font-weight: 700; font-size:16px;" id="modals" @click.native="modals.steve = true">
            Contact Me
          </n-button>
       
   
    <!-- Randy Modal -->
    <modal :show.sync="modals.steve" headerClasses="justify-content-center" style="color:black">
      <h4 slot="header" class="title title-up">Contact Steve</h4>
        <div class="row justify-content-md-center">
          <i class="fas fa-mobile-alt fa-4x col-sm-3"></i>
          <i class="far fa-envelope-open fa-4x col-sm-3"></i>
        </div>
      <template slot="footer">
        <n-button type="danger" @click.native="modals.steve = false"
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
        steve: false
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
