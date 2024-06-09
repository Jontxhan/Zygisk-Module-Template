## Zygisk Module Template
Template for your own Magisk Module.

## How to use
1. Install [Magisk](https://github.com/topjohnwu/Magisk) v24 or later and enable Zygisk
2. Build module
   - GitHub Actions
      1. Fork this repo
      2. Go to the **Actions** tab in your forked repo
      3. In the left sidebar, click the **Build** workflow.
      4. Above the list of workflow runs, select **Run workflow**
      5. Wait for the action to complete and download the artifact
   - Android Studio
      1. Download the source code
      2. Use Android Studio to run the gradle task `:module:assembleRelease` to compile, the zip package will be generated in the `out` folder
3. Install module in Magisk

## Credits
- [topjohnwu](https://github.com/topjohnwu) - [zygisk-module-sample](https://github.com/topjohnwu/zygisk-module-sample.git)
- [Perfare](https://github.com/Perfare) - [Zygisk-Il2CppDumper](https://github.com/Perfare/Zygisk-Il2CppDumper.git)
