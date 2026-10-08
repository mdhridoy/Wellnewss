LE MONDE WELLNESS FIRST CIC - MOBILE APP (Capacitor project)

APK বানানোর সবচেয়ে সহজ উপায় (কম্পিউটারে কিছু install লাগবে না):
1. github.com এ বিনামূল্যে account খুলুন, নতুন repository বানান।
2. এই ফোল্ডারের সব ফাইল (.github ফোল্ডারসহ) repository তে upload করুন।
3. Actions ট্যাব > "Build APK" > Run workflow চাপুন।
4. ৫-১০ মিনিট পর "LeMonde-APK" artifact থেকে app-debug.apk ডাউনলোড করুন।

নিজের কম্পিউটারে বানাতে: Node 20 + Android Studio লাগবে।
  npm install && npx cap add android && npx capacitor-assets generate --android && npx cap sync android
  তারপর Android Studio তে android/ ফোল্ডার খুলে Build > Build APK.

Google Play তে দিতে হলে signed release (AAB) লাগবে। debug APK শুধু test/শেয়ারের জন্য।
