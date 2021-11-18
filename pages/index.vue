<template>
  <div>
    <v-row justify="center" align="center">
      <v-col cols="12" sm="8" md="6">
        <div class="pa-7 white rounded-circle d-inline-block">
          <v-icon color="#0989ff" large>
            mdi-cloud-upload
          </v-icon>
        </div>
      </v-col>
    </v-row>
    <h1 style="margin-top:20px;">
      KNN Bank
    </h1>
    <h3>MOBILE APP</h3>

    <v-form>
      <v-container>
        <v-row>
          <v-col
            cols="12"
            sm="6"
            md="4"
          >
            <v-text-field
              label="PLEATE ENTER YOUR PASSWORD"
              placeholder="PASSWORD"
              filled
              rounded
              dense
              color="white"
            />
            <!-- <v-text-field
              label="PLEATE ENTER YOUR PASSWORD"
              single-line
              solo
              rounded
              color="white"
            /> -->
            <v-btn
              depressed
              class="btn1"
            >
              <span class="txt1">LOG IN</span>
            </v-btn>
            <p class="Ftxt">
              Forgot password?
            </p>
            <p class="Ftxt">
              New to Bank Apps? Sing Up
            </p>
          </v-col>
        </v-row>
      </v-container>
    </v-form>
  </div>
</template>

<style>
.pa-7{
  margin-top: 110px;
  /* 100px */
}
h3{
  margin-bottom: 50px;
}
.btn1{
  background: linear-gradient(to bottom,#ffeb3b,#FBC02D);
  margin-bottom: 50px;
}
.txt1{
  color:#4E342E;
}
.Ftxt{
  color:#CFD8DC;
}
</style>
