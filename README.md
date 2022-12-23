# 여행사이트 view 페이지 구현
HTML,CSS만을 사용한 화면구현 페이지입니다



**1. 개발 목표** : 여행사이트의 view 페이지만 구현

(HTML, CSS만을 사용하여 기능은 별도로 없습니다)

**2. 메인 사진**
![main](https://user-images.githubusercontent.com/116271236/209341462-edaffd27-b389-4a74-b5cc-15db6a3bb9c8.png)

**3. URL 주소** : 추후 예정

**4. 작업기간** : 2022. 7. 1

**5. 사용 기술**

- 언어 : HTML, CSS

- 프로그램 : vs code

**6. 주요기능**

- 캐러셀 기능을 사용하여 움직이는 사진 구현

- 인터넷 창 크기에 따라 화면 구성이 자동으로 변하는 반응형 웹으로 구성

**7. Advanced Feature**

캐러셀 기능을 사용하여 사진이 움직이는 동적인 화면을 구성하였습니다

```html
<div id="carouselExampleCaptions" class="carousel slide" data-bs-ride="carousel">
  <div class="carousel-indicators">
    <button type="button" data-bs-target="#carouselExampleCaptions" data-bs-slide-to="0" class="active" aria-current="true" aria-label="Slide 1"></button>
    <button type="button" data-bs-target="#carouselExampleCaptions" data-bs-slide-to="1" aria-label="Slide 2"></button>
    <button type="button" data-bs-target="#carouselExampleCaptions" data-bs-slide-to="2" aria-label="Slide 3"></button>
  </div>
    <div class="carousel-inner">
      <div class="carousel-item active">
        <img src="3_1_swiss.jpg" class="d-block w-100" alt="..." style="max-width: 100%; height: 500px;">
          <div class="carousel-caption d-none d-md-block">
            <h3>스위스</h3>
              <p>화려함과 매력이 가득한 나라</p>
          </div>
      </div>
      <div class="carousel-item">
        <img src="3_2_Vietnam.jpg" class="d-block w-100" alt="..." style="max-width: 100%; height: 500px;">
          <div class="carousel-caption d-none d-md-block">
            <h5>베트남</h5>
              <p>긴 역사와 전통문화를 가진 나라</p>
          </div>
      </div>
        <div class="carousel-item">
          <img src="3_3_Praha.jpg" class="d-block w-100" alt="..." style="max-width: 100%; height: 500px;">
            <div class="carousel-caption d-none d-md-block">
              <h5>프라하</h5>
                <p>잘 만들어진 예술품같은 아름다운 도시</p>
            </div>
        </div>
  </div>
</div>
  ```

**8. 개선사항** : 현재는 버튼에 기능이 없지만, 향후 각자 해당되는 기능을 넣을 예정입니다
