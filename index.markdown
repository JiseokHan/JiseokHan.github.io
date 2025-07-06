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
  display: flex;
  align-items: center;      /* 세로 중앙 정렬 */
  gap: 20px;                /* 이미지와 텍스트 사이 간격 */
  flex-wrap: nowrap;        /* 줄 바꿈 방지 */
}

.profile-image {
  width: 10px;             /* 적절히 줄인 이미지 너비 */
  height: auto;             /* 원본 비율 유지 */
  flex-shrink: 0;           /* 축소 방지 */
}

.profile-text h1 {
  margin-top: 0;            /* 불필요한 여백 제거 */
}
</style>
