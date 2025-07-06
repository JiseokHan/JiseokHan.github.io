---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults

layout: home
# title: Home
---

<div class="profile">
  <img src="/assets/img/IMG_3929.jpeg" alt="Profile photo" class="profile-image">
  <div class="profile-text">
    <h1>JISEOK HAN, REPUBLIC OF KOREA</h1>
    <p>I am a master course student in mechanical engineering. My research goal is to bridge mechanics and biomedicine to create solutions for challenging medical issues. I enjoy hiking, futsal, and cooking in my spare time.</p>
  </div>
</div>

<style>
.profile {
  display: flex;        /* 가로로 나란히 */
  width: 100%;          /* 부모 컨테이너의 전체 너비 차지 */
  gap: 0;               /* 간격 없이 딱 반씩 */
}

.profile-image,
.profile-text {
  flex: 0 0 50%;        /* flex-grow:0, flex-shrink:0, flex-basis:50% */
  box-sizing: border-box;
}

.profile-image img {
  display: block;
  width: 100%;          /* 부모(50%)에 꽉 채우기 */
  height: auto;         /* 종횡비 유지 */
}

.profile-text {
  padding: 20px;        /* 필요 시 내부 여백 */
}

</style>
