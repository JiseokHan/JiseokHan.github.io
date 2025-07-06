diff --git a/index.markdown b/index.markdown
index 06715078416fe7a0f7153a3d1e9ec351217c99ad..b761ef990db880d202fed8aa3c2f052a0e329231 100644
--- a/index.markdown
+++ b/index.markdown
@@ -1,6 +1,29 @@
 ---
 # Feel free to add content and custom Front Matter to this file.
 # To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults
 
 layout: home
+title: Home
 ---
+
+<div class="profile">
+  <img src="/assets/img/profile-placeholder.png" alt="Profile photo" class="profile-image">
+  <div class="profile-text">
+    <h1>JISEOK HAN, REPUBLIC OF KOREA</h1>
+    <p>I am a master course student in mechanical engineering. My research goal is to bridge mechanics and biomedicine to create solutions for challenging medical issues. I enjoy hiking, futsal, and cooking in my spare time.</p>
+  </div>
+</div>
+
+<style>
+.profile {
+  display: flex;
+  align-items: center;
+}
+.profile-image {
+  max-width: 200px;
+  margin-right: 20px;
+}
+.profile-text h1 {
+  margin-top: 0;
+}
+</style>
