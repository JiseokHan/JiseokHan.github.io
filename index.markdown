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
  width: 100%;
  max-width: 1200px;
  margin: 0 auto;
  align-items: flex-start;
}
.profile-image {
  flex: 0 0 50%;
}
.profile-image img {
  display: block;
  width: 100%;
  height: auto;
  border-radius: 8px;
  object-fit: cover;
}
.profile-text {
  flex: 0 0 50%;
  padding-left: 2rem;
  box-sizing: border-box;
}
.profile-text h2 {
  color: #298019;
  font-size: 2rem;
  margin: 0 0 1rem;
  line-height: 1.2;
}
.profile-text p {
  font-size: 1rem;
  line-height: 1.6;
  margin: 0 0 1.5rem;
  color: #333;
}
.linkedin-icon {
  display: inline-block;
  font-size: 1.5rem;
  color: #0077B5;
  text-decoration: none;
}

/* 모바일 전환 */
@media (max-width: 768px) {
  .profile { flex-direction: column; }
  .profile-image,
  .profile-text {
    flex: 0 0 auto;
    width: 100%;
  }
  .profile-text {
    padding-left: 0;
    margin-top: 1.5rem;
  }
}
</style>
