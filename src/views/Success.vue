<template>
  <div class="success">
    <div class="d-flex success-checkout align-items-center justify-content-center">
      <div class="col col-lg-4 text-center">
        <img src="img/success-buy.png" alt width="294" />
        <h3 class="mt-4">Sukses Order!</h3>
        <p
          class="mt-2"
        >Silakan bayar melalui nomer rekening yg sudah di berikan sebelumnya, setelah selesai transfer harap konfirmasi via chat Whatsapp melalui tombol di bawah ini.</p>
        <!--<router-link to="/">-->
        <a href="https://api.whatsapp.com/send?phone=6281316682467&text=Halo%20Bro%0A%0Aini%20bukti%0ATransfernya%20:" class="primary-btn pd-cart mt-3">Kirim bukti pembayaran</a>
        <!--</router-link>-->
      </div>
    </div>
  </div>
</template>
<script>
export default {
    name: "Success"
}
</script>