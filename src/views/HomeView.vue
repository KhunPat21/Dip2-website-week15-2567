<script setup>
import { toast } from 'vue3-toastify';
import 'vue3-toastify/dist/index.css';

toast.info("ยืนดีต้องรับสู่ โลกอนาคต", {
  autoClose: 1500,
  position:toast.POSITION.TOP_CENTER
})

const notify = () => {
  toast.success("ยืนดีต้องรับสู่ โลกอนาคต", {
    autoClose: 1500,
    position: toast.POSITION.TOP_CENTER
  })
  return notify
}

</script>

<template>
  <div class="container my-5">
    <div class="row row-cols-1 row-cols-md-3 g-4">
  <div class="col">
    <div class="card h-100">
      <img src="https://www.veryfastmovie.com/wp-content/uploads/2015/08/%E0%B9%82%E0%B8%94%E0%B8%A3%E0%B8%B2%E0%B9%80%E0%B8%AD%E0%B8%A1%E0%B8%AD%E0%B8%99-%E0%B9%80%E0%B8%94%E0%B8%AD%E0%B8%B0%E0%B8%A1%E0%B8%B9%E0%B8%9F%E0%B8%A7%E0%B8%B5%E0%B9%88-%E0%B8%95%E0%B8%AD%E0%B8%99-%E0%B9%82%E0%B8%99%E0%B8%9A%E0%B8%B4%E0%B8%95%E0%B8%B0%E0%B8%9C%E0%B8%B9%E0%B9%89%E0%B8%81%E0%B8%A5%E0%B9%89%E0%B8%B2%E0%B9%81%E0%B8%AB%E0%B9%88%E0%B8%87%E0%B8%AD%E0%B8%A7%E0%B8%81%E0%B8%B2%E0%B8%A8-2015-Doraemon-Nobita-and-the-Space-Heroes.jpg" class="card-img-top" alt="...">
      <div class="card-body">
        <b><h5 class="card-title">สงครามอวกาศจิ๋วของโนบิตะ</h5></b>
        <p class="card-text">ยานอวกาศขนาดเล็กเข้าโดยบังเอิญและภายในยานนั้น ได้เจอกับมนุษย์ต่างดาวขนาดจิ๋วชื่อว่า ปาปิ ซึ่งได้หลบหนีกองทัพ PCIA มาจากดาวพิริกาของเขา โดราเอมอนและผองเพื่อนจึงใช้ ไฟฉายย่อส่วน เพื่อให้มีขนาดเท่ากับปาปิ และสร้างมิตรภาพระหว่างเพื่อนกับปาปิได้ แต่แล้วเมื่อมียานอวกาศรูปปลาวาฬไล่ตามปาปิ มายังโลกเพื่อมาจับตัวปาปิ และยังโจมตี โดราเอมอนและเพื่อนๆ ปาปิจึงโทษตัวเองว่าเป็นต้นเหตุของเรื่อง ปาปิจึงลุกขึ้นต่อสู้กับกองทัพ PCIA ด้วยตัวเอง เพื่อปกป้องดาวพิริกา และช่วยเหลือปาปิ โดราเอมอนและเพื่อน ๆ จึงรวมพลังเพื่อช่วยเหลือปาปิ สหายตัวจิ๋วของพวกเขาจากเงื้อมมือของกองทัพ PCIA ที่เข้ามารุกราน</p>
      </div>
      <div class="card-footer">
        <small class="text-body-secondary">เข้าฉายวันที่ 6 ตุลาคม 2565 นี้ ในโรงภาพยนตร์</small>
      </div>
    </div>
  </div>
  <div class="col">
    <div class="card h-100">
      <img src="https://anime-titan.com/wp-content/uploads/2021/03/Doraemon-The-Movie-1990-%E0%B9%82%E0%B8%94%E0%B9%80%E0%B8%A3%E0%B8%A1%E0%B9%88%E0%B8%AD%E0%B8%99-%E0%B9%80%E0%B8%94%E0%B8%AD%E0%B8%B0%E0%B8%A1%E0%B8%B9%E0%B8%9F%E0%B8%A7%E0%B8%B5%E0%B9%88-%E0%B8%95%E0%B8%AD%E0%B8%99-%E0%B8%95%E0%B8%B0%E0%B8%A5%E0%B8%B8%E0%B8%A2%E0%B8%94%E0%B8%B2%E0%B8%A7%E0%B8%95%E0%B9%88%E0%B8%B2%E0%B8%87%E0%B8%A1%E0%B8%B4%E0%B8%95%E0%B8%B4-%E0%B8%9E%E0%B8%B2%E0%B8%81%E0%B8%A2%E0%B9%8C%E0%B9%84%E0%B8%97%E0%B8%A2.jpg" class="card-img-top" alt="...">
      <div class="card-body">
        <h5 class="card-title">โนบิตะตะลุยอาณาจักรดาวสัตว์</h5>
        <p class="card-text">เด็กหนุ่มปริศนา กับการเริ่มต้นผจญภัยอีกครั้ง
เริ่มเรื่องด้วยเด็กผู้หญิงคนหนึ่งกำลังเล่นบอลและขอให้หุ่นยนต์ตัวหนึ่งช่วยเก็บบอลให้ แต่แล้วหุ่นยนต์ตัวนั้นก็ถูกทหารดรอยด์จับตัวไปล้างโปรแกรมที่วังดรอยด์ อีกฝั่งหนึ่งหุ่นยนต์แม่ลูกมาเรียกับโปโกะกำลังหนีจากการถูกทหารดรอยด์ไล่ล่า มาเรียถูกจับตัวส่วนโปโกะกับหนึ่งในทหารหายเข้าไปในมิติเวลา</p>
      </div>
      <div class="card-footer">
        <small class="text-body-secondary">Doraemon The Movie 11 1990 </small>
      </div>
    </div>
  </div>
  <div class="col">
    <div class="card h-100">
      <img src="http://img.kapook.com/image/Movie%202/poster-doraemon_1.jpg" class="card-img-top" alt="...">
      <div class="card-body">
        <h5 class="card-title">สงครามเงือกใต้สมุทร</h5>
        <p class="card-text">ภาพยนตร์เรื่องนี้เปิดขึ้นด้วยเรือจมซึ่งฉลามกำลังว่ายน้ำอยู่ ปลาหมึกยักษ์ร่อนลงบนหัวของมันถัดจากนางเงือก เผ่าเมอร์แมนทำลายดาวเคราะห์ดวงอื่นในขณะที่ตามหาเผ่าเงือก

แม่ของโนบิตะบอกให้เขาไปซื้อของ แต่เขาเล่นกับไจแอนด์แทน แม่ของเขาถามโดราเอมอนและสามีของเธอ แต่พวกเขาปฏิเสธ โดราเอมอนซื้อของในรายการเขาเห็นโดรายากิขนมซึ่งเป็นอาหารโปรดของเขา

ซูเนโอะโชว์ภาพถ่ายดำน้ำในปาเลาให้ไจแอนด์และชิซูกะดู โนบิตะต้องการไปที่บ้านของซูเนโอะเพื่อดูภาพเพิ่มเติม แต่เขาไม่พอใจโดราเอมอนก็ปลอบใจเขา เมื่อโนบิตะต้องการดำน้ำโดราเอมอนใช้เครื่องจำลองปั๊มใต้น้ำ</p>
      </div>
      <div class="card-footer">
        <small class="text-body-secondary">ฉายในปี 18 ตุลาคม 2020</small>
      </div>
    </div>
  </div>
</div>
  </div>
</template>
