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
/* 1) 프로필 컨테이너 최대 폭 지정 + 가로 중앙 정렬 */
.profile {
  display: flex;
  align-items: flex-start;
  /* 부모보다 작거나 뷰포트보다 작게 고정 너비/퍼센트를 줍니다 */
  width: 50%;          /* 부모 너비의 90% */
  max-width: 1200px;   /* 또는 px 단위 최대값 */
  margin: 0 auto;      /* 좌우 마진 자동—가운데 정렬 */
  gap: 2rem;
  padding: 2rem 1rem;
}

/* 2) 왼쪽 이미지 영역 */
.profile-image {
  flex: 0 0 50%;        /* 컨테이너 너비의 50% 고정 */
}
.profile-image img {
  width: 50%;
  height: auto;
  display: block;
  border-radius: 8px;
  object-fit: cover;
}

/* 3) 오른쪽 텍스트 영역 */
.profile-text {
  flex: 0 0 50%;
  box-sizing: border-box;
}
.profile-text h2 {
  margin: 0 0 1rem;
  color: #298019;
  font-size: 2rem;
  line-height: 1.2;
}
.profile-text p {
  margin: 0 0 1.5rem;
  line-height: 1.6;
  color: #333;
}
.linkedin-icon {
  font-size: 1.5rem;
  color: #0077B5;
  text-decoration: none;
  display: inline-block;
}

/* 4) 모바일 대응: 768px 이하에선 세로 정렬 */
@media (max-width: 768px) {
  .profile {
    flex-direction: column;
  }
  .profile-image,
  .profile-text {
    flex: 0 0 auto;
    width: 100%;
  }
  .profile-text {
    margin-top: 1.5rem;
  }
}
</style>
