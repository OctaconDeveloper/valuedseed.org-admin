<template>
    <!-- Other Profile Info -->

        <div class="col-md-9">
          <div
            class="h-100 g-brd-around g-brd-gray-light-v7 g-rounded-4 g-pa-15 g-pa-20--md">
            <form class="js-validate">
              <header>
                <h2
                  class="text-uppercase g-font-size-12 g-font-size-default--md g-color-black mb-0"
                >
                  General information
                </h2>
              </header>

              <hr class="d-flex g-brd-gray-light-v7 g-my-15 g-my-30--md" />

              <div class="row g-mb-20">
                <div class="col-md-3 align-self-center g-mb-5 g-mb-0--md">
                  <label class="mb-0" for="#firstName">First Name</label>
                </div>

                <div class="col-md-9 align-self-center">
                  <div class="form-group g-pos-rel mb-0">
                    <span
                      class="g-pos-abs g-top-0 g-right-0 d-block g-width-40 h-100 opacity-0 g-opacity-1--success"
                    >
                      <i
                        class="hs-admin-check g-absolute-centered g-font-size-default g-color-secondary"
                      ></i>
                    </span>
                    <input
                      id="firstName"
                      name="firstName"
                      class="form-control form-control-md g-brd-gray-light-v7 g-brd-lightblue-v3--focus g-brd-primary--error g-rounded-4 g-px-20 g-py-12"
                      type="text"
                      value="Charlie"
                      required="required"
                      data-msg="This field is mandatory"
                      data-error-class="u-has-error-v3"
                      data-success-class="has-success"
                      aria-required="true"
                    />
                  </div>
                </div>
              </div>

              <div class="row g-mb-20">
                <div class="col-md-3 align-self-center g-mb-5 g-mb-0--md">
                  <label class="mb-0" for="#lastName">Last Name</label>
                </div>

                <div class="col-md-9 align-self-center">
                  <div class="form-group g-pos-rel mb-0">
                    <span
                      class="g-pos-abs g-top-0 g-right-0 d-block g-width-40 h-100 opacity-0 g-opacity-1--success"
                    >
                      <i
                        class="hs-admin-check g-absolute-centered g-font-size-default g-color-secondary"
                      ></i>
                    </span>
                    <input
                      id="lastName"
                      name="lastName"
                      class="form-control form-control-md g-brd-gray-light-v7 g-brd-lightblue-v3--focus g-brd-primary--error g-rounded-4 g-px-20 g-py-12"
                      type="text"
                      value="Bailey"
                      required="required"
                      data-msg="This field is mandatory"
                      data-error-class="u-has-error-v3"
                      data-success-class="has-success"
                      aria-required="true"
                    />
                  </div>
                </div>
              </div>

              <div class="row g-mb-20">
                <div class="col-md-3 align-self-center g-mb-5 g-mb-0--md">
                  <label class="mb-0">I’m</label>
                </div>

                <div class="col-md-9 align-self-center">
                  <div class="row g-mx-minus-10">
                    <div
                      class="col-md-auto align-self-center g-width-180--md g-px-10"
                    >
                      <div
                        class="form-group u-select--v2 g-pos-rel g-brd-gray-light-v7 g-rounded-4 mb-0"
                      >
                        <span
                          class="g-pos-abs g-top-0 g-right-0 d-block g-width-40 h-100 opacity-0 g-opacity-1--success"
                        >
                          <i
                            class="hs-admin-check g-absolute-centered g-font-size-default g-color-secondary"
                          ></i>
                        </span>
                        <select
                          class="js-select u-select--v2-select w-100"
                          required="required"
                          style="display: none;"
                        >
                          <option value="Male" selected="selected">Male</option>
                          <option value="Female">Female</option>
                          <option value="Others">Others</option>
                        </select>
                        <i
                          class="hs-admin-angle-down g-absolute-centered--y g-right-0 g-color-gray-light-v6 ml-auto g-mr-15"
                        ></i>
                      </div>
                    </div>

                    <div class="col align-self-center g-hidden-md-down g-px-10">
                      <span class="g-font-weight-300 g-color-gray-dark-v6"
                        >We use this only for statistics</span
                      >
                    </div>
                  </div>
                </div>
              </div>

              <div class="row g-mb-20">
                <div class="col-md-3 align-self-center g-mb-5 g-mb-0--md">
                  <label class="mb-0">State</label>
                </div>

                <div class="col-md-9 align-self-center">
                  <div class="row g-mx-minus-10">
                    <div
                      class="col-md align-self-center g-px-10 g-mb-20 g-mb-0--md"
                    >
                      <div
                        class="form-group u-select--v2 g-pos-rel g-brd-gray-light-v7 g-rounded-4 mb-0"
                      >
                        <span
                          class="g-pos-abs g-top-0 g-right-0 d-block g-width-40 h-100 opacity-0 g-opacity-1--success"
                        >
                          <i
                            class="hs-admin-check g-absolute-centered g-font-size-default g-color-secondary"
                          ></i>
                        </span>
                        <select
                          class="js-select u-select--v2-select w-100"
                          required="required"
                          style="display: none;"
                        >
                          <option>January</option>
                          <option>February</option>
                          <option>March</option>
                          <option selected="selected">Lagos</option>
                          <option>May</option>
                          <option>June</option>
                          <option>July</option>
                          <option>August</option>
                          <option>September</option>
                          <option>October</option>
                          <option>November</option>
                          <option>December</option>
                        </select>
                        <i
                          class="hs-admin-angle-down g-absolute-centered--y g-right-0 g-color-gray-light-v6 ml-auto g-mr-15"
                        ></i>
                      </div>
                    </div>
                  </div>
                </div>
              </div>
              <div class="row g-mb-20">
                <div class="col-md-3 align-self-center g-mb-5 g-mb-0--md">
                  <label class="mb-0">Country</label>
                </div>

                <div class="col-md-9 align-self-center">
                  <div class="row g-mx-minus-10">
                    <div
                      class="col-md align-self-center g-px-10 g-mb-20 g-mb-0--md"
                    >
                      <div
                        class="form-group u-select--v2 g-pos-rel g-brd-gray-light-v7 g-rounded-4 mb-0"
                      >
                        <span
                          class="g-pos-abs g-top-0 g-right-0 d-block g-width-40 h-100 opacity-0 g-opacity-1--success"
                        >
                          <i
                            class="hs-admin-check g-absolute-centered g-font-size-default g-color-secondary"
                          ></i>
                        </span>
                        <select
                          class="js-select u-select--v2-select w-100"
                          required="required"
                          style="display: none;"
                        >
                          <option>January</option>
                          <option>February</option>
                          <option>March</option>
                          <option selected="selected">Nigeria</option>
                          <option>May</option>
                          <option>June</option>
                          <option>July</option>
                          <option>August</option>
                          <option>September</option>
                          <option>October</option>
                          <option>November</option>
                          <option>December</option>
                        </select>
                        <i
                          class="hs-admin-angle-down g-absolute-centered--y g-right-0 g-color-gray-light-v6 ml-auto g-mr-15"
                        ></i>
                      </div>
                    </div>
                  </div>
                </div>
              </div>

              <div class="row g-mb-20">
                <div class="col-md-3 align-self-center g-mb-5 g-mb-0--md">
                  <label class="mb-0" for="#email">Email</label>
                </div>

                <div class="col-md-9 align-self-center">
                  <div class="form-group g-pos-rel mb-0">
                    <span
                      class="g-pos-abs g-top-0 g-right-0 d-block g-width-40 h-100 opacity-0 g-opacity-1--success"
                    >
                      <i
                        class="hs-admin-check g-absolute-centered g-font-size-default g-color-secondary"
                      ></i>
                    </span>
                    <input
                      id="email"
                      name="email"
                      class="form-control form-control-md g-brd-gray-light-v7 g-brd-lightblue-v3--focus g-brd-primary--error g-rounded-4 g-px-20 g-py-12"
                      type="email"
                      value="charlie.bailey@example.com"
                      required="required"
                      data-msg="This field is mandatory"
                      data-error-class="u-has-error-v3"
                      data-success-class="has-success"
                      aria-required="true"
                      disabled
                    />
                  </div>
                </div>
              </div>

              <div class="row g-mb-20">
                <div class="col-md-3 align-self-center g-mb-5 g-mb-0--md">
                  <label class="mb-0" for="#confirmEmail">Phone</label>
                </div>

                <div class="col-md-9 align-self-center">
                  <div class="form-group g-pos-rel mb-0">
                    <span
                      class="g-pos-abs g-top-0 g-right-0 d-block g-width-40 h-100 opacity-0 g-opacity-1--success"
                    >
                      <i
                        class="hs-admin-check g-absolute-centered g-font-size-default g-color-secondary"
                      ></i>
                    </span>
                    <input
                      id="confirmEmail"
                      name="confirmEmail"
                      class="form-control form-control-md g-brd-gray-light-v7 g-brd-lightblue-v3--focus g-brd-primary--error g-rounded-4 g-px-20 g-py-12"
                      type="email"
                      value="08090990902"
                      required="required"
                      data-msg="This field is mandatory"
                      data-error-class="u-has-error-v3"
                      data-success-class="has-success"
                      aria-required="true"
                      disabled
                    />
                  </div>
                </div>
              </div>
              <hr class="d-flex g-brd-gray-light-v7 g-my-15 g-my-30--md" />

              <div>
                <button
                  class="btn btn-md btn-xl--md u-btn-secondary g-width-160--md g-font-size-12 g-font-size-default--md g-mb-10"
                  type="submit" style=""
                >
                  Save Changes
                </button>
                <!-- <button
                  class="btn btn-md btn-xl--md u-btn-outline-gray-dark-v6 g-font-size-12 g-font-size-default--md g-mr-10 g-mb-10"
                  type="reset"
                >
                  Cancel
                </button> -->
              </div>
            </form>
          </div>
        </div>

        <!-- End Other Profile Info -->
</template>
<script>
export default {
    name:"Otherinfo"
}
</script>