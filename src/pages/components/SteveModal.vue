<template>
  <div class="section-javascript" id="SteveModal">
    
        
          <n-button style="color:black; background-color: #74FED0" id="modals" @click.native="modals.steve = true">
            Contact Me!
          </n-button>
       
   
    <!-- Randy Modal -->
    <modal :show.sync="modals.steve" headerClasses="justify-content-center" style="color:black">
      <h4 slot="header" class="title title-up">Contact Steve</h4>
      <p>
        Far far away, behind the word mountains, far from the countries Vokalia
        and Consonantia, there live the blind texts. Separated they live in
        Bookmarksgrove right at the coast of the Semantics, a large language
        ocean. A small river named Duden flows by their place and supplies it
        with the necessary regelialia. It is a paradisematic country, in which
        roasted parts of sentences fly into your mouth.
      </p>
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
