# Re-Vanced

Google colab Re-Vanced Builder.<br>
## 6 simple steps that's it.

1. Open Google [Colab](https://colab.research.google.com/)
2. Open the `.ipynb` in Colab.
4. Upload and copy id for `youtube.apk` from drive.
    * Run the script, more info there.
5. Wait for the script to build, once you start it. 
6. Download your Revanced..!



You could manually provide compilation commands.
 but by default it uses non-root method from official [docs](https://github.com/revanced/revanced-documentation/wiki/Using-the-ReVanced-CLI-and-installing-ReVanced)
with `-d device-name` omitted.
``` # Non-Root
java -jar revanced-cli-all.jar -a some.apk -c -d device-name -o revanced.apk -b revanced-patches.jar 
```
