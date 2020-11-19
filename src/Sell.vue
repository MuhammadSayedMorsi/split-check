<template>
  <b-container>
    <div class="register-wrap">
      <div class="content">
        <h4>Is your business eligible to sell on SplitChek?</h4>
        <p>
          As a family-friendly gifting platform, we cater to all buyers ages
          seven and above. Therefore, to let you sell on SplitChek, we need to
          approve your business manually to make sure it is safe and appropriate
          for all ages. If you want to get approved on our platform, your
          business should meet
          <span class="__colored">all three of the criteria </span> below:
        </p>
      </div>

      <div class="__wrap-form-text">
        <div class="__content-form">
          <ul>
            <li>
              <span></span>
              Your business should be registered (ex. in Australia, an ABN is
              required)
            </li>
            <li>
              <span></span>
              You should tell us your target audience and age bracket
            </li>
            <li>
              <span></span>
              You should only sell quality products or services worth gifting
            </li>
            <li class="__colored">

              If approved, you can sell up to 100 products or services for free
            </li>
          </ul>
        </div>

        <b-card class="__form">
          <b-form>
            <div class="__group-one">
              <b-form-group
                id="input-group-1"
                label="First Name"
                label-for="input-1"
              >
                <b-form-input
                  id="input-1"
                  type="text"
                  required
                  placeholder="Enter email"
                ></b-form-input>
              </b-form-group>

              <b-form-group
                id="input-group-2"
                label="Last Name"
                label-for="input-2"
              >
                <b-form-input
                  id="input-2"
                  type="text"
                  required
                  placeholder="Enter email"
                ></b-form-input>
              </b-form-group>
            </div>

            <div class="__group-two">
              <b-form-group
                id="input-group-3"
                label="Target age group"
                label-for="input-3"
              >
                <b-form-input
                  id="input-3"
                  type="text"
                  required
                  placeholder="Enter email"
                ></b-form-input>
              </b-form-group>
              <b-form-group
                id="input-group-4"
                label="Contact number"
                label-for="input-4"
              >
                <b-form-input
                  id="input-4"
                  type="text"
                  required
                  placeholder="Contact number"
                ></b-form-input>
              </b-form-group>
            </div>
            <b-form-group
              id="input-group-5"
              label="Website (optional)"
              label-for="input-5"
            >
              <b-form-input
                id="input-5"
                type="text"
                required
                placeholder="Enter Website Url"
              ></b-form-input>
            </b-form-group>
          </b-form>
          <button class="__request-approval">Request approval</button>
        </b-card>
      </div>
    </div>
  </b-container>
</template>

<script>
export default {};
</script>

<style lang="sass" scoped>
.register-wrap
  display: flex
  justify-content: center
  align-items: center
  flex-direction: column
  .content
    width: 740px
    text-align: center
    @media (max-width: 767px)
      width: 100%
    h4
      font-size: 40px
      color: #35558F
    p
      font-size: 22px
      color: #0B0212
      .__colored
        font-family: "Neue Haas Grotesk Display Pro Medium", sans-serif

  .__wrap-form-text
    display: flex
    justify-content: space-between
    width: 100%
    .__content-form
      width: 100%
      max-width: 460px
      @media (max-width: 767px)
        width: 100%
      ul
        width: 450px
        list-style: none

        li
          margin-top: 30px
          font-size: 22px
          color: #0B0212
          span
            width: 12px
            height: 12px
            background: #FB7D00
            border-radius: 50%
            display: inline-block
        .__colored
          margin-top: 50px
          font-size: 22px
          color: #0B0212
          font-family: "Neue Haas Grotesk Display Pro Medium", sans-serif



    .__form
      width: 100%
      max-width: 640px
      background: #FFFFFF
      box-shadow: 0px 15px 50px 15px rgba(11, 2, 18, 0.04)
      border-radius: 8px
      border: 0
      input
        background-color: #F8F9FB
        border-radius: 5px
        border: 0
      .__group-one
        display: flex
        #input-group-1,
        #input-group-2
          width: 280px
          max-width: 280px

          margin-right: 16px
          @media(max-width: 767px)
            width: 100%
      .__group-two
        display: flex
        #input-group-3,
        #input-group-4
          width: 280px
          max-width: 280px

          margin-right: 16px
          @media (max-width: 767px)
            width: 100%


      #input-group-5
        width: 570px
        max-width: 570px
        @media (max-width: 100%)
          width: 100%
      .__request-approval
        background-color: #35558F
        width: 240px
        height: 48px
        margin: 56px auto
        border: 0
        outline: none
        border-radius: 5px
        font-size: 18px
        color: #fff
        font-family: "Neue Haas Grotesk Display Pro Medium", sans-serif



</style>