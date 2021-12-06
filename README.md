# lesson-plan

## Flutter install

1. Download flutter tar file from [website](https://docs.flutter.dev/get-started/install/linux)
2. Extract tar file to home directory
```bash
tar -xf flutter_linux_2.5.3-stable.tar.xz -C /home/aj/
```
3. Add flutter path to your bashrc file
```bash
sudo nano ~/.bashrc


Add this > export PATH="$PATH:/home/aj/flutter/bin"
```
4. Dont for get to run this after saving your bashrc file
```bash
source ~/.bashrc
```
5. Close your current terminal and open a new one.
6. Type ```which flutter``` to check and also ```flutter doctor```
7. Now you need to download [Android Studio](https://developer.android.com/studio)
8. Extract android studio tar file to home directory

```bash
tar -xf android-studio-2020.3.1.25-linux.tar.gz -C /home/aj
```

9. After extracting cd into android studios bin folder and run ```./studio.sh``` and install

10. Then go into sdk tools and install Android SDK command-line tools
![](https://codimd.theninja.life/uploads/upload_e9b21af202bac46d5228e272ed3683ac.png)

11. Once that is installed run ``` flutter doctor --android-licenses ```

12. Lastly run ``` flutter doctor ``` to check.
