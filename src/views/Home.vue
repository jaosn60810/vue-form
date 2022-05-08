<template>
  <!-- 導覽列 -->
  <nav class="navbar navbar-expand-lg navbar-light bg-white">
    <div class="container">
      <!-- Logo -->
      <a class="navbar-brand fs-4" href="#"
        ><i class="bi bi-record-fill text-info"></i
        ><span class="text-dark fw-bold">小懶蟲</span></a
      >

      <!-- 漢堡 -->
      <button
        class="navbar-toggler"
        type="button"
        data-bs-toggle="collapse"
        data-bs-target="#navbarSupportedContent"
        aria-controls="navbarSupportedContent"
        aria-expanded="false"
        aria-label="Toggle navigation"
      >
        <span class="navbar-toggler-icon"></span>
      </button>

      <!-- 導覽列連結 -->
      <div class="collapse navbar-collapse" id="navbarSupportedContent">
        <ul class="navbar-nav ms-auto mb-2 mb-lg-0">
          <li class="nav-item mx-3">
            <a class="nav-link" aria-current="page" href="index.html">首頁</a>
          </li>
          <li class="nav-item mx-3">
            <a class="nav-link" href="index.html#services">服務介紹</a>
          </li>
          <li class="nav-item mx-3">
            <a class="nav-link" href="index.html#servicesCost">方案費用</a>
          </li>
          <li class="nav-item mx-3">
            <a class="nav-link" href="questionAndAnswer.html">常見問題</a>
          </li>
          <li class="nav-item mx-3">
            <a class="btn btn-info text-light" href="payment.html">購買方案</a>
          </li>
        </ul>
      </div>
    </div>
  </nav>

  <!-- banner -->
  <header class="py-7" style="background-image: url(./img/bg_paper.png)">
    <div class="container text-center">
      <h4 class="fw-bold text-info h5">HAPPY LIFE</h4>
      <h2 class="fw-bold">開始當個小懶蟲</h2>
    </div>
  </header>

  <section class="py-5 container">
    <div class="row justify-content-center">
      <div class="col-lg-8">
        <!-- 表單 -->
        <form
          action="https://docs.google.com/forms/u/1/d/e/1FAIpQLSfkCh3a4T2VFonX4XneKDnqYt4QXcP2pfy76DbxXYnvwtrAiA/formResponse"
          method="POST"
          class="p-lg-5 shadow-lg"
        >
          <!-- 填寫資料 -->
          <h3 class="deco-line mb-3 fw-bold">填寫資料</h3>

          <!-- 全名 -->
          <div class="row row-cols-1 row-cols-lg-2">
            <!-- 名字 -->
            <div class="col">
              <div class="mb-3">
                <label for="firstName" class="form-label">名字</label>
                <input
                  type="text"
                  class="form-control"
                  id="firstName"
                  placeholder="例如：小明"
                  name="entry.14600121"
                />
              </div>
            </div>

            <!-- 姓氏 -->
            <div class="col">
              <div class="mb-3">
                <label for="lastName" class="form-label">姓氏</label>
                <input
                  type="text"
                  class="form-control"
                  id="lastName"
                  placeholder="例如：陳"
                  name="entry.1961851557"
                />
              </div>
            </div>
          </div>

          <!-- 手機號碼 -->
          <div class="mb-3">
            <label for="phone" class="form-label">手機號碼</label>
            <input
              type="tel"
              class="form-control"
              id="phone"
              placeholder="例如：0912345678"
              name="entry.100148320"
            />
          </div>

          <!-- 電子郵件 -->
          <div class="mb-3">
            <label for="email" class="form-label">電子郵件</label>
            <input
              type="email"
              class="form-control"
              id="email"
              placeholder="例如：name@example.com"
              name="entry.2121659184"
            />
          </div>

          <!-- 住址 -->
          <div class="mb-3">
            <label for="address" class="form-label">住址</label>
            <input
              type="text"
              class="form-control"
              id="address"
              placeholder="例如：台北市大安區..."
              name="entry.715942379"
            />
          </div>

          <!-- 方便聯繫時間 -->
          <div class="mb-3">
            <label for="contactTime" class="form-label">方便聯繫時間</label>
            <select
              id="contactTime"
              class="form-select"
              name="entry.1233311593"
            >
              <option value="13:00-17:00">13:00-17:00</option>
              <option value="17:00-18:00">17:00-18:00</option>
              <option value="18:00-19:00">18:00-19:00</option>
              <option value="19:00-20:00">19:00-20:00</option>
            </select>
          </div>

          <!-- 加購服務 -->
          <div class="mb-3">
            <p>加購服務</p>
            <!-- 加購 1 -->
            <div class="form-check form-check-inline">
              <input
                class="form-check-input"
                type="checkbox"
                id="inlineCheckbox1"
                value="option1"
                name="entry.690287219"
              />
              <label class="form-check-label" for="inlineCheckbox1"
                >每週一清掃家裡+100</label
              >
            </div>

            <!-- 加購 2 -->
            <div class="form-check form-check-inline">
              <input
                class="form-check-input"
                type="checkbox"
                id="inlineCheckbox2"
                value="option2"
                name="entry.690287219"
              />
              <label class="form-check-label" for="inlineCheckbox2"
                >按摩+50</label
              >
            </div>

            <!-- 加購 3 -->
            <div class="form-check form-check-inline">
              <input
                class="form-check-input"
                type="checkbox"
                id="inlineCheckbox3"
                value="option2"
                name="entry.690287219"
              />
              <label class="form-check-label" for="inlineCheckbox3"
                >聽你說話+150</label
              >
            </div>
          </div>

          <!-- 備註說明 -->
          <div class="mb-5">
            <label for="exampleFormControlTextarea1" class="form-label"
              >備註說明</label
            >
            <textarea
              class="form-control"
              id="exampleFormControlTextarea1"
              rows="3"
              name="entry.771773845"
            ></textarea>
          </div>

          <!-- 表單按鈕 -->
          <div class="mb-3">
            <button type="submit" class="btn btn-info py-2 w-100 fw-bold fs-5">
              選擇方案
            </button>
          </div>
        </form>
      </div>
    </div>
  </section>

  <!-- 協助區域 -->
  <section class="py-5 bg-light">
    <div class="container">
      <h2 class="text-center mb-4 fw-bold">需要其他協助嗎？</h2>

      <!-- 卡片群組 -->
      <div
        class="row row-cols-1 row-cols-lg-3 justify-content-center gy-4 gy-lg-0"
      >
        <!-- 電話 -->
        <div class="col help-card">
          <div class="card border-0 shadow">
            <div class="card-body text-center py-4 fs-4">
              <i class="bi bi-telephone-fill text-info"></i>
              <span>07-555-666</span>
            </div>
          </div>
        </div>

        <!-- FB -->
        <a href="#" class="col help-card text-decoration-none text-dark">
          <div class="card border-0 shadow">
            <div class="card-body text-center py-4 fs-4">
              <i class="bi bi-facebook text-info"></i>
              <span>我就是個小懶蟲</span>
            </div>
          </div>
        </a>

        <!-- 常見問題 -->
        <a
          href="questionAndAnswer.html"
          class="col help-card text-decoration-none text-dark"
        >
          <div class="card border-0 shadow">
            <div class="card-body text-center py-4 fs-4">
              <i class="bi bi-question-lg text-info"></i>
              <span>常見問題</span>
            </div>
          </div>
        </a>
      </div>
    </div>
  </section>

  <footer class="bg-secondary">
    <p class="text-center text-white lh-lg py-3 m-0 fs-s-14">
      Copyright © 2021 小懶蟲.All rights reserved.
    </p>
  </footer>
</template>

<script>
// @ is an alias to /src

export default {
  name: 'Home',
};
</script>
