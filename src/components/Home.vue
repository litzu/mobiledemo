<template>
  <div class="row">
    <h2>色系說明</h2>
    <ul class="nav nav-tabs mb-3 mt-3" id="tab" role="tablist">
      <li class="nav-item" role="presentation">
        <a
          class="nav-link"
          id="login-tab"
          data-bs-toggle="tab"
          href="#login"
          role="tab"
          aria-controls="login"
          aria-selected="true"
          >登入口</a
        >
      </li>
      <li class="nav-item" role="presentation">
        <a
          class="nav-link active"
          id="home-tab"
          data-bs-toggle="tab"
          href="#home"
          role="tab"
          aria-controls="home"
          aria-selected="false"
          >首頁</a
        >
      </li>
      <li class="nav-item" role="presentation">
        <a
          class="nav-link"
          id="slider-tab"
          data-bs-toggle="tab"
          href="#slider"
          role="tab"
          aria-controls="slider"
          aria-selected="false"
          >首頁側邊攔</a
        >
      </li>
      <li class="nav-item" role="presentation">
        <a
          class="nav-link"
          id="contact-tab"
          data-bs-toggle="tab"
          href="#contact"
          role="tab"
          aria-controls="contact"
          aria-selected="false"
          >內頁</a
        >
      </li>
    </ul>

    <div class="tab-content" id="tabContent">
      <!-- 首頁 -->
      <section
        class="tab-pane fade show active"
        id="home"
        role="tabpanel"
        aria-labelledby="home-tab"
      >
        <div class="container">
          <div class="row">
            <div class="card mb-3">
              <div class="row g-0">
                <div class="col-md-7">
                  <img class="w-100" src="../assets/Home/1.jpg" alt="..." />
                </div>
                <div class="col-md-5">
                  <div class="card-body">
                    <h5 class="card-title">首頁</h5>
                    <div class="card-text">
                      <ul class="list-group">
                        <li
                          class="list-group-item d-flex justify-content-between align-items-center text-left"
                        >
                          <span class="badge" style="background: #f70408"
                            >7</span
                          >
                          頭部被景色漸層-上
                        </li>
                        <li
                          class="list-group-item d-flex justify-content-between align-items-center"
                        >
                          <span class="badge" style="background: #0101f4"
                            >8</span
                          >
                          頭部被景色漸層-下
                        </li>
                        <li
                          class="list-group-item d-flex justify-content-between align-items-center"
                        >
                          <span class="badge" style="background: #fff815"
                            >9</span
                          >
                          易記域名文字顏色
                        </li>
                        <li
                          class="list-group-item d-flex justify-content-between align-items-center"
                        >
                          <span class="badge" style="background: #0bfa57"
                            >10</span
                          >
                          網址文字顏色
                        </li>
                        <li
                          class="list-group-item d-flex justify-content-between align-items-center"
                        >
                          <span class="badge" style="background: #0af7df"
                            >11</span
                          >
                          登入按鈕背景底色
                        </li>
                        <li
                          class="list-group-item d-flex justify-content-between align-items-center"
                        >
                          <span class="badge" style="background: #0b92f9"
                            >12</span
                          >
                          登入按鈕文字顏色
                        </li>
                        <li
                          class="list-group-item d-flex justify-content-between align-items-center"
                        >
                          <span class="badge" style="background: #b154f1"
                            >13</span
                          >
                          免費開戶按鈕背景底色
                        </li>
                        <li
                          class="list-group-item d-flex justify-content-between align-items-center"
                        >
                          <span class="badge" style="background: #5106cd"
                            >14</span
                          >
                          免費開戶文字顏色
                        </li>
                        <li
                          class="list-group-item d-flex justify-content-between align-items-center"
                        >
                          <span class="badge" style="background: #fdb75d"
                            >15</span
                          >
                          最新公告-背景底色
                        </li>
                        <li
                          class="list-group-item d-flex justify-content-between align-items-center"
                        >
                          <span class="badge" style="background: #0660af"
                            >16</span
                          >
                          最新公告-文字顏色
                        </li>
                        <li
                          class="list-group-item d-flex justify-content-between align-items-center"
                        >
                          <span class="badge" style="background: #786756"
                            >17</span
                          >
                          首頁遊戲分類-背景底色
                        </li>
                        <li
                          class="list-group-item d-flex justify-content-between align-items-center"
                        >
                          <span class="badge" style="background: #ec0b89"
                            >18</span
                          >
                          首頁遊戲分類-文字顏色
                        </li>
                        <li
                          class="list-group-item d-flex justify-content-between align-items-center"
                        >
                          <span class="badge" style="background: #45b449"
                            >19</span
                          >
                          首頁遊戲分類-次文字顏色
                        </li>
                        <li
                          class="list-group-item d-flex justify-content-between align-items-center"
                        >
                          <span class="badge" style="background: #01fcdb"
                            >20</span
                          >
                          首頁平台遊戲入口-背景顏色
                        </li>
                        <li
                          class="list-group-item d-flex justify-content-between align-items-center"
                        >
                          <span class="badge" style="background: #0703ee"
                            >21</span
                          >
                          首頁平台遊戲入口-文字顏色
                        </li>
                        <li
                          class="list-group-item d-flex justify-content-between align-items-center"
                        >
                          <span class="badge" style="background: #15f917"
                            >22</span
                          >
                          footer選單-漸層背景-上
                        </li>
                        <li
                          class="list-group-item d-flex justify-content-between align-items-center"
                        >
                          <span class="badge" style="background: #029239"
                            >23</span
                          >
                          footer選單-漸層背景-下
                        </li>
                        <li
                          class="list-group-item d-flex justify-content-between align-items-center"
                        >
                          <span class="badge" style="background: #f60603"
                            >24</span
                          >
                          footer選單-文字顏色
                        </li>
                        <li
                          class="list-group-item d-flex justify-content-between align-items-center"
                        >
                          <span class="badge" style="background: #1197f5"
                            >25</span
                          >
                          footer選單-文字顏色
                        </li>
                      </ul>
                    </div>
                    <p class="card-text">
                      <small class="text-muted">Last updated 3 mins ago</small>
                    </p>
                  </div>
                </div>
              </div>
            </div>
          </div>
        </div>
      </section>
      <!-- 首頁-側邊攔... -->
      <section
        class="tab-pane fade"
        id="slider"
        role="tabpanel"
        aria-labelledby="slider-tab"
      >
        <div class="container">
          <div class="row">
            <div class="card mb-3">
              <div class="row g-0">
                <div class="col-md-7">
                  <img class="w-100" src="../assets/Home/3.png" alt="..." />
                </div>
                <div class="col-md-5">
                  <div class="card-body">
                    <h5 class="card-title">首頁-側邊攔</h5>
                    <div class="card-text">
                      <ul class="list-group">
                        <li
                          class="list-group-item d-flex justify-content-between align-items-center text-left"
                        >
                          <span class="badge" style="background: #A74FE4">
                            26</span
                          >
                          上方背景底色&登入後矩形文字顏色
                        </li>
                        <li
                          class="list-group-item d-flex justify-content-between align-items-center"
                        >
                          <span class="badge" style="background: #7E4B0D"
                            >27</span
                          >
                          人頭顏色&登入後矩形底色
                        </li>
                        <li
                          class="list-group-item d-flex justify-content-between align-items-center"
                        >
                          <span class="badge" style="background: #0CB4E2"
                            >28</span
                          >
                          下方選單背景底色
                        </li>
                        <li
                          class="list-group-item d-flex justify-content-between align-items-center"
                        >
                          <span class="badge" style="background: #103B8E"
                            >29</span
                          >
                          下方選單主文字顏色
                        </li>
                        <li
                          class="list-group-item d-flex justify-content-between align-items-center"
                        >
                          <span class="badge" style="background: #FCEA16"
                            >30</span
                          >
                          下方選單次文字顏色
                        </li>
                      </ul>
                    </div>
                    <p class="card-text">
                      <small class="text-muted">Last updated 3 mins ago</small>
                    </p>
                  </div>
                </div>
              </div>
            </div>
          </div>
        </div>
      </section>
      <!-- 登入口... -->
      <section
        class="tab-pane fade"
        id="login"
        role="tabpanel"
        aria-labelledby="login-tab"
      >
        <div class="container">
          <div class="row">
            <div class="card mb-3">
              <div class="row g-0">
                <div class="col-md-7">
                  <img class="w-100" src="../assets/Home/2.jpg" alt="..." />
                </div>
                <div class="col-md-5">
                  <div class="card-body">
                    <h5 class="card-title">登入口</h5>
                    <div class="card-text">
                      <ul class="list-group">
                        <li
                          class="list-group-item d-flex justify-content-between align-items-center text-left"
                        >
                          <span class="badge" style="background: #0592f5"
                            >1</span
                          >
                          登入口-背景色
                        </li>
                        <li
                          class="list-group-item d-flex justify-content-between align-items-center"
                        >
                          <span class="badge" style="background: #f45c09"
                            >2</span
                          >
                          登入口-文字顏色&人頭顏色
                        </li>
                        <li
                          class="list-group-item d-flex justify-content-between align-items-center"
                        >
                          <span class="badge" style="background: #0cfc55"
                            >3</span
                          >
                          登入口-輸入框底色
                        </li>
                        <li
                          class="list-group-item d-flex justify-content-between align-items-center"
                        >
                          <span class="badge" style="background: #ed0d03"
                            >4</span
                          >
                          登入口-輸入框文字顏色
                        </li>
                        <li
                          class="list-group-item d-flex justify-content-between align-items-center"
                        >
                          <span class="badge" style="background: #01753d"
                            >5</span
                          >
                          登入口-按鈕底色
                        </li>
                        <li
                          class="list-group-item d-flex justify-content-between align-items-center"
                        >
                          <span class="badge" style="background: #aa02f0"
                            >6</span
                          >
                          登入口-按鈕文字顏色
                        </li>
                      </ul>
                    </div>
                    <p class="card-text">
                      <small class="text-muted">Last updated 3 mins ago</small>
                    </p>
                  </div>
                </div>
              </div>
            </div>
          </div>
        </div>
      </section>
      <section
        class="tab-pane fade"
        id="contact"
        role="tabpanel"
        aria-labelledby="contact-tab"
      >
        <div class="container">
          <div class="row">
            <div class="card mb-3">
              <div class="row g-0">
                <div class="col-md-7">
                  <img class="w-100" src="../assets/Home/4.png" alt="..." />
                </div>
                <div class="col-md-5">
                  <div class="card-body">
                    <h5 class="card-title">內頁</h5>
                    <div class="card-text">
                      <ul class="list-group">
                        <li
                          class="list-group-item d-flex justify-content-between align-items-center text-left"
                        >
                          <span class="badge" style="background: #0AA333">
                            31</span
                          >
                          內頁-橫幅背景色
                        </li>
                        <li
                          class="list-group-item d-flex justify-content-between align-items-center"
                        >
                          <span class="badge" style="background: #139BD5"
                            >32</span
                          >
                          內頁-橫幅文字顏色
                        </li>
                        <li
                          class="list-group-item d-flex justify-content-between align-items-center"
                        >
                          <span class="badge" style="background: #E86104"
                            >33</span
                          >
                          內頁-內容背景底色
                        </li>
                        <li
                          class="list-group-item d-flex justify-content-between align-items-center"
                        >
                          <span class="badge" style="background: #423D32"
                            >34</span
                          >
                          內頁-內容主文字顏色
                        </li>
                        <li
                          class="list-group-item d-flex justify-content-between align-items-center"
                        >
                          <span class="badge" style="background: #A88A58"
                            >35</span
                          >
                          內頁-內容次文字顏色
                        </li>
                        <li
                          class="list-group-item d-flex justify-content-between align-items-center"
                        >
                          <span class="badge" style="background: #116931"
                            >36</span
                          >
                          優惠按鈕背景顏色
                        </li><li
                          class="list-group-item d-flex justify-content-between align-items-center"
                        >
                          <span class="badge" style="background: #1DFAE5"
                            >37</span
                          >
                          優惠按鈕文字顏色
                        </li><li
                          class="list-group-item d-flex justify-content-between align-items-center"
                        >
                          <span class="badge" style="background: #569BDA"
                            >38</span
                          >
                          優惠&公告內頁-標題背景色
                        </li><li
                          class="list-group-item d-flex justify-content-between align-items-center"
                        >
                          <span class="badge" style="background: #F2FB39"
                            >39</span
                          >
                          優惠&公告內頁-標題文字顏色
                        </li><li
                          class="list-group-item d-flex justify-content-between align-items-center"
                        >
                          <span class="badge" style="background: #F70600"
                            >40</span
                          >
                          優惠&公告內頁-內文背景色
                        </li><li
                          class="list-group-item d-flex justify-content-between align-items-center"
                        >
                          <span class="badge" style="background: #CF59EE"
                            >41</span
                          >
                          優惠&公告內頁-內文文字顏色
                        </li>
                      </ul>
                    </div>
                    <p class="card-text">
                      <small class="text-muted">Last updated 3 mins ago</small>
                    </p>
                  </div>
                </div>
              </div>
            </div>
          </div>
        </div>
      </section>
    </div>
  </div>
</template>

<script>
export default {
  name: "Home",
};
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
</style>
