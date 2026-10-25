# Cube Hop - APK

## Najlakši način (bez Android Studija, samo preglednik)
1. Napravi besplatan račun na github.com i novi repozitorij (npr. "cube-hop").
2. Uploadaj SVE iz ovog zipa (ukljucujuci skrivenu mapu .github) u repozitorij.
   Najlakše: "Add file" -> "Upload files", povuci sve unutra.
3. Otvori karticu **Actions**. Build se pokrene sam (traje ~5 min).
4. Kad bude zelen, otvori ga i na dnu u "Artifacts" skini **cube-hop-apk**.
5. Raspakiraj zip -> dobiješ app-debug.apk. Prebaci na mobitel i instaliraj
   (dopusti "instalaciju iz nepoznatih izvora").

## Na računalu (Node + Android Studio)
    npm install
    npx cap add android
    npx cap sync android
    npx cap open android   # Build > Build APK(s)

Napomena: ovo je debug APK, savršen za dijeljenje prijateljima.
Za Google Play treba potpisani release build (AAB) i developer račun.
