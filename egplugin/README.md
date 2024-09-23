This is the source for "compiling" `PulseEightPlus.egplugin`

The contents of this directory were composed by downloading the `PulseEightPlus`
snapshot from [here](https://drive.google.com/file/d/1ONPyKmcKmnPSFnrFHAA4zrBpLWb0QT7N/view?usp=sharing)
(per [../README.md#description](../README.md#description)) and then repackaging in the `.egplugin` format
as described [here](https://github.com/Pulse-Eight/libcec/issues/357#issuecomment-316842192).

You can create the `.egplugin` via:

```shell
cd ./egplugin
zip -9 -r ../PulseEightPlus.egplugin ./ -x ./README.md -x **/.DS_Store
```
