<template>
  <q-page class="bg-grey-1">
    <div class="column flex-center text-center q-py-xl bg-primary text-white" style="min-height: 500px; border-bottom-right-radius: 50px; border-bottom-left-radius: 50px;">
      <q-icon name="rocket" size="100px" class="q-mb-md animate-bounce" />
      <div class="text-h2 text-weight-bold q-mb-sm">Quasar Express App</div>
      <div class="text-h5 text-weight-light q-mb-lg opacity-80">
        สร้างเว็บแอปพลิเคชันที่สวยงาม รวดเร็ว และทรงพลัง
      </div>

      <div class="row q-gutter-md">
        <q-btn
          color="white"
          text-color="primary"
          label="เริ่มต้นใช้งาน"
          size="lg"
          rounded
          unelevated
          icon="play_arrow"
        />
        <q-btn
          outline
          color="white"
          label="เรียนรู้เพิ่มเติม"
          size="lg"
          rounded
        />
      </div>
    </div>

    <div class="q-pa-md" style="margin-top: -50px;">
      <div class="row q-col-gutter-lg justify-center">

        <div class="col-12 col-md-3">
          <q-card class="my-card shadow-10 hover-effect">
            <q-card-section class="text-center">
              <q-avatar color="teal" text-color="white" icon="speed" size="60px" class="shadow-5" />
              <div class="text-h6 q-mt-md">รวดเร็วปานสายฟ้า</div>
              <div class="text-grey-7 q-mt-sm">
                โหลดหน้าเว็บได้ทันใจด้วยเทคโนโลยี Vue.js และ Quasar Framework ล่าสุด
              </div>
            </q-card-section>
          </q-card>
        </div>

        <div class="col-12 col-md-3">
          <q-card class="my-card shadow-10 hover-effect">
            <q-card-section class="text-center">
              <q-avatar color="orange" text-color="white" icon="design_services" size="60px" class="shadow-5" />
              <div class="text-h6 q-mt-md">ดีไซน์ทันสมัย</div>
              <div class="text-grey-7 q-mt-sm">
                รองรับ Responsive Design ใช้งานได้ดีทั้งบนมือถือ แท็บเล็ต และคอมพิวเตอร์
              </div>
            </q-card-section>
          </q-card>
        </div>

        <div class="col-12 col-md-3">
          <q-card class="my-card shadow-10 hover-effect">
            <q-card-section class="text-center">
              <q-avatar color="purple" text-color="white" icon="security" size="60px" class="shadow-5" />
              <div class="text-h6 q-mt-md">ความปลอดภัยสูง</div>
              <div class="text-grey-7 q-mt-sm">
                จัดการ Version Control และระบบความปลอดภัยตามมาตรฐานสากล
              </div>
            </q-card-section>
          </q-card>
        </div>

      </div>
    </div>

    <div class="row justify-center q-py-xl">
      <div class="col-12 col-md-8 text-center">
        <div class="text-h4 text-primary q-mb-md">พร้อมที่จะเริ่มกันหรือยัง?</div>
        <p class="text-body1 text-grey-8">
          โปรเจกต์นี้ถูกสร้างขึ้นเพื่อทดสอบระบบ Git Flow และการใช้งาน Quasar Framework เบื้องต้น
        </p>
      </div>
    </div>

  </q-page>
</template>

<script setup>
// Script setup ว่างไว้ก่อน ยังไม่มี Logic
</script>

<style scoped>
/* เพิ่มลูกเล่นเล็กน้อย */
.hover-effect {
  transition: transform 0.3s;
}
.hover-effect:hover {
  transform: translateY(-10px);
}
.opacity-80 {
  opacity: 0.8;
}
</style>
