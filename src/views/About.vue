<template>
  <div class="about">
    <h1>This is an about page</h1>
    <button class="btn btn-info" @click="$dialog.datas((message = 'แจ้งเพื่อทราบ'), (type = 'info'))">Info</button>
    <button class="btn btn-success" @click="$dialog.datas((message = 'สำเร็จสิ้น'), (type = 'success'))">Success</button>
    <button class="btn btn-warning" @click="$dialog.datas((message = 'เราเตือนคุณแล้วนะ'), (type = 'warning'))">Warning</button>
    <button class="btn btn-error" @click="$dialog.datas((message = 'มีอะไรบางอย่างไม่ถูกต้อง'), (type = 'error'))">Error</button>
  </div>
</template>
