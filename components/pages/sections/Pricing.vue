<template>
  <div class="cd-section" id="pricing">
    <!--     *********    PRICING 1     *********      -->
    <div class="pricing-1 section-image" id="pricing-1" style="background-image: url('img/pricing1.jpg')">
      <div class="container">
        <div class="row">
          <div class="col-md-6 ml-auto mr-auto text-center">
            <h2 class="title">Pick the best plan for you</h2>
            <h4 class="description">
              You have Free Unlimited Updates and Premium Support on each
              package.
            </h4>
            <div class="section-space"></div>
          </div>
        </div>
        <div class="row">
          <div class="col-md-3">
            <card type="pricing" plain>
              <h6 class="category">Bravo Pack</h6>
              <div class="icon icon-warning">
                <em class="now-ui-icons media-1_button-power"></em>
              </div>
              <h3 class="card-title">$10</h3>
              <ul>
                <li>Complete documentation</li>
                <li>Working materials in Sketch</li>
              </ul>
              <n-button type="warning" round class="btn-neutral">Add to Cart</n-button>
            </card>
          </div>
          <div class="col-md-3">
            <card type="pricing">
              <h6 class="category">Alpha Pack</h6>
              <div class="icon icon-success">
                <em class="now-ui-icons objects_diamond"></em>
              </div>
              <h3 class="card-title">$67</h3>
              <ul>
                <li>Working materials in EPS</li>
                <li>6 months access to the library</li>
              </ul>
              <n-button type="success" round class="btn-success">Add to Cart</n-button>
            </card>
          </div>
          <div class="col-md-3">
            <card type="pricing" plain>
              <h6 class="category">Charlie Pack</h6>
              <div class="icon icon-success">
                <em class="now-ui-icons media-2_sound-wave"></em>
              </div>
              <h3 class="card-title">$69</h3>
              <ul>
                <li>Working materials in PSD</li>
                <li>1 year access to the library</li>
              </ul>
              <n-button type="success" round class="btn-neutral">Add to Cart</n-button>
            </card>
          </div>
          <div class="col-md-3">
            <card type="pricing" plain>
              <h6 class="category">Extra Pack</h6>
              <div class="icon icon-danger">
                <em class="now-ui-icons education_atom"></em>
              </div>
              <h3 class="card-title">$159</h3>
              <ul>
                <li>Complete documentation</li>
                <li>2GB cloud storage</li>
              </ul>
              <n-button type="danger" round class="btn-neutral">Add to Cart</n-button>
            </card>
          </div>
        </div>
      </div>
    </div>
    <!--     *********    END PRICING 1      *********      -->
    <!--     *********    PRICING 2     *********      -->
    <div class="pricing-2" id="pricing-2">
      <div class="container">
        <div class="row">
          <div class="col-md-6 ml-auto mr-auto text-center">
            <h2 class="title">Pick the best plan for you</h2>
            <tabs pills type="success" centered>
              <tab-pane label="Legal Entity"></tab-pane>
              <tab-pane label="Individual"></tab-pane>
            </tabs>
          </div>
        </div>
        <div class="row">
          <div class="col-md-4">
            <card type="pricing" plain>
              <h6 class="category">Enterprise</h6>
              <h1 class="card-title">
                <small>$</small>
                59
              </h1>
              <ul>
                <li><strong>10GB</strong> Disk Space</li>
                <li><strong>100GB</strong> Monthly Bandwidth</li>
                <li><strong>20</strong> Email Accounts</li>
                <li><strong>Unlimited</strong> subdomains</li>
              </ul>
              <n-button type="success" round> Sign Up </n-button>
            </card>
          </div>
          <div class="col-md-4">
            <card type="pricing" raised class="card-background" style="background-image: url('img/pricing2.jpg')">
              <h6 class="category text-info">Professional</h6>
              <h1 class="card-title">
                <small>$</small>
                29
              </h1>
              <ul>
                <li><strong>5GB</strong> Disk Space</li>
                <li><strong>50GB</strong> Monthly Bandwidth</li>
                <li><strong>10</strong> Email Accounts</li>
                <li><strong>Unlimited</strong> subdomains</li>
              </ul>
              <nuxt-link to="#pablo" class="btn btn-neutral btn-round"> Sign Up </nuxt-link>
            </card>
          </div>
          <div class="col-md-4">
            <card type="pricing" plain>
              <h6 class="category">Standard</h6>
              <h1 class="card-title">
                <small>$</small>
                17
              </h1>
              <ul>
                <li><strong>2GB</strong> Disk Space</li>
                <li><strong>25GB</strong> Monthly Bandwidth</li>
                <li><strong>5</strong> Email Accounts</li>
                <li><strong>Unlimited</strong> subdomains</li>
              </ul>
              <nuxt-link to="#pablo" class="btn btn-success btn-round">
                Get Started
              </nuxt-link>
            </card>
          </div>
        </div>
      </div>
    </div>
    <!--     *********    END PRICING 2      *********      -->
    <!--     *********    PRICING 3     *********      -->
    <div class="pricing-3 section-image" style="background-image: url('img/pricing3.jpg')" id="pricing-3">
      <div class="container">
        <div class="row">
          <div class="col-md-6 ml-auto mr-auto text-center">
            <h2 class="title">Pick the best plan for you</h2>
            <h4 class="description">
              You have Free Unlimited Updates on each package.
            </h4>
            <div class="section-space"></div>
          </div>
        </div>
        <div class="row">
          <div class="col-md-4 ml-auto">
            <card type="pricing">
              <h6 class="category">Freelance</h6>
              <h1 class="card-title">
                <small>$</small>
                29
                <small>/mo</small>
              </h1>
              <ul>
                <li>1 GB of space</li>
                <li>Limited Support</li>
                <li>Support at $25/hour</li>
                <li>Limited cloud access</li>
              </ul>
              <n-button type="success" round>Get Started</n-button>
            </card>
          </div>
          <div class="col-md-4 mr-auto">
            <card type="pricing" raised color="green">
              <h6 class="category">Business</h6>
              <h1 class="card-title">
                <small>$</small>
                59
                <small>/mo</small>
              </h1>
              <ul>
                <li>5 GB of space</li>
                <li>UnLimited Support</li>
                <li>Unlimited Downloads</li>
                <li>Full cloud access</li>
              </ul>
              <n-button type="neutral" round>Get Started</n-button>
            </card>
          </div>
        </div>
      </div>
    </div>
    <!--     *********    END PRICING 3      *********      -->
    <!--     *********    PRICING 4     *********      -->
    <div class="pricing-4" id="pricing-4">
      <div class="container">
        <div class="row">
          <div class="col-md-6 ml-auto mr-auto text-center">
            <h2 class="title">Pick the best plan for you</h2>
            <h4 class="description">
              You have Free Unlimited Updates and Premium Support on each
              package.
            </h4>
            <div class="section-space"></div>
          </div>
        </div>
        <div class="row">
          <div class="col-md-4">
            <card type="pricing" plain>
              <h6 class="category">Starter</h6>
              <div class="icon icon-danger">
                <em class="now-ui-icons tech_headphones"></em>
              </div>
              <h3 class="card-title">
                <small>$</small>
                10
              </h3>
              <ul>
                <li>1000 MB</li>
                <li>3 email</li>
                <li>5 Databases</li>
              </ul>
              <n-button type="danger" round>Get it Now</n-button>
            </card>
          </div>
          <div class="col-md-4">
            <card type="pricing" color="green">
              <h6 class="category">Professional</h6>
              <div class="icon icon-success">
                <em class="now-ui-icons tech_headphones"></em>
              </div>
              <h3 class="card-title">
                <small>$</small>
                40
              </h3>
              <ul>
                <li>Unlimited MB</li>
                <li>Unlimited emails</li>
                <li>Full Support</li>
              </ul>
              <nuxt-link to="#pablo" class="btn btn-neutral btn-success disabled btn-round">
                Current Plan
              </nuxt-link>
            </card>
          </div>
          <div class="col-md-4">
            <card type="pricing" plain>
              <h6 class="category">Basic</h6>
              <div class="icon icon-warning">
                <em class="now-ui-icons tech_headphones"></em>
              </div>
              <h3 class="card-title">
                <small>$</small>
                20
              </h3>
              <ul>
                <li>1000 MB</li>
                <li>3 email</li>
                <li>No Support</li>
              </ul>
              <nuxt-link to="#pablo" class="btn btn-warning btn-round">
                Upgrade Plan
              </nuxt-link>
            </card>
          </div>
        </div>
      </div>
    </div>
    <!--     *********    END PRICING 4      *********      -->
    <!--     *********    PRICING 5     *********      -->
    <div class="pricing-5 section-pricing-5 section-image" id="pricing-5" style="background-image: url('img/bg31.jpg')">
      <div class="container">
        <div class="row">
          <div class="col-md-4">
            <h2 class="title">Choose a plan for your next project</h2>
            <tabs v-model="pricing5Tab" pills type="success" no-content-space>
              <tab-pane label="Expensive"></tab-pane>
              <tab-pane label="Cheaper"></tab-pane>
            </tabs>
            <p class="description">
              You have Free Unlimited Updates and Premium Support on each
              package. You also have 20 days to request a refund if you're not
              happy with your purchase.
            </p>
          </div>
          <div class="col-md-7 ml-auto mr-auto">
            <div class="tab-content tab-space">
              <div v-if="pricing5Tab === 'Expensive'" class="tab-pane active" id="personal">
                <div class="row">
                  <div class="col-md-6">
                    <card type="pricing" raised>
                      <h6 class="category">Plus</h6>
                      <h1 class="card-title">
                        <small>$</small>
                        100
                      </h1>
                      <ul>
                        <li><strong>15</strong> Projects</li>
                        <li><strong>5GB</strong> Storage</li>
                        <li><strong>Unlimited</strong> users</li>
                        <li><strong>No time</strong> tracking</li>
                      </ul>
                      <nuxt-link to="#pablo" class="btn btn-success btn-round">
                        Buy Now!
                      </nuxt-link>
                    </card>
                  </div>
                  <div class="col-md-6">
                    <card type="pricing" plain>
                      <h6 class="category">Maximum</h6>
                      <h1 class="card-title">
                        <small>$</small>
                        120
                      </h1>
                      <ul>
                        <li><strong>25</strong> Projects</li>
                        <li><strong>15GB</strong> Storage</li>
                        <li><strong>Unlimited</strong> users</li>
                        <li><strong>No time</strong> tracking</li>
                      </ul>
                      <nuxt-link to="#pablo" class="btn btn-success btn-round">
                        Buy Now!
                      </nuxt-link>
                    </card>
                  </div>
                </div>
              </div>
              <div v-else class="tab-pane active" id="commercial">
                <div class="row">
                  <div class="col-md-6">
                    <card type="pricing" raised>
                      <h6 class="category">Standard</h6>
                      <h1 class="card-title">
                        <small>$</small>
                        20
                      </h1>
                      <ul>
                        <li><strong>5</strong> Projects</li>
                        <li><strong>2GB</strong> Storage</li>
                        <li><strong>Unlimited</strong> users</li>
                        <li><strong>No time</strong> tracking</li>
                      </ul>
                      <nuxt-link to="#pablo" class="btn btn-success btn-round">
                        Buy Now!
                      </nuxt-link>
                    </card>
                  </div>
                  <div class="col-md-6">
                    <card type="pricing" plain>
                      <h6 class="category">Premium</h6>
                      <h1 class="card-title">
                        <small>$</small>
                        60
                      </h1>
                      <ul>
                        <li><strong>7</strong> Projects</li>
                        <li><strong>3GB</strong> Storage</li>
                        <li><strong>Unlimited</strong> users</li>
                        <li><strong>No time</strong> tracking</li>
                      </ul>
                      <nuxt-link to="#pablo" class="btn btn-success btn-round">
                        Buy Now!
                      </nuxt-link>
                    </card>
                  </div>
                </div>
              </div>
            </div>
          </div>
        </div>
      </div>
    </div>
    <!--     *********    END PRICING 5      *********      -->
  </div>
</template>
<script>
import { Card, Button, Tabs, TabPane } from "@/components";

export default {
  components: {
    Card,
    Tabs,
    TabPane,
    [Button.name]: Button,
  },
  data() {
    return {
      pricing5Tab: "Expensive",
    };
  },
};
</script>
<style>
</style>
