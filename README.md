# 미디어 쿼리 연습

<데스크탑 사이즈>

@media ( min-width:992px ){
    .desktop{
      color: red;
    }
}

![desktop](https://github.com/jji-min/Media-Query/assets/162656013/76c881a0-7594-48f0-875d-8828e14f9d35)

<태블릿 사이즈>

@media ( min-width:600px ) and ( max-width:992px ){
    .tablet{
      color: red;
    }
}

![tablet](https://github.com/jji-min/Media-Query/assets/162656013/65139f12-573c-4f0f-8241-5557e799e754)

<핸드폰 사이즈>

@media ( max-width:600px ) {
    .cellphone{
      color: red;
    }
}

![phone](https://github.com/jji-min/Media-Query/assets/162656013/6f8a5a3d-7995-43c2-9939-101b0aada6f7)

---

<가로가 긴 화면> - landscape

@media ( orientation:landscape ){
  body{
    color: green;
    display: flex;
  }
  .desktop{
    color: blue;
  }
}

![landscape](https://github.com/jji-min/Media-Query/assets/162656013/f07ee071-3135-4056-9216-a8a553bb02dd)

<세로가 긴 화면> - portrait

@media ( orientation:portrait ){
  body{
    color: orange;
  }
}

![portrait](https://github.com/jji-min/Media-Query/assets/162656013/93397b6d-ca6e-4336-9123-60a80f57c7b6)

---

<인쇄>

@media print{
  body{
    color: purple;
  }
}

![print](https://github.com/jji-min/Media-Query/assets/162656013/126c27b9-8f85-4ded-9785-a87c3d7051e1)
