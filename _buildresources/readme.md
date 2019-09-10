# Create a new build

- Update the task version in `Tasks\AzurePowerShellV4\task.json`
- In the root of the directory run `node make.js build --task AzurePowerShellV4`
  - This will create you the build output in `_build`
- Copy vss-extension.json and build.ps1 into `_build\task`
- update the version number in `vss-extension.json` to match the task version
- run `build.ps1`
- update the extension by uploading the visx file to `https://marketplace.visualstudio.com/manage/publishers/fiscaltechnologies`
