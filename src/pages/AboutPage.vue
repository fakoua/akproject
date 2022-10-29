<template>
  <div class="q-pa-md">
    <h5>Queuer</h5>
    <div class="text-weight-light">Lets queue it!</div>
    <hr />
    <h6>Author</h6>
    <q-card class="my-card" flat bordered>
      <q-card-section horizontal>
        <q-img
          class="col"
          src="https://media-exp1.licdn.com/dms/image/C4E03AQEDVJsGdhU39Q/profile-displayphoto-shrink_200_200/0/1662136254521?e=1672272000&v=beta&t=Hb2SVsL5YSRdlg7T0SD_TPP9s_22WHtusO1VN4xGQrQ"
        >
          <div class="absolute-bottom text-h6">Akram Nasrallah</div>
        </q-img>
        <q-card-actions vertical class="justify-around q-px-md">
          <q-btn
            flat
            round
            color="red"
            icon="language"
            type="a"
            href="https://github.com"
            target="_blank"
          />
          <q-btn
            flat
            round
            color="accent"
            icon="alternate_email"
            type="a"
            href="mailto:akram@gmail.com"
          />
          <q-btn
            flat
            round
            color="primary"
            icon="code"
            type="a"
            href="https://github.com"
            target="_blank"
          />
        </q-card-actions>
      </q-card-section>
    </q-card>
  </div>
</template>

<script>
export default {
  name: 'AboutPage',
};
</script>
<style scoped>
h5 {
  margin-top: 1px;
  margin-bottom: 2px;
}
.my-card {
  max-width: 320px;
}
</style>
