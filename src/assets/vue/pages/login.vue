<template>
<f7-page>
  <form class="list form-store-data" id="demo-form">
    <ul>
      <li class="item-content item-input">
        <div class="item-inner" style="    text-align: center;margin:50px 0px;">
          <img width="220" height="73" src="http://wallsofsteel.com/wp-content/uploads/2018/02/cropped-walls_of_steel_logo-1.png" class="custom-logo" alt="Walls of Steel" itemprop="logo">
          </div>
      </li>
      <li class="item-content item-input">
        <div class="item-inner">
          <div class="item-title item-label">Email:</div>
          <div class="item-input-wrap">
            <input name="name" type="text" placeholder="Your name">
            <span class="input-clear-button"></span>
          </div>
        </div>
      </li>
      <li class="item-content item-input">
        <div class="item-inner">
          <div class="item-title item-label">Password</div>
          <div class="item-input-wrap">
            <input name="password" type="password" placeholder="Your password">
            <span class="input-clear-button"></span>
          </div>
        </div>
      </li>
      <li class="item-content item-input">
        <div class="item-inner">
          <div class="block">
            <div class="row">
              <button class="col button button-fill button-round">Login</button>
            </div>
          </div>
        </div>
      </li>
    </ul>
  </form>
</f7-page>
</template>
<script>
import {
  f7Navbar,
  f7Page,
  f7BlockTitle
} from 'framework7-vue';

export default {
  components: {
    f7Navbar,
    f7Page,
    f7BlockTitle,
  },
};
</script>
