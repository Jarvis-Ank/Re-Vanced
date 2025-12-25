> ⚠️ **Repository Archived**
> 
> This repository was created before ReVanced Manager was available, when building ReVanced APKs required a PC and manual setup. It provided a Google Colab–based script to automate the build process, allowing users to generate patched APKs without a local Android environment.
> # Why this repository is archived
> 
> The official ReVanced Manager now offers a simpler, more stable, and officially supported way to build and manage ReVanced apps.
> Frequent changes in patches and build requirements make script-based automation hard to maintain.
> Google Colab limitations reduce long-term reliability for this use case.

# Re-Vanced

Google colab Re-Vanced Builder.<br>
# Contributors

<a href="https://github.com/Jarvis-Ank/Re-Vanced/graphs/contributors">
  <img src="https://contrib.rocks/image?repo=Jarvis-Ank/Re-Vanced"/>
</a>

## 4 simple steps that's it.
⭐ The project if it works. 
   Follow me for updates.

<hr>

1. Open `.ipynb` in Google [Colab](https://colab.research.google.com/github/Jarvis-Ank/Re-Vanced/blob/main/Re-Vanced.ipynb)
2. Upload and copy id for `youtube.apk` from drive.
    * Run the script, more info there.
3. Wait for the script to build, once you start it. 
4. Download your Revanced..!

<hr>

You could manually provide compilation commands.
 but by default it uses non-root method from official [docs](https://github.com/revanced/revanced-documentation/wiki/Using-the-ReVanced-CLI-and-installing-ReVanced)
with `-d device-name` omitted.
``` # Non-Root
java -jar revanced-cli-all.jar -a some.apk -c -d device-name -o revanced.apk -b revanced-patches.jar 
```

<hr>

⚠️ This is not official revanced page. 
You can find it [here](https://github.com/revanced/)
